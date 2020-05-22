---
title: "PERDICE: Towards Discovering Software Inefficiencies Leading to Cache Misses and Branch Mispredictions"
collection: publications
permalink: /publication/compsac_2018
excerpt: 'Ting Chen, Wanyu Huang, **Muhui Jiang**, Xiapu Luo, Lei Xue, Ying Wang, Xiaosong Zhang'
date: 2018-01-01
venue: 'Proceedings of the 42nd Annual Computer Software and Applications Conference (**COMPSAC 2018**)'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
CPU cache misses and branch mispredictions waste CPU cycles and affect program performance. Such software inefficiencies could be neither eliminated by existing compilers nor avoided by developers. In this paper, we propose a novel approach, named PERDICE, to automatically discover such performance bugs by leveraging concolic execution. PERDICE adopts a new path exploration algorithm to discover such software inefficiencies. In particular, we measure performance losses in the granularity of program locations (e.g., instructions, source code lines) instead of paths to avoid getting stuck into the code without software inefficiencies. Moreover, when scoring test inputs, our new approach prefers the test inputs incurring increments in performance losses. This strategy allows PERDICE to avoid getting stuck into the software inefficiencies that have been found. We have implemented PERDICE for both PC (X86 instructions) and Android smartphones (ARM instructions). The experimental results with real-world desktop software and Android native code show that PERDICE outperforms the other four popular algorithms and PROFs (a multi-path performance profiler) in terms of the speed to discover software inefficiencies and the severity (i.e, amount of wasted CPU cycles) of inefficiencies.

