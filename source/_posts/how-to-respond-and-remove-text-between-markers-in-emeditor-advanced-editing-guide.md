---
title: How to Respond & Remove Text Between Markers in EmEditor - Advanced Editing Guide
date: 2024-10-07T16:01:14.919Z
updated: 2024-10-14T16:14:15.249Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/3b2bc9a3a892785318d5d0f2114220ad982ea100320932632e38a5b677339306.jpg
---

## How to Respond & Remove Text Between Markers in EmEditor - Advanced Editing Guide

November 14, 2006 at 7:41 pm [#4006](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

You can use the following macros (JavaScript):
  

	// Delete lines between bookmarks  

	bSuccess = false;  

	if(document.selection.NextBookmark()){  

	    y1 = document.selection.GetActivePointY(eePosLogical);  

	    if(document.selection.NextBookmark()){  

	        y2 = document.selection.GetActivePointY(eePosLogical);  

	        document.selection.SetActivePoint(eePosLogical, 1, y1, false);  

	        document.selection.SetActivePoint(eePosLogical, 1, y2, true);  

	        document.selection.Delete(1);  

	        bSuccess = true;  

	if(!bSuccess){  

	    alert("Cannot find bookmarks. The cursor position must be above both bookmarks before you run this macro.")  

	  

	// Copy lines between bookmarks  

	bSuccess = false;  

	if(document.selection.NextBookmark()){  

	    y1 = document.selection.GetActivePointY(eePosLogical);  

	    if(document.selection.NextBookmark()){  

	        y2 = document.selection.GetActivePointY(eePosLogical);  

	        document.selection.SetActivePoint(eePosLogical, 1, y1, false);  

	        document.selection.SetActivePoint(eePosLogical, 1, y2, true);  

	        document.selection.Copy(eeCopyUnicode);  

	        bSuccess = true;  

	if(!bSuccess){  

	    alert("Cannot find bookmarks. The cursor position must be above both bookmarks before you run this macro.")  

	  

	// Cut lines between bookmarks  

	bSuccess = false;  

	if(document.selection.NextBookmark()){  

	    y1 = document.selection.GetActivePointY(eePosLogical);  

	    if(document.selection.NextBookmark()){  

	        y2 = document.selection.GetActivePointY(eePosLogical);  

	        document.selection.SetActivePoint(eePosLogical, 1, y1, false);  

	        document.selection.SetActivePoint(eePosLogical, 1, y2, true);  

	        document.selection.Cut();  

	        bSuccess = true;  

	if(!bSuccess){  

	    alert("Cannot find bookmarks. The cursor position must be above both bookmarks before you run this macro.")

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-comparing-recording-obs-studio-versus-bandicam/"><u>[New] In 2024, Comparing Recording OBS Studio Versus Bandicam</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-master-your-fb-video-archive-with-1-5-choices/"><u>[New] In 2024, Master Your FB Video Archive with #1-5 Choices</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-unlock-the-potential-of-live-streaming-facebook-via-obs-devices/"><u>[New] Unlock the Potential of Live Streaming Facebook via OBS Devices</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-eye-catching-youtube-most-followed-channels/"><u>[Updated] Eye-Catching YouTube Most Followed Channels</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-xiaomi-redmi-k70-pro-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Xiaomi Redmi K70 Pro Phone? | Dr.fone</u></a></li>
<li><a href="https://win-superb.techidaily.com/efficient-techniques-for-handling-parameters-in-emeditor-scripts/"><u>Efficient Techniques for Handling Parameters in EmEditor Scripts</u></a></li>
<li><a href="https://win-superb.techidaily.com/eliminating-trailing-whitespace-in-your-texts-using-emeditor-a-comprehensive-guide/"><u>Eliminating Trailing Whitespace in Your Texts Using EmEditor: A Comprehensive Guide</u></a></li>
<li><a href="https://win-superb.techidaily.com/emeditor-text-editor-guide-configuring-sticky-vertical-mode-java-macros-tutorial/"><u>EmEditor Text Editor Guide: Configuring Sticky Vertical Mode - Java Macros Tutorial</u></a></li>
<li><a href="https://win-superb.techidaily.com/enhanced-text-editing-with-mtex2-in-emeditor-comprehensive-input-assistance/"><u>Enhanced Text Editing with MTeX2 in EmEditor: Comprehensive Input Assistance</u></a></li>
<li><a href="https://facebook.techidaily.com/halt-digital-misappropriation-of-intriguing-selfies/"><u>Halt Digital Misappropriation of Intriguing Selfies</u></a></li>
<li><a href="https://win-superb.techidaily.com/new-release-emeditor-professional-suite-v1460-beta-edition-next-level-text-editor-experience/"><u>New Release: EmEditor Professional Suite v14.6.0 Beta Edition – Next-Level Text Editor Experience</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-background-generator-for-2024/"><u>New What Is AI Background Generator for 2024</u></a></li>
<li><a href="https://win-superb.techidaily.com/resolving-the-phantom-character-issue-with-emeditor-step-by-step-solutions/"><u>Resolving the Phantom Character Issue with EmEditor - Step-by-Step Solutions</u></a></li>
<li><a href="https://buynow-help.techidaily.com/storage-solutions/"><u>Storage Solutions</u></a></li>
<li><a href="https://win-superb.techidaily.com/ultimate-text-editing-software-emeditor-your-perfect-digital-wordsmith-companion/"><u>Ultimate Text Editing Software: EmEditor, Your Perfect Digital Wordsmith Companion</u></a></li>
<li><a href="https://win-superb.techidaily.com/unleash-powerful-text-editing-capabilities-using-emeditors-advanced-features/"><u>Unleash Powerful Text Editing Capabilities Using EmEditor's Advanced Features</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unlocking-road-safety-and-convenience-at-a-great-price-the-ultimate-guide-to-z-edge-z3plus-dashcam-review/"><u>Unlocking Road Safety and Convenience at a Great Price - The Ultimate Guide to Z-Edge Z3+ Dashcam Review</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557742/17382" target="_top" id="1557742">
  <img src="//a.impactradius-go.com/display-ad/17382-1557742" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557742/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

