---
layout: post
title: Using the Critical Apparatus in Digital Scholarship
date: 2012-10-18 18:00:00 +0000
categories: ''
permalink: "/using-the-critical"

---

[![](/wp-content/uploads/2008/09/ladyofshalott.jpg "Lady of Shalott page image"){:class="col-6  p-1"}](/wp-content/uploads/2008/09/ladyofshalott.jpg){:class="col-6  p-0"}[![](/wp-content/uploads/2008/09/tennysonapparat.jpg "Critical Apparatus"){:class="col-6  p-0"}](/wp-content/uploads/2008/09/tennysonapparat.jpg){:class="col-6  p-0"}

 
As the Juxta R&D team has worked to take the desktop version of our collation software to the web, I’ve found myself thinking a great deal about the [critical apparatus](http://en.wikipedia.org/wiki/Critical_apparatus)and its role when working with digital (digitized?) texts.

In the thumbnails above, you can see a page image from a traditional print edition (in this case, of Tennyson’s poetry) on the left, and a screenshot of the old Juxta critical apparatus output on the right. In the original, downloadable, version of Juxta, we allowed users to browse several visualizations of the collation in order to target areas of interest, but we also offered them the ability to export their results in an HTML-encoded apparatus. This was an effort to connect digital scholarship to traditional methods of textual analysis, as well as a way to allow scholars to share their findings with others in a familiar medium.

It has become clear to me, based on the feedback from our users, that this HTML critical apparatus has been quite useful for a number of scholars. Even though our output could seem cryptic without being paired with the text of the base witness (as it is in the Tennyson edition), it was apparent that scholars still needed to translate their work in Juxta into the traditional format.

In the meantime, scholars working with the [Text Encoding Initiative](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/TC.html) (TEI) developed Parallel Segmentation, a method of encoding the critical apparatus in XML. In her article, “[Knowledge Representation and Digital Scholarly Editions in Theory and Practice](http://jtei.revues.org/203?lang=en),” Tanya Clement describes the effectiveness of using parallel segmentation to encode her digital edition of the work of the Baroness Elsa von Freytag-Loringhoven. Using a TEI apparatus along with a visualization tool called the[Versioning Machine](http://www.v-machine.org/), Clement argued that her project “encourage\[d\] critical inquiry concerning _how_ a digital scholarly edition represents knowledge differently than a print edition,” and illustrated the flexibility of working with full texts in tandem. Witnesses, or alternate readings, were not subsumed under a (supposedly static) base text, but living, dynamic representations of the social and cultural networks within which the Baroness lived and wrote.

Working with digital texts can make generating a critical apparatus difficult. One could encode your apparatus manually, as Clement did, but most users of Juxta wanted us to take their plain text or XML-encoded files and transform them automatically. The traditional apparatus requires exact notations of line numbers and details about the printed page. How does one do that effectively when working with plain text files that bear no pagination and few (if any) hard returns, denoting line breaks? Instead of hurriedly replicating the desktop apparatus online –knowing it would posses these weaknesses and more — the R&D team chose to offer TEI Parallel Segmentation output for [Juxta Commons](http://juxtacommons.org/).

[![Juxta TEI  Parallel Segmentation export](/wp-content/uploads/2012/10/tei_parSeg-300x174.jpg "Juxta TEI  Par Seg export"){:class="col-8  p-0"}](/wp-content/uploads/2012/10/tei_parSeg.jpg)

Any user of Juxta Commons can upload a file encoded in TEI Parallel Segmentation, and see their documents represented in Juxta’s [heat map, side-by-side, and histogram views](http://juxtacommons.org/guide#visualizations). Those working with plain text of XML files can also export the results of their collations as a downloadable TEI Parallel Segmentation file. In short, Juxta Commons and can both read and write TEI Parallel Segmentation.

However, we’re not convinced that the traditional apparatus has lost its functionality. We’d like to ask you, our users, to tell us more about your needs. How do you use the critical apparatus in your studies? What other kind of apparatus could we offer to streamline and enhance your work in Juxta Commons?