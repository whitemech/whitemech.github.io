---
layout: post
title: On-the-fly Synthesis for LTL over Finite Traces
---

**When**:  Thursday, May 6, 2021, 12pm (CEST).

**Where**: Zoom online, check the address in the Google Calendar Event.

**Topic**: On-the-fly Synthesis for LTL over Finite Traces.

**Speaker**: [Jianwen Li](https://scholar.google.com/citations?user=kpv4RzgAAAAJ&hl=en), Youth Research Professor, East 
China Normal University, Shanghai.

#### Abstract
We present a new synthesis framework based on the on-the-fly DFA construction for LTL over finite traces (LTLf ). Extant 
approaches rely heavily on the construction of the complete DFA w.r.t. the input LTLf formula, whose size can be doubly 
exponential to the size of the formula in the worst case. Under those approaches, the synthesis cannot be conducted 
unless the whole DFA is completely constructed, which is not only inefficient but also not scalable in practice. Indeed, 
the DFA construction is the main bottleneck of LTLf synthesis in prior work. To mitigate this challenge, we follow two 
steps in this paper: Firstly, we present several light-weight preprocessing techniques such that the synthesis result 
can be obtained even without DFA construction; Secondly, we propose to achieve the synthesis together with the 
on-the-fly DFA construction such that the synthesis result can be obtained before constructing the whole DFA. The 
on-the-fly DFA construction is implemented using the SAT-based techniques for automata generation. We compared our new 
approach with the traditional ones on extensive LTLf synthesis benchmarks. Experimental results showed that the 
preprocessing techniques have a significant advantage on the synthesis performance in terms of scalability, and the 
on-the-fly synthesis is able to complement extant approaches on both realizable and unrealizable cases.

#### Material
- [Slides](https://drive.google.com/file/d/1LVPGgv--bCB5Ra18kNVR3-jfQtycko9p/view?usp=sharing)
- [Video](https://uniroma1.zoom.us/rec/share/MwS9szNGU36fCsuDFHkOWONEA-LjDqOiXH4G7lp_2ZyaeALY6gbbxRQM6FTTWjLp.9tAW4X-_qlVZOCQI)
  (Passcode: fxC.J3TL)
