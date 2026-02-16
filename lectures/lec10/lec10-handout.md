# Lecture 10 - Handout - 02-16-26 - Grad Networks

## Overview

In the last lecture, we looked at the two major QoS architectures, Integrated Services (IntServ) and Differentiated Services (DiffServ).  IntServ took a flow-centric approach and as a result, struggled due to scaling concerns.  DiffServ took the approach of relative differentation, differentiating the performance of classes.  Both struggled with how to truly deliver end-to-end QoS and were largely made unneeded by gains in the core of the network though QoS indirectly has resurged (a bit) due to constraints in the last wireless mile.  In today's lecture, we will look at an instrumentation paper for DiffServ that examines how to measure performance.  We will continue looking at CoDel and then will conclude with a transition to Quality of Experience (QoE) if time allows.

## Readings

* Monday - Lecture 10 - QoS to QoE
   * [CoDel](https://dl.acm.org/doi/pdf/10.1145/2209249.2209264)
   * [QoE Evaluation](https://ieeexplore.ieee.org/abstract/document/8447199)
   * Optional: [PIE vs. CoDel](https://ieeexplore.ieee.org/abstract/document/6849173)
* Wednesday - Lecture 11 - Multimedia, DASH, Multicast
   * [Pensieve](https://dl.acm.org/doi/abs/10.1145/3098822.3098843)
   * [QoS Multicast](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1007412)
* Next Monday - Module 3 - Wireless


## Last Lecture - Key Points

* Explain the core concepts with respect to Integrated Services.
* How is RSVP related to IntServ?
* Explain the core concepts with respect to Differentiated Services.
* Compare / contrast: DSCP, BB, EF, AF, BE, Ingress, Egress, Edge Router, Core Router, PHB.

## This Lecture - Key Points

* *From last lecture:* Why is end-to-end QoS hard?
* What is the major insight from CoDel? Is it knob free or mostly knob free?
* Where is CoDel or for that matter, QoS most relevant?
* What is QoE and how does it differ from QoS?
* What makes capturing QoE hard?

## Schedule

| **Date** | **Item** | **Topic** |
|---|---|---|
| 02-18 M | Lecture 10 | Evolution of QoS to QoE |
| 02-18 W | | Student Paper - Rana |
| 02-20 W | Lecture 11 | Multimedia / Adaptation - DASH and Beyond |
| 02-20 F | Due Date | Project Proposal (1-2 paragraphs) |
| 02-20 F | Due Date | Course Feedback Survey  (see Canvas or Slack) |