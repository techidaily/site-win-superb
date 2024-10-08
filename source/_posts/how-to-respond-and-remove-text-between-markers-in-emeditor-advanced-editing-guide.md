---
title: How to Respond & Remove Text Between Markers in EmEditor - Advanced Editing Guide
date: 2024-10-06T17:09:53.361Z
updated: 2024-10-08T16:52:37.650Z
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
<li><a href="https://article-tips.techidaily.com/new-in-2024-behind-the-screen-discovering-samsung-galaxy-s8s-4k-edge/"><u>[New] In 2024, Behind the Screen Discovering Samsung Galaxy S8's 4K Edge</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-archive-mastery-how-and-why/"><u>[New] In 2024, Instagram Archive Mastery How and Why?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unlock-the-power-of-pause-with-instagrams-slow-motion/"><u>[Updated] 2024 Approved Unlock the Power of Pause with Instagram's Slow Motion</u></a></li>
<li><a href="https://win-superb.techidaily.com/convert-and-preserve-quality-download-videos-in-mp4movavi-format-from-mediasite-platforms-using-our-tool/"><u>Convert and Preserve Quality: Download Videos in MP4/MOV/AVI Format From Mediasite Platforms Using Our Tool.</u></a></li>
<li><a href="https://win-superb.techidaily.com/converting-your-favorite-ximalaya-podcasts-into-high-quality-mp3-files-a-guide-for-windows-and-macos/"><u>Converting Your Favorite Ximalaya Podcasts Into High-Quality MP3 Files: A Guide for Windows & macOS</u></a></li>
<li><a href="https://win-superb.techidaily.com/download-high-quality-goo-videos-in-mp4movavi-formats-using-easy-techniques/"><u>Download High-Quality Goo Videos in MP4/MOV/AVI Formats Using Easy Techniques</u></a></li>
<li><a href="https://win-superb.techidaily.com/easy-steps-to-save-ndr-broadcasts-from-any-computer-including-mac-and-pc/"><u>Easy Steps to Save NDR Broadcasts From Any Computer, Including Mac & PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-psychedelic-pulse-the-fade-technique-in-music-mixing/"><u>In 2024, Psychedelic Pulse The Fade Technique in Music Mixing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leverage-ai-to-automate-your-typistits-in-microsoft-word/"><u>Leverage AI to Automate Your Typist'its in Microsoft Word</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

