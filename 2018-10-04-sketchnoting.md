---
layout: page
title:  "Sketchnoting, Mobility, and Writing a Spatial Self"
date:   2018-10-04 21:15:05 +0000
image: /assets/images/sketchnote.jpg
permalink: /sketchnotes/
my_variable: image.html, iframe.html

---

Sketchnoting, Mobility, and Writing a Spatial Self was a collaborative research project between faculty and Ph.D. students in the Professional Writing Program at North Carolina State University. The project examines multimodal compositions in everyday mobile literacy practices by collecting and analyzing sketchnotes posted on Flickr. 

To collect sketchnotes, we collected approximately 16,000 posts referencing the keyword “sketchnotes” through Flickr’s API and prepared the returned data for a variety of computational and human modes of analysis. 

As a means to examine the way in which space, place, mobility, and identity were composed, we first identified geolocation information in our sketchnotes collection. Since this information is present only if the Flickr user chooses to geolocate, approximately only 10% of the data was geotagged. By mapping this geotagged sample, we found posts were primarily located in Europe, mostly in Italy. The map also helped us identify key traits about the whole dataset. During the mapping process, we found a long tail pattern in the users that appeared in the geolocated data, which stayed consistent in our non-geolocated data. In the complete dataset, most of the 889 unique users were power users, meaning most posts came from just a few dynamic users. The remaining users posted infrequently, perhaps producing only one digitally circulated sketchnote. In the map below, the darker dots indicate higher numbers of geolocated sketchnotes in that place.

{% include iframe.html class="carto" url="https://ddighto.carto.com/builder/f45893ab-855d-4c5e-8dbe-bc185f6e3904/embed" width="100%" height="600px" %}

Though the map helped us identify locations for further analysis of location and mobility in sketchnoting, it quickly taught us that looking only at user geolocated posts was insufficient. 
{% include image.html image="/assets/images/sketchnote_tagging.png" width="500px" height="auto" %} 
To further explore the posts, specifically those without geotags, we identified and hand-coded location information in: 1) user location, 2) image title, 3) image description, 4) hashtags, and in the 5) sketchnote images themselves.


The tags field was particularly informative for understanding mobility. We used Voyant Tools to visualize patterns in the most recurring tags, which were often autogenerated by platforms and devices, most notably Instagram. These visualizations began to reveal the influence of nonhuman actors like platforms, the role that human-technological assemblages play in the distribution of these multi-modal compositions, and the possibilities for encounters afforded by multiple network interactions.

<!--
{% include iframe.html class="voyant" url="//voyant-tools.org/tool/Cirrus/?corpus=24ac88a6ae818591a2c48d5b733335c8" width="50%" height="400px" %}

{% include iframe.html class="voyant" url="//voyant-tools.org/tool/Trends/?query=graphic&query=instagram&query=square&query=notes&query=visual&withDistributions=raw&mode=document&corpus=24ac88a6ae818591a2c48d5b733335c8" width="50%" height="400px" %}
-->

<div class="gallery">
{% include image.html image="/assets/images/wordcloud.png" width="400px" height="auto" %}
{% include image.html image="/assets/images/relative_freq_graph.png" width="400px" height="auto" %}
</div>

* Further analysis done through location-based human coding processes allowed us to understand users within categories of masters and apprentices who interacted based on unique affordances. These affordances were partly defined by users’ technological and sketchnoting skills and experiences, semiotic resources available in situated spatial contexts, and the technological influence of social networking platforms and mobile devices. Continuing research will further trace how networked mobile technologies afford the circulation of messages and how the materialities of different technologies and social media platforms provide users opportunities and constraints based on a variety of semiotic resources that shape the place, space, and mobility of their texts. Pedagogically, this research suggests new heuristics for analyzing social media as multimodal compositions and invites new inquiry into understanding writing knowledge and skill transfer across a wide variety of social, professional, and technological context.

The code for retrieving posts from Flickr is available on [Github](https://github.com/ddighton/flickr_scripts).

This research was presented during an invited conference presentation: “Sketchnoting, Mobility, and Writing a Spatial Self,” with Stacey Pigg, co-panelists Kendra Andrews, Chen Chen, and Desiree Dighton at the Thomas R. Watson Conference in Louisville, KY on October 22, 2016.

<br/><br/>
