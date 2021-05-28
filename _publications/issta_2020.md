---
title: "An Empirical Study on ARM Disassembly Tools"
collection: publications
permalink: /publication/issta_2020
excerpt: '**Muhui Jiang**, Yajin Zhou*, Xiapu Luo, Ruoyu Wang, Yang Liu, Kui Ren'
date: 2020-01-01
venue: 'Proceedings of the ACM SIGSOFT International Symposium on Software Testing and Analysis (**ISSTA 2020 **)'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'our Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---


With the increasing popularity of embedded devices, ARM is becoming the dominant architecture for them. In the meanwhile, there is a pressing need to perform security assessments for these devices. Due to different types of peripherals, it is challenging to dynamically run the firmware of these devices in an emulated environment.Therefore, the static analysis is still commonly used. Existing work usually leverages off-the-shelf tools to disassemble stripped ARM binaries and (implicitly) assume that reliable disassembling binaries and function recognition are solved problems. However, whether this assumption really holds is unknown.
In  this  paper,  we  conduct  the  first  comprehensive  study  on ARM disassembly tools. Specifically, we build 1,896 ARM binaries (including 248 obfuscated ones) with different compilers, compiling options, and obfuscation methods. We then evaluate themusing eight state-of-the-art ARM disassembly tools (including both commercial and noncommercial ones) on their capabilities to locate instructions and function boundaries. These two are fundamental ones, which are leveraged to build other primitives. Our work  reveals  some  observations  that  have  not  been  systemati-cally summarized and/or confirmed. For instance, we find that the existence of both ARM and Thumb instruction sets, and the reuse of the BL instruction for both function calls and branches bring serious challenges to disassembly tools. Our evaluation sheds light on the limitations of state-of-the-art disassembly tools and points out potential directions for improvement. To engage the community,  we  release  the  data  set,  and  the  related  scripts  at [https://github.com/valour01/arm_disasssembler_study](https://github.com/valour01/arm_disasssembler_study).

