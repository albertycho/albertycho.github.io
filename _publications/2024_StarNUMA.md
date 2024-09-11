---
title: "StarNUMA: Mitigating NUMA Challenges with Memory Pooling"
#authors: '**Albert Cho**, Alexandros Daglis'
collection: publications
category: conferences
permalink: #/publication/2015-10-01-paper-title-number-3
excerpt: '**Albert Cho**, Alexandros Daglis <br><br> Addressing performance bottleneck in large multi-socket machines using CXL.'
date: 2024-11-30
venue: '57th IEEE/ACM International Symposium on Microarchitecture (MICRO 2024)'
slidesurl: #'http://academicpages.github.io/files/slides3.pdf'
paperurl: #'http://academicpages.github.io/files/paper3.pdf'
citation: #'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
**Albert Cho**, Alexandros Daglis

Large multi-socket machines suffer from NUMA effects, where remote and local memory access latency can differ by 4X. StarNUMA introduces a CXL memory device pool directly accessible from all sockets in a single hop, to house shared pages and ameliorate long-latency memory accesses. StarNUMA reduces the average memory access time of a 16-socket system by 35%, yielding performance improvement of 1.13X on average, and up to 1.29X.


<!--The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.-->