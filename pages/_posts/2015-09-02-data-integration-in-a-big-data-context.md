---
title: Data Integration in a Big Data Context
date: 2015-09-02T21:14:54+01:00
author: Alasdair Gray
layout: post
categories:
  - ADRC-Scotland
  - Dataset Description
  - Open PHACTS
  - Presentation
  - Research
  - Streaming Data
---
Today I had the pleasure of visiting the [Urban Big Data Centre](http://ubdc.ac.uk/) (UDBC) to give a seminar on Data Integration in a Big Data context (slides below). The idea for the seminar came about due to my collaboration with [Nick Bailey](http://ubdc.ac.uk/about/our-team/senior-management/nick-bailey/) (Associate Director of the UBDC) in the [Administrative Research Data Centre for Scotland](http://adrn.ac.uk/centres/scotland) (ADRC-S).

In the seminar I wanted to highlight the challenges of data integration that arise in a Big Data context and show examples from my past work that would be relevant to those in the UBDC. In the presentation, I argue that RDF provides a good approach for data integration but it does not solve the basic challenges of messy data and generating mappings between datasets. It does however lay these challenges bare on the table, as [Frank van Harmelen](http://www.cs.vu.nl/~frank.van.harmelen/) highlighted in his [SWAT4LS](http://www.swat4ls.org/workshops/edinburgh2013/) keynote in 2013.

The first use case is drawn from my work on the EU [SemSorGrid4Env](http://www.semsorgrid4env.eu/) project where we were developing an integrated view for emergency response planning. The particular use case shown is that of coastal flooding on the south coast of England. Although this project finished in 2011, I am still involved with developing RDF and SPARQL continuous data extensions; see the [W3C RDF Stream Processing Community Group](https://www.w3.org/community/rsp/) for details.

The second use case is drawn from my work on the EU [Open PHACTS](http://www.openphacts.org/) project. I showed the approach we developed for supporting user controlled views of the integrated data through Scientific Lenses. However, I also talked about the successes of the project and the fact that is currently being actively used for pharmacology research and receiving over 20million hits a month.

I finished the talk with an overview of the [Administrative Data Research Centre for Scotland](http://adrn.ac.uk/centres/scotland) (ADRC-S) and my work on linking birth, marriage, and death records. I am hoping that we can adopt the lenses approach together with incorporating feedback on the linkages from the researchers who will use the integrated views.

In the discussions following the talk, the notion of [FAIR](https://www.force11.org/group/fairgroup/fairprinciples) data came up. This is the idea that data should be Findable, Accessible, Interoperable, and Reusable by both humans and machines. RDF is one approach that could lead to this. The other area of discussion was around community initiatives for converting existing open datasets into an RDF format. I advocated adopting the approach followed by the [Bio2RDF](https://github.com/bio2rdf/bio2rdf-scripts/wiki) community who share the tasks of creating and maintaining such scripts for biological datasets. An important part of this jigsaw is tracking the provenance of the datasets, for which the [W3C Health Care and Life Sciences Community Profile for Dataset Descriptions](http://www.w3.org/TR/hcls-dataset/) could be beneficial (there is nothing specific to the HCLS community in the profile).

<iframe src="//www.slideshare.net/slideshow/embed_code/key/1RZ4Phz0VTJL9W" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/alasdair_gray/data-integration-in-a-big-data-context" title="Data Integration in a Big Data Context" target="_blank">Data Integration in a Big Data Context</a> </strong> from <strong><a href="https://www.slideshare.net/alasdair_gray" target="_blank">Alasdair Gray</a></strong> </div>