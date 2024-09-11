---
title: "Patching up Network Data Leaks with Sweeper"
#authors: '**Albert Cho**, Alexandros Daglis'
collection: publications
category: conferences
permalink: #/publication/2015-10-01-paper-title-number-3
excerpt: 'Marina Vemmou, **Albert Cho**, Alexandros Daglis <br><br> Identifying and removing bottleneck in network applications.'
date: 2022-10-30
venue: '55th IEEE/ACM International Symposium on Microarchitecture (MICRO 2022)'
slidesurl: #'http://academicpages.github.io/files/slides3.pdf'
paperurl: #'http://academicpages.github.io/files/paper3.pdf'
citation: #'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Marina Vemmou, **Albert Cho**, Alexandros Daglis

Modern NICs write/read packets directly into the LLC, bypassing memory. However, dirty packet writebacks still generate a significant amount of memory traffic, even though the evicted packets are never used again. To this end, we propose Sweeper, which marks the used packets to omit their writeback. Sweeper improves the peak sustainable throughput of a server by up to 2.6X. 


<!--The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.-->