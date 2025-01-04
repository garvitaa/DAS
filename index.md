---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

<img src="fig/MET.png" alt="" style="width: 400px;"/>

This tutorial will give you the basics you need to deal with transverse missing energy (MET) in your analysis. We start with the basics of MET, how it is derived, what are the associated uncertainties, etc. Then, we give examples with scripts on how to access MET and use them in your analysis frameworks, including corrections and systematics.

The tutorial is designed to be executed at cmslpc, following the setup step, using jupyter notebooks. On this website, you will find links to instructional slides and more information about the topics to walk you through the exercises.

_For general questions, problems, debugs, or asking for help from experts on jets and MET:_ [CMS Talk JetMET category](https://cms-talk.web.cern.ch/c/pog/jetmet/51)

_Follow the CMS workbook on MET analysis:_ [WorkBookMetAnalysis](https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookMetAnalysis)

> ## What is this set of exercises trying to do?
>
>It gives you hands-on experience accessing MET collection in an event, plotting basic quantities, and applying corrections.
> * Introduction to MET reconstruction and fundamental concepts
> * MET calibration and uncertainties
> * Identification of sources that can lead to artificial MET and Noisy event filters
> * Illustrate each exercise using real-life example scripts.
> * Give a comprehensive reference to more advanced workbook examples, additional resources, and pedagogical documentation in one place.
{: .objectives}

> ## What are these exercises NOT meant for?
>
> To summarize the CMS JetMET software machinery comprehensively or the MET analyses performed at CMS.
{: .keypoints}

> ## What do we expect from you?
>
> * You should have followed all the pre-exercises and have a cmslpc account, grid certificate, and a current web browser.
> * It would be best if you worked through the notebooks, ensuring you understand every step and every plot.
> * The exercises are prepared to be run directly from a cmslpc node, with non-interactive notebooks to follow and discuss the exercises.
{: .testimonial}

### Facilitators CMSDAS LPC 2025

<img src="fig/photo_facilitators.png" alt="" style="width:70%">


### Support

Join the [ShortExMET Mattermost channel](https://mattermost.web.cern.ch/cmsdaslpc2025/channels/shortexmet) and don't hesitate to ask for help from the facilitators in the room.


<!-- this is an html comment -->
{% comment %} This is a comment in Liquid {% endcomment %}

> ## Prerequisites
>
> [CMS DAS Pre-exercises](https://fnallpc.github.io/cms-das-pre-exercises/) 
{: .prereq}

{% include links.md %}
