---
id: 370
title: Will the real Kevin Macleod please line up?
date: 2016-09-09T16:30:35+01:00
author: Alasdair Gray
layout: post
guid: http://www.macs.hw.ac.uk/~ajg33/?p=370
permalink: /will-the-real-kevin-macleod-please-line-up/
image: /wp-content/uploads/2016/09/2016-08-28-14.25.20-e1473433119177-620x220.jpg
categories:
  - ADRC-Scotland
  - Linked Data
  - Research
---
Last week I attended the [Digitising Scotland Project](http://www.lscs.ac.uk/projects/digitising-scotland/) Colloquium at [Raasay House](https://www.raasay-house.co.uk/) (featured image above) on the Isle of Raasay. The colloquium was a gathering of historians and computer scientists to discuss the challenges of linking the vital records of the people of Scotland between 1851 and 1974.

The Digitising Scotland Project is having the birth, marriage, and death records of Scotland transcribed from the scans of the original hand written registration books. This process is not without its own challenges, try reading [this birth record](http://www.scotlandspeople.gov.uk/content/images/crmbirthjune1868l.jpg) of a famous [Scottish artist and architect](https://en.wikipedia.org/wiki/Charles_Rennie_Mackintosh), but the focus of the colloquium was on what happens after the records have been transcribed.

Each Scottish vital record identifies several individuals, e.g. on a birth record you will have the baby, their parents, the informant, and the registrar. The same individuals will appear on multiple records relating to events in their own life, e.g. an individual will have a birth record, potentially one or more marriage records, and a death record, assuming that they have not emigrated. They can also appear in the records of other individuals, e.g. as a mother on a birth record, the mother-of-the-bride on a marriage record, or the doctor on a death record. The challenge is how to identify the same individual across all the records, when all you have is a name (first and last) and potentially the age.

The problem is compounded in an area like Skye, which was one of the focus regions of the Digitising Scotland project, because there is a relatively small distribution of names on which to draw upon. For example, a name like Kevin Macleod will appear on multiple records. In some cases the name will correspond to a single Kevin Macleod, in other cases it will be a closely related Kevin Macleod, e.g. Kevin Macleod the father of Kevin Macleod, and in others the two Kevin Macleods will not be related at all. The challenge is how to develop a computer algorithm that is capable of making these distinctions.

The colloquium was a great opportunity for historians and computer scientists to discuss the challenges and help each other to develop a solution. However, first we had to agree on a common understanding for terms such as &#8220;record&#8221; and &#8220;individual&#8221;.

Overall, we made great progress on exchanging ideas and techniques. We heard how similar challenges are being addressed in a related project focusing on North Orkney, how historians approach the record linkage challenge, and about work for automatically classifying causes of death to their [ICD10](http://www.who.int/classifications/icd/en/) code and jobs to [HISCO](https://socialhistory.org/en/projects/hisco-history-work). There was also time to socialise and enjoy some of the scenery of Raasay, which is a beautiful island the size of Manhattan but with a population of only 160.

<div id="attachment_380" style="width: 310px" class="wp-caption alignleft">
  <a href="http://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26.jpg"><img aria-describedby="caption-attachment-380" class="wp-image-380 size-medium" src="http://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26-300x225.jpg" alt="View from the meeting room" width="300" height="225" srcset="https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26-300x225.jpg 300w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26-768x576.jpg 768w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26-1024x768.jpg 1024w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-18.21.26-620x465.jpg 620w" sizes="(max-width: 300px) 100vw, 300px" /></a>
  
  <p id="caption-attachment-380" class="wp-caption-text">
    View from the meeting room
  </p>
</div>

<div id="attachment_381" style="width: 310px" class="wp-caption aligncenter">
  <a href="http://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24.jpg"><img aria-describedby="caption-attachment-381" class="wp-image-381 size-medium" src="http://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24-300x225.jpg" alt="Sunset over Portree, Skye" width="300" height="225" srcset="https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24-300x225.jpg 300w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24-768x576.jpg 768w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24-1024x768.jpg 1024w, https://www.macs.hw.ac.uk/~ajg33/wp-content/uploads/2016/09/2016-08-28-20.55.24-620x465.jpg 620w" sizes="(max-width: 300px) 100vw, 300px" /></a>
  
  <p id="caption-attachment-381" class="wp-caption-text">
    Sunset over Portree, Skye
  </p>
</div>