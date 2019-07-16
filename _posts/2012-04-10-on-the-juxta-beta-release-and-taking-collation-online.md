---
layout: post
title: On the Juxta Beta release, and taking collation online
date: 2012-04-10 18:00:00 +0000
categories: ''
permalink: "/on-the-juxta-beta"

---
 
![](/wp-content/uploads/2012/04/tennyson.heatmap-300x240.jpg "Heat Map, Lady of Shalott")

In September of 2008, when I first became acquainted with Juxta as a collation tool, I wrote a [blog post](http://dev-juxtasoftware.pantheonsite.io/searching-tennyson/) as a basic demonstration of the software. I hunted down transcriptions of two versions of one of my favorite poems, Tennyson’s “The Lady of Shalott,” and collated them alongside the abbreviated lyrics to the song adapted from work by Loreena McKennitt. [Screenshots](/wp-content/uploads/2008/09/tennsysoncomp.jpg) were all I had to illustrate the process and its results, however – anyone interested in exploring the dynamic collation in full would need to first download Juxta, then get the set of files from me. We had a great tool that encouraged discovery and scholarly play, but it didn’t facilitate collaboration and communication. Now, in 2012, I can finally show you[that set](http://juxta.performantsoftware.com/shares/e0547f83dc8c48ff971ecd706970c02e/view?mode=heatmap) in its entirety.

The dream of Juxta for the web has been a long time coming, and we couldn’t have done it without generous funding from the [Google Digital Humanities Award](http://dev-juxtasoftware.pantheonsite.io/juxta-receives-google-digital-humanities-award/) and support from European scholars in the [COST Action 32 group](http://www.cost-a32.eu/), TextGrid and the whole team behind [CollateX](http://collatex.sourceforge.net/). As Project Manager, I’m thrilled to be a part of the open beta release of the [Juxta web service](http://juxta.performantsoftware.com/), accessed through version 1.6.5 of the desktop application.

I imagine at this point you’re wondering: _if I want to try out the web service, do I still have to download the desktop application? Why would I do that?_

Over the past year, our development team’s efforts have been directed to breaking down the methods by which Juxta handles texts into ‘microservices’ following the[Gothenberg Model](http://www.interedition.eu/wiki/index.php/About_microservices#Gothenburg_Model_and_Implementation) for collation. We designed the web service to enable other tools and methods to make use of its output: in [Bamboo CorporaSpace](https://wiki.projectbamboo.org/display/BTECH/Corpora+Space), for example, a text-mining algorithm could benefit from the tokenization performed by Juxta. We imagined Juxta not just as a standalone tool, but as one that could interact with a suite of other potential tools.

That part of our development is ready for testing, and the [API documentation](https://github.com/performant-software/juxta-desktop/wiki/JuxtaWebServiceApi) is available at GitHub.

However, the user workflow for Juxta as a destination site for collations on the web, is still being implemented. Hence this new, hybrid beta, which leverages the desktop application’s interface for adding, subtracting and editing documents while also inviting users to share their curated comparison sets online.

This is where you come in, beta testers – we need you to tell us more about how you’d like to user Juxta online. We know that collation isn’t just for scholarly documents: we’ve seen how [visualizing versions of Wikipedia pages](http://juxta.performantsoftware.com/shares/ba4a680b3ad341fe8f7561d6d38b1581/view?mode=heatmap&base=451) can tell us something about evolving conversations in Digital Humanities, and we’ve thought about Juxta’s potential as a method for authenticating online texts. But as we design a fully online environment for Juxta, we want to get a better sense of what the larger community wants.

I want to thank everyone who has set up and account and tried out the newest version. We’ve seen some really exciting possibilities, and we’re taking in a lot of valuable feedback. If you’ve held off so far, I ask that you consider trying it out.

**But I don’t have any texts to collate!**

No worries! We’re slowly populating a Collation Gallery of comparison sets shared by other beta testers. You might just find something there that gets your creative juices flowing.

Explore [Juxta Beta](http://juxta.performantsoftware.com/) today!

\** cross-posted on the NINES site **