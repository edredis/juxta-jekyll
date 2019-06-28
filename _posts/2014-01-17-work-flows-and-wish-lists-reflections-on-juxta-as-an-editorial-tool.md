---
layout: post
title: 'Work Flows and Wish Lists: Reflections on Juxta as an Editorial Tool'
date: 2014-01-17 18:00:00 +0000
categories: ''
permalink: "/work-flows-wish-lists"

---
# Work Flows and Wish Lists: Reflections on Juxta as an Editorial Tool

I have had the opportunity to use [Juxta Commons](http://juxtacommons.org/ "Juxta Commons") for several editorial projects, and while taking a breath between a Juxta-intensive term project last semester and my Juxta-intensive MA thesis this semester, I would like to offer a few thoughts on Juxta as an editorial tool.

For my term project for Jerome McGann’s American Historiography class last semester, I conducted a collation of Martin R. Delany’s novel, _Blake, or, The Huts of America_, one of the earliest African American novels published in the United States.Little did I know that my exploration would conduct me into an adventure as much technological as textual, but when Professor McGann recommended I use Juxta for conducting the collation and displaying the results, that is exactly what happened. I input my texts into Juxta Commons, collated them, and produced HTML texts of the individual chapters, each with an apparatus of textual variants, using Juxta’s Edition Starter. I linked these HTML files together into an easily navigable website to present the results to Professor McGann. I’ll be posting on the intriguing results themselves next week, but in the meantime, they can also be viewed on the website I constructed, hosted by [GitHub](https://github.com/ "GitHub"): [_Blake_ Project home](http://stephanie-kingsley.github.io/Blakeindex.html "Blake Project home").

Juxta helped me enormously in this project. First, it was incredibly useful in helping me clean up my texts. My collation involved an 1859 serialization of the novel, and another serialization in 1861-62. The first, I was able to digitize using OCR; the second, I had to transcribe myself. Anyone who has done OCR work knows that every minute of scanning leads to (in my case) an average of five or ten minutes of cleaning up OCR errors. I also had my own transcription errors to catch and correct. By checking Juxta’s highlighted variants, I was able to—relatively quickly—fix the errors and produce reliable texts. Secondly, once collated, I had the results stored in Juxta Commons; I did not have to write down in a collation chart every variant to avoid losing that information, as I would if I were machine- or sight-collating. Juxta’s heat-map display allows the editor to see variants in-line, as well, which saves an immense amount of time when it comes to analyzing results: you do not have to reference page and line numbers to see the context of the variants. Lastly, Juxta enabled me to organize a large amount of text in individual collation sets—one for each chapter. I was able to jump between chapters and view their variants easily.

As helpful as Juxta was, however, I caution all those new to digital collation that no tool can perfectly collate or create an apparatus from an imperfect text. In this respect, there is still no replacement for human discretion—which is, ultimately, a good thing. For instance, while the Juxta user can turn off punctuation variants in the display, if the user does want punctuation and the punctuation is not spaced exactly the same in both witnesses, the program highlights this anomalous spacing. Thus, when 59 reads

‘ Henry, wat…

and 61 reads

‘Henry, wat…

Juxta will show that punctuation spacing as a variant, while the human editor knows it is the result of typesetting idiosyncrasies rather than a meaningful variant. Such variants can carry over into the Juxta Edition Builder, as well, resulting in meaningless apparatus entries. For these reasons, you must make your texts _perfect_to get a perfect Juxta heat map and especially before using Edition Starter; otherwise, you’ll need to fix the spacing in Juxta and output another apparatus, or edit the text or HTML files to remove undesirable entries.

Spacing issues can also result in disjointed apparatus entries, as occurred in my apparatus for Chapter XI in the case of the contraction _needn’t_. Notice how because of the spacing in _needn t_ and _need nt_, Juxta recognized the two parts of the contraction as two separate variants (lines 130 and 131):

[![spacing 2](http://www.nines.org/news/wp-content/uploads/2014/01/spacing-2.jpg)](http://www.nines.org/news/wp-content/uploads/2014/01/spacing-2.jpg)

This one variant was broken into two apparatus entries because Juxta recognized it as two words. There is really no way of rectifying this problem except by checking and editing the text and HTML apparatuses after the fact_._

I mean simply to caution scholars going into this sort of work so that they can better estimate the time required for digital collation. This being my first major digital collation project, I averaged about two hours per chapter (chapters ranging between 1000 and 4000 words each) to transcribe the 61-62 text and then collate both witnesses in Juxta. I then needed an extra one or two hours per chapter to correct OCR and transcription errors.

While it did take me time to clean up the digital texts so that Juxta could do its job most efficiently, in the end, Juxta certainly saved me time—time I would have spent keeping collation records, constructing an apparatus, and creating the HTML files (as I wanted to do a digital presentation). I would be remiss, however, if I did not recommend a few improvements and future directions.

As useful as Juxta is, it nevertheless has limitations. One difficulty I had while cleaning my texts was that I could not correct them while viewing the collation sets; I had, rather, to open the witnesses in separate windows.

[![screenshot windows](http://www.nines.org/news/wp-content/uploads/2014/01/screenshot-windows.jpg)](http://www.nines.org/news/wp-content/uploads/2014/01/screenshot-windows.jpg)

The ability to edit the witnesses in the collation set directly would make correction of digitization errors much easier. This is not a serious impediment, though, and is easily dealt with in the manner I mentioned. The Juxta download does allow this in a limited capacity: the user can open a witness in the “Source” field below the collation visualization, then click “Edit” to enable editing in that screen. However, while the editing capability is turned on for the “Source,” you cannot scroll in the visualization—and so navigate to the next error which may need to be corrected.

A more important limitation is the fact that the Edition Starter does not allow for the creation of eclectic texts, texts constructed with readings from multiple witnesses; rather, the user can only select one witness as the “base text,” and all readings in the edition are from that base text.

[![screenshot Edition Starter](http://www.nines.org/news/wp-content/uploads/2014/01/screenshot-Edition-Starter.jpg)](http://www.nines.org/news/wp-content/uploads/2014/01/screenshot-Edition-Starter.jpg)

Most scholarly editors, however, likely will need to adopt readings from different witnesses at some point in the preparation of their editions. Juxta’s developers need to mastermind a way of selecting which reading to adopt _per variant_; selected readings would then be adopted in the text in Edition Starter. For the sake of visualizing, I did some screenshot melding in Paint of what this function might look like:

[![mockup](http://www.nines.org/news/wp-content/uploads/2014/01/mockup.jpg)](http://www.nines.org/news/wp-content/uploads/2014/01/mockup.jpg)

Currently, an editor wishing to use the Edition Starter to construct an edition would need to select either the copy-text or the text with the most adopted readings for the base text. The editor would then need to adopt readings from other witnesses by editing the the output DOCX or HTML files. I do not know the intricacies of the code which runs Juxta. I looked at it on GitHub, but, alas! my very elementary coding knowledge was completely inadequate to the task. I intend to delve more as my expertise improves, and in the meantime, I encourage all the truly code-savvy scholars out there to look at the code and consider this problem. In my opinion, this is the one hurdle which, once overcome, would make Juxta the optimal choice as an edition-preparation tool—not just a collation tool. Another feature which would be fantastic to include eventually would be a way of digitally categorizing variants: accidental versus substantive; printer errors, editor corrections, or author revisions; etc. Then, an option to adopt all substantives from text A, for instance, would—perhaps—leave nothing to be desired by the digitally inclined textual editor. I am excited about Juxta. I am amazed by what it can do and exhilarated by what it may yet be capable of, and taking its limitations with its vast benefits, I will continue to use it for all future editorial projects.