---
layout: post
title: Juxta 1.2.1 Released
date: 2007-10-31 18:00:00 +0000
categories: ''
permalink: "/juxta-1-2-1"

---
# Juxta 1.2.1 Released

It has been a while since we have had an update on this blog, but work has been occurring this year behind the scenes at ARP. Juxta 1.2.1 is now available for download.

Last summer, [Performant Software Solutions](http://www.performantsoftware.com/) developed a new version of Juxta for ARP. This is the version I demoed at COST 32 Workshop in Antwerp, Belgium in September. Below is a summary of the new features and bug fixes found in this release.

\**New Features  
\**  
Passage Collation – Juxta can now collate texts in which passages appear in different order from one text to the next. A new user interface component, the Passage Panel, guides the user through the process. See the updated [user’s manual](http://www.patacriticism.org/juxta/?page_id=4)for more information.

Fragment Collation – Juxta can also collate fragments of texts. This is useful when the target of collation is embedded in a document.

Free Scrolling in Comparison View – Documents in the side-by-side comparison view can now be scrolled independent of one another.

Easier to Find Samples Directory – A file menu shortcut has been added that takes you straight to the samples directory.

Improvements to generation of Critical Apparatus – A dialog box now allows you to specify a title for the critical apparatus. A progress bar is now provided while the critical apparatus is being generated. Some bugs with the generation of lemmas within the apparatus have been fixed.

Find Works in Either Document – The Find Dialog can now find text in either document in the side-by-side comparison mode.  
\**  
Bug Fixes**

Improvements to Collation Algorithm – Hans Walter Gabler found some problems with the collation output in specific circumstances. We have corrected these errors.

Margin Box Clipping – Occasionally, when the window was resized it would cause the margin boxes to be clipped, this has been fixed.

Scrollbar Positioning Sometimes Incorrect – When loading a large document the scrollbar would become positioned incorrectly, this has been fixed.

Image Display Not Updating – When flipping between documents, sometimes the image associated with the document on screen would not appear, this has been fixed.

Large Images Cause Scrolling to Be Erratic – Related to the issue above, scrolling through documents which have images associated with them could be jerky at times as the images loaded. Loading has been adjusted so this no longer occurs.

Out of Memory Error – Loading two large, completely unrelated documents could cause a system error. This has been fixed.