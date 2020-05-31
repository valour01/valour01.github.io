---
title: "An Empirical Study on ARM Disassembly Tools"
collection: publications
permalink: /publication/issta_2020
excerpt: '**Muhui Jiang**, Yajin Zhou*, Xiapu Luo, Ruoyu Wang, Yang Liu, Kui Ren'
date: 2020-01-01
venue: 'Proceedings of the ACM SIGSOFT International Symposium on Software Testing and Analysis (**ISSTA 2020 To Appear**)'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
#citation: 'our Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

[Paper(Preprint)](https://www.muhui.site/files/issta20.pdf)

With the increasing popularity of embedded devices, ARM is becom-ing the dominant architecture for them. In the meanwhile, there isa pressing need to perform security assessments for these devices.Due to different types of peripherals, it is challenging to dynami-cally run the firmware of these devices in an emulated environment.Therefore, the static analysis is still commonly used. Existing workusually leverages off-the-shelf tools to disassemble stripped ARMbinaries and (implicitly) assume that reliable disassembling binariesand function recognition are solved problems. However, whetherthis assumption really holds is unknown.
In  this  paper,  we  conduct  the  first  comprehensive  study  onARM disassembly tools. Specifically, we build1,896ARM bina-ries (including248obfuscated ones) with different compilers, com-piling options, and obfuscation methods. We then evaluate themusing eight state-of-the-art ARM disassembly tools (including bothcommercial and noncommercial ones) on their capabilities to lo-cate instructions and function boundaries. These two are funda-mental ones, which are leveraged to build other primitives. Ourwork  reveals  some  observations  that  have  not  been  systemati-cally summarized and/or confirmed. For instance, we find thatthe existence of both ARM and Thumb instruction sets, and thereuse of theBLinstruction for both function calls and branchesbring serious challenges to disassembly tools. Our evaluation shedslight on the limitations of state-of-the-art disassembly tools andpoints out potential directions for improvement. To engage thecommunity,  we  release  the  data  set,  and  the  related  scripts  at [https://github.com/valour01/arm_disasssembler_study](https://github.com/valour01/arm_disasssembler_study).

