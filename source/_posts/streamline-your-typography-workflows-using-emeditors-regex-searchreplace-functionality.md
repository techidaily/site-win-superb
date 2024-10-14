---
title: Streamline Your Typography Workflows Using EmEditor's Regex Search/Replace Functionality
date: 2024-10-12T16:04:15.031Z
updated: 2024-10-14T16:07:34.141Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/5cb2e70fe5fc4984663e55071f50818b86ad28c6053861679577418a188e88c7.jpg
---

## Streamline Your Typography Workflows Using EmEditor's Regex Search/Replace Functionality

Viewing 11 posts - 1 through 11 (of 11 total)

* Author  
Posts
* October 20, 2010 at 1:10 pm [#9063](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
One feature I’ve had the need for recently is the ability to extract text matching a Regular Expression, with the actual text that is extracted matching a Replacement Expression (ie. so you can use back references from the Find RE).  
 For example, some text I wish to match is as follows:  
http://www.emeditor.com/123/321  
 where the numbers can change. When extracted, I want the numbered parts to be swapped, so in this example, the text extracted to the new document would be:  
http://www.emeditor.com/321/123  
 So, I use the following Find Regular Expression:  
http://www.emeditor.com/(d{3})/(d{3})  
 and want to use the following Replacement Expression to extract the text to a new line:  
http://www.emeditor.com/2/1n  
 It would be great if there was an easy way to do this from both the Replace dialog, Replace in Files dialog, and Find bar. For the Replace in Files, it would be handy if there was an option to either put all matches in a single new file, or have separate new documents for each file.  
 Also, maybe the Find plugin could be extended to become a Find/Replace/Extract plugin.  
 With this feature, text could be extracted/mined from files.  
October 20, 2010 at 4:52 pm [#9065](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c095e276d7d1f5ed27f91bf623e4e445?s=80&d=identicon&r=g)CrashNBurn](https://www.emeditor.com/forums/users/CrashNBurn/ "View CrashNBurn's profile")  
Member  
Find/Replace should be able to enable the “Output bar” to indicate what should be placed there:  
 1) All Found Text, and 2) All Replaced Text  
 or just 2) All Replaced Text.  
 I thought it was possible, but it appears only the “Find in Files” allows usage of the Output bar for searches.  
October 20, 2010 at 4:58 pm [#9066](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello Deipotent and CrashNBurn,  
 I will consider those options in future versions.  
 Thanks for your inputs!  
November 2, 2010 at 3:18 pm [#9087](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
Further to my suggestion, it would be useful if the Output bar could be used to display the extracted text. Even better, would be if this could be updated in realtime, similar to the incremental search, so you can see immediately the extracted text as the Find/Replacement expression is modified.  
 This would make it far easier to create the correct Find/Replacement expressions, since it would give immediate feedback on what is matched (ie. the current incremental search feature), along with what is extracted.  
 While this real-time updating is probably not feasible for Find/Replace in Files with the option “Look in Subfolders” enabled, it could come in handy when the “Look in Subfolders” is not enabled.  
November 2, 2010 at 3:18 pm [#9088](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
A few more suggestions related to extract text, plus Find/Replace In Files:  
 1) Ability to exclude file name from search results (ie. the opposite of the “Display File Names Only” option)  
 2) Similar to (1), but also option to only show matched/extracted text (ie. not the whole line).  
 3) Incremental Search option on Find/Replace In Files, which will apply to currently active document, to aid creation of Find Expression without the need to switch to normal Find/Replace windows.  
 4) Option to leave Find/Replace in Files window open after pressing Find button.  
November 2, 2010 at 8:17 pm [#9090](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c095e276d7d1f5ed27f91bf623e4e445?s=80&d=identicon&r=g)CrashNBurn](https://www.emeditor.com/forums/users/CrashNBurn/ "View CrashNBurn's profile")  
Member  
I dunno about the live-regex/Incremental search for “In Files”  
 But XNews.exe has a very useful tool built-in, “Test Regex”  
> **Pattern**: (Regex Pattern).\*(goes here).?  
> **Test String**: Example string for Regex Pattern to match goes here.  
> **Result**: \*\*\*Match\*\*\*  
> **Matched String and sub-expressions**:  
>  
>> 00) Regex Pattern to match goes here.  
>> 01) Regex Pattern  
>> 02) goes here  
The dialog has a \[Match\] and \[Close\] button, and a \[x\] Match case, checkbox.  
January 17, 2011 at 9:33 pm [#9204](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
> I dunno about the live-regex/Incremental search for “In Files”  
A tool called [BareGrep](http://www.baremetalsoft.com/baregrep/) offers live-regex/Incremental search for files, so it’s feasible, particularly given the powerful nature of computers these days. Admittedly, an option to disable it should be present though, if not required.  
> But XNews.exe has a very useful tool built-in, “Test Regex”  
EmEditor already has this functionality for Find, except it will match against the current document, rather than a Test String. Given this, I don’t see a need for a separate “Text RegEx” tool.  
January 18, 2011 at 12:15 am [#9206](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c095e276d7d1f5ed27f91bf623e4e445?s=80&d=identicon&r=g)CrashNBurn](https://www.emeditor.com/forums/users/CrashNBurn/ "View CrashNBurn's profile")  
Member  
Merely finding text in a given document (valid regex) is in no way the same functionality as displaying how a given regex breaks up into its various pieces.  
 These days if a particular regex is being difficult, I’ll likely just Run a 3 line AHK script and messageBox the output.  
April 17, 2014 at 8:03 am [#18285](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
In the hope I can finally persuade Yutaka to fully implement text extraction capability to EmEditor, I thought I’d revisit this thread :) Let me try to explain what I’m after:  
EE v14.0 beta 1 added the ability to “Display only matched strings” in the Output bar for Find In Files. This allows text to be extracted from files matching the Find pattern (including RegEx). This is useful, but it can easily be made a lot more powerful/useful.  
1) Output option to “Display only strings matching Replace pattern” – this allows you to extract text matching a pattern, but manipulate the matched text with the Replace pattern. For example, suppose I have the following text in a file:  
```  
AJCKDDSVCDhttp://www.emeditor.com/123/321 osajknosdnkojsdnfksd  
http://www.emeditor.com/223/321 gfdbfdgbnfdgfdgfdg  
fdgfdgfdgdfghttp://www.emeditor.com/323/321 fdgfdgfdgfdgfdghttp://www.emeditor.com/423/321 fdgfdgfdg  
http://www.emeditor.com/523/321 fdgfdgfdgfdgfdgfdg  
```  
and want to extract all the URL’s, but switch the two path components (ie. 1st URL becomes `http://www.emeditor.com/321/123`). I might use a Find pattern of  
`http://www.emeditor.com/(\d{3})/(\d{3})`  
and Replace pattern of  
`http://www.emeditor.com/\2/\1`  
If I could specify an Output option of “Display only strings matching Replace pattern”, then I would see the following in the Output Bar:  
```  
http://www.emeditor.com/321/123  
http://www.emeditor.com/321/223  
http://www.emeditor.com/321/323  
http://www.emeditor.com/321/423  
http://www.emeditor.com/321/523  
```  
So, I’ve managed to extract all URL’s but also switch over the path components of the URL.  
April 17, 2014 at 8:18 am [#18287](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
– Often, you may just want to extract text from the current document (or all open documents), so the “Use Output Bar” option and “Output Options drop-down” should be added to the Find and Replace dialogs.  
– To aid in regex construction, and to visually see what will being matched, the Output Bar should be updated with matches when “Incremental Search” is enabled (similar to how the text matching the Find pattern is updated as you type into the Find box).  
– Incremental Search option on Find/Replace In Files, which will apply to currently active document, to aid creation of Find Expression without the need to switch to normal Find/Replace windows.  
– Option to leave Find/Replace in Files window open after pressing Find button.  
– As you may want to do further processing on extracted text, a “Copy to new document” button in the Output Bar header (to the right of the text “Output”) would make this easy. ie. one click would create a new document containing the contents of the Output Bar.  
Member CrashNBurn also wanted the Output option, “Display only text matching find pattern and also text matching Replace pattern”  
As already mentioned, EmEditor already has the capability to do all the above. eg. When “Use Output Bar” checkbox state changes, show or hide the Output Bar. When incremental matches are being highlighted in document, update Output Bar (if enabled) with matches.  
April 17, 2014 at 8:20 am [#18288](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/c962eeb8483fd8ad7d82a003f8405439?s=80&d=identicon&r=g)Deipotent](https://www.emeditor.com/forums/users/deipotent/ "View Deipotent's profile")  
Participant  
To allow extraction of a lot of text, it might be worth replacing the current Output Bar editor control with the same control used for editing documents (which supports massive files), although I would be happy without this.
* Author  
Posts

Viewing 11 posts - 1 through 11 (of 11 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-expertise-amplified-10-must-know-canva-techniques-for-2024/"><u>[New] Expertise Amplified 10 Must-Know Canva Techniques for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-decoding-the-new-apeaksoft-screenscape-expert-analysis/"><u>[New] In 2024, Decoding the New Apeaksoft Screenscape Expert Analysis</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-proven-techniques-for-effective-video-transfer-ios-to-mac-for-2024/"><u>[Updated] Proven Techniques for Effective Video Transfer IOS to MAC for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-secret-handbook-to-instagrams-exclusive-club-elevating-your-profile-with-six-tips-for-2024/"><u>[Updated] The Secret Handbook to Instagram's Exclusive Club Elevating Your Profile with Six Tips for 2024</u></a></li>
<li><a href="https://win-superb.techidaily.com/emeditor-text-editor-guide-configuring-sticky-vertical-mode-java-macros-tutorial/"><u>EmEditor Text Editor Guide: Configuring Sticky Vertical Mode - Java Macros Tutorial</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-data-from-apple-iphone-14-plus-to-zte-phones-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Data from Apple iPhone 14 Plus to ZTE Phones | Dr.fone</u></a></li>
<li><a href="https://win-superb.techidaily.com/new-release-emeditor-professional-suite-v1460-beta-edition-next-level-text-editor-experience/"><u>New Release: EmEditor Professional Suite v14.6.0 Beta Edition – Next-Level Text Editor Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-11-display-dilemma-with-this-guide-to-fix-hdmi-tv-recognition/"><u>Resolve Your Windows 11 Display Dilemma with This Guide to Fix HDMI TV Recognition</u></a></li>
<li><a href="https://win-superb.techidaily.com/resolving-the-phantom-character-issue-with-emeditor-step-by-step-solutions/"><u>Resolving the Phantom Character Issue with EmEditor - Step-by-Step Solutions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/revolutionized-ios-screenshot-and-recording-methods-for-2024/"><u>Revolutionized iOS Screenshot & Recording Methods for 2024</u></a></li>
<li><a href="https://win-superb.techidaily.com/ultimate-text-editing-software-emeditor-your-perfect-digital-wordsmith-companion/"><u>Ultimate Text Editing Software: EmEditor, Your Perfect Digital Wordsmith Companion</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972679/19272" target="_top" id="1972679">
  <img src="//a.impactradius-go.com/display-ad/19272-1972679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

