---
title: First FAIRport-Elixir BYOD Workshop
date: 2014-07-11T10:35:22+01:00
author: Alasdair Gray
layout: post
categories:
  - Open PHACTS
excerpt_separator: <!--more-->
---
<div id="namespaces" prefix="schema: http://schema.org/">
  
  <p>
    <a href="/assets/img/2014-07-11_byod-group.jpeg"><img src="/assets/img/2014-07-11_byod-group.jpeg" alt="Participants at first BYOD workshop" width="620" height="258" class="aligncenter size-large wp-image-127"/></a>
  </p>
  <p>
    At the end of June, a group of individuals from across Europe came together in Leiden for the first <span><a href="http://www.datafairport.org/">FAIRport</a>&#8211;<a href="http://www.elixir-europe.org">ELIXIR</a></span> Bring Your Own Data (BYOD) workshop. None of us quite knew what would happen but we were all excited that such an event was taking place.  The result was better than we expected.<br /> <!--more-->
  </p>
  
  <p>
    This first BYOD workshop combined the expertise of Linked Data experts and data experts from <a href="http://www.mycobank.org">MycoBase</a> and the Human Protein Atlas (<a href="http://www.proteinatlas.org/">HPA</a>). The participants were pretty evenly split between data providers (who had some, but not a lot of RDF knowledge) and trainers (experts in semantic web technologies). The idea of the workshop was to give the data providers a hands on training event (part tutorial, part hackathon) for making their data available in a findable, accessible, interoperable and reusable manner (<a href="http://www.datafairport.org">FAIR</a>). The chosen approach to make the data FAIR was RDF<sup><a href="#rdf-footnote">1</a></sup>. The goal was to develop showcases that would demonstrate the added value of interoperable data for facilitating questions across multiple resources.
  </p>
  
  <p>
    The first day of the workshop was mainly devoted to introducing the ideas of publishing data as interoperable RDF and understanding the datasets represented by the data providers. Before the afternoon was over we&#8217;d split into two teams to work up the showcase studies using either MycoBase or HPA and the experts knowledge of related datasets. The day ended with a social meal by the canal in central Leiden.
  </p>
  
  <p>
    The next day started with the teams feverishly working up their ideas. There was a general buzz around the room with the experts calling on each other’s knowledge across the teams to bring together working demonstrations. The day closed with a show and tell of what had been accomplished.
  </p>
  
  <p>
    <a href="/assets/img/2014-07-11_byod-myco.jpeg"><img src="/assets/img/2014-07-11_byod-myco.jpeg" alt="MycoBase Group" width="300" height="155" style="float:right; padding: 20px" /></a>The MycoBase showcase focused on discovering which compounds fermented. About 10,000 fungal strains in MycoBase were represented in RDF resulting in 2.5 million triples. These were linked to the ChEMBL database by exploiting the <a href="http://www.openphacts.org/">Open PHACTS</a> Discovery Platform <a href="https://dev.openphacts.org/">API</a> to resolve chemical names present in MycoBase to their <a href="https://www.ebi.ac.uk/chembl/">ChEMBL</a> <a href="https://www.ebi.ac.uk/rdf/services/chembl/">URI</a>. This formed the key linkage to integrate the two data sets, pulling in key facts (e.g. molecular weight, log p value and hydrogen bound count) from the ChEMBL database.
  </p>
  
  <p>
    <a href="/assets/img/2014-07-11_byod-HPA.jpeg"><img src="/assets/img/2014-07-11_byod-HPA.jpeg" alt="HPA Group" width="300" height="146" style="float:left; padding: 20px" /></a>The Human Protein Atlas (HPA) team worked up two possible showcases. The first involved discovering for a given HPA protein the pathways, sourced from <a href="http://wikipathways.org/">wikipathways</a>, in which the protein occurs. The second involved linking with the genes present in <a href="http://fantom.gsc.riken.jp/5">FANTOM5</a> and included a resolution step involving the <a href="http://bio2rdf.org/">Bio2RDF</a> version of <a href="http://www.ncbi.nlm.nih.gov/gene/">EntrezGene</a>. These connections were possible due to the lengthy modelling discussions and the development of an RDF generating script that converted part of the HPA relational database into an RDF representation.
  </p>
  
  <p>
    Overall the workshop was a great success. The data providers felt they had learnt about RDF and were happy with the progress that had been made. While it was recognised that modelling the data in RDF was hard, the interoperability possibilities were a great incentive. The trainers were pleased with the ad hoc training approach, although they had some key suggestions for training material for the next BYOD workshop. The facilitators also played a key role in ensuring that there was an appropriate amount of tutorial time and making us catch our planes. Both teams left vowing to continue working up their showcases to completion and aiming to produce a paper about their work. A summer of work lies ahead.
  </p>
  
  <p>
    For me, the key measure of success for the workshop will be if the data providers are now able to find their way into the world of semantic data publishing without further workshops. Only time will tell.
  </p>
  
  <hr />
  
  <p>
    The first BYOD workshop was made possible by the kind sponsorship of <a href="http://www.datafairport.org">Data FAIRport</a>, the Dutch Techcentre for Life Sciences (<a href="http://www.dtls.nl/dtl/">DTL</a>), and <a href="http://www.elixir-europe.org">Elixir</a>.
  </p>
  
  <p>
    <a href="http://www.datafairport.org/"><img src="/assets/img/2014-07-11_datafairport.png" alt="Data FAIRport logo" width="307" height="96" /></a><a href="http://www.dtls.nl/dtl/"> <img src="/assets/img/2014-07-11_dtl.png" alt="Dutch Techcentre for Life Sciences Logo" width="245" height="81" /></a> <a href="/assets/img/2014-07-11_elixir-logo.png"><img src="/assets/img/2014-07-11_elixir-logo.png" alt="ELIXIR logo" width="203" height="107" /></a>
  </p>
  
  <hr />
  
  <p>
    <a id="rdf-footnote"></a><br /> <sup>1</sup> RDF, Resource Description Framework, is a model for representing data using largely the same technologies that made the world wide web such a success. While on the world wide web the focus is on linking documents, RDF is aimed at linking data with data, and data with ontologies, in a computer readable format. For tutorials click <span><a href="http://www.cambridgesemantics.com/semantic-university">here</a> or <a href="http://www.slideshare.net/MarcoRoos/linked-data-and-ontology-tutorial-for-rdconnect">here</a></span>.
  </p>
</div>
