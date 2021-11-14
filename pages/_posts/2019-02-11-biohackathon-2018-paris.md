---
title: Biohackathon 2018 -Paris
date: 2019-02-11T10:11:49+00:00
author: Alasdair Gray
layout: post
categories:
  - BioSchemas
  - ELIXIR
  - Research
excerpt_separator: <!--more-->
---
<img src="/assets/img/2019-02-11_biohackathon-paris.jpg" alt="Bioschemas at the Biohackathon" width="80%" class="center" style="padding: 10px"/>

Last November I had the privilege to be one of 150 participants at the <a href="https://2018.biohackathon-europe.org/">Biohackathon</a> organised by <a href="https://www.elixir-europe.org/">ELIXIR</a>. The hackathon was organised into 29 topics, many of which were related to <a href="http://bioschemas.org/">Bioschemas</a> and one directly focused on Bioschemas. For the Bioschemas topic we had up to 30 people working around three themes.
<!--more-->

The first theme was to implement markup for the various life sciences resources present. Representatives from ELIXIR Core Data Resources and node resources from the UK and Switzerland were there to work on this thanks to the <a href="https://www.elixir-europe.org/platforms/interoperability/rfp-bioschemas">staff exchange and travel fund</a>. By the end of the week we had new <a href="http://bioschemas.org/liveDeploys/">live deploys</a> for 11 additional resources and examples for many more.

The second theme was to refine the types and profiles that Bioschemas has been developing based on the experiences of deploying the markup. Prior to the hackathon, Bioschemas had moved from a minimal <a href="http://schema.org">Schema.org</a> extension of a single <a href="http://bioschemas.org/BioChemEntity">BioChemEntity</a> type to collection of types for the different life science resources, e.g. <a href="http://bioschemas.org/Gene">Gene</a>, <a href="http://bioschema.org/Protein">Protein</a>, and <a href="http://bioschemas.org/Taxon">Taxon</a>. Just before the hackathon a revised set of types and profiles were released. This proved to be useful for discussion, but it very quickly became clear that there was need for further refinement. During the hackathon we started new profiles for <a href="http://bioschemas.org/devSpecs/DNA/">DNA</a>, <a href="http://bioschemas.org/devSpecs/Study/">Experimental Studies</a>, and <a href="http://bioschemas.org/devSpecs/Phenotype/">Phenotype</a>, and the Chemical profile was split into <a href="http://bioschemas.org/devSpecs/MolecularEntity/">MolecularEntity</a> and ChemicalSubstance. Long discussions were held about the types and their structure with early drafts for 17 types being <a href="https://docs.google.com/document/d/1_rO64r4JZgHA-66s_nsvLikUKZJnPJcwQte9BFb0WiU/edit?usp=sharing">proposed</a>. These are now getting to a state where they are ready for further experimentation.

The third theme was to develop tooling to support Bioschemas. Due to the intensity of the discussions on the types and profiles, there was no time to work on this topic. However, the prototype <a href="http://www.macs.hw.ac.uk/~ajg33/BioschemasGenerator/">Bioschemas Generator</a> was extensively tested during the first theme and improvements fed back to the developer. There were also refinements made to the <a href="https://github.com/BioSchemas/bioschemas-goweb">GoWeb tool</a>.

Overall, it was a very productive hackathon. The venue proved to be very conducive to fostering the right atmosphere. During the evenings there were opportunities to socialise or carry on the discussions. Below are two of the paintings that were produced during one of the social activities that capture the Bioschemas discussions.

And there was the food. Wow! Wonderful meals, three times a day.

<img src="/assets/img/2019-02-11_bioschemas-rabithole.jpg" alt="Bioschemas down the rabbit hole" width="45%" style="float:left"/>
<img src="/assets/img/2019-02-11_breaking-bioschemas.jpg" alt="Bioschemas painted logo broken apart" width="45%" style="float:right" />