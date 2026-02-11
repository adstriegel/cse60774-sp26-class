# Lecture 9 - Handout - 02-11-26 - Grad Networks

## Overview

With our deep dive of RED finished, we will now pivot into Quality of Service (QoS) architectures.  Specifically, we will cover the two major QoS architectures proposed in the late 1990s / early 2000s, Integrated Services (IntServ) and Differentiated Services (DiffServ).  IntServ took a flow-centric view of QoS leveraging in part the notion of a flow identifier from IPv6 while DiffServ attempted to improve on the scalability of IntServ by adopting a class-centric view for QoS.  We will discuss the key aspects of each of the respective architectures and then as time allows, discuss a paper on performance evaluation for DiffServ.

## Notes

There is a survey for the class and for course feedback that will be posted via a Canvas announcement and Slack message.

## Readings

* Wednesday - Lecture 9 - Quality of Service Architectures
   * [QoS - A Big Picture](https://ieeexplore.ieee.org/abstract/document/768484)
   * [DiffServ Performance Evaluation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4277052)
* Monday - Lecture 10 - QoS to QoE
   * [CoDel](https://dl.acm.org/doi/pdf/10.1145/2209249.2209264)
   * [QoE Evaluation](https://ieeexplore.ieee.org/abstract/document/8447199)
   * Optional: [PIE vs. CoDel](https://ieeexplore.ieee.org/abstract/document/6849173)
* Wednesday - Lecture 11 - Multimedia, DASH, Multicast
   * [Pensieve](https://dl.acm.org/doi/abs/10.1145/3098822.3098843)
   * [QoS Multicast](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1007412)

## Handouts

* This handout

## Last Lecture - Key Points

* What are the key features that are used by the throughput prediction paper? Why are those features relevant?
* Explain RED at a high level. What is the problem that it is trying to fix?
* Explain the key settings for RED.

## This Lecture - Key Points

* Explain the core concepts with respect to Integrated Services.
* How is RSVP related to IntServ?
* Explain the core concepts with respect to Differentiated Services.
* Compare / contrast: DSCP, BB, EF, AF, BE, Ingress, Egress, PHB.
* Why is end-to-end QoS hard?

## Schedule

| **Date** | **Item** | **Topic** |
|---|---|---|
| 02-11 W | Lecture 9 | QoS Architectures (IntServ, DiffServ) |
| 02-11 W | | Student Paper - Francis, Ben |
| 02-13 F | Due Date | Homework 3 (Note the Changed Date) |
| 02-18 M | Lecture 10 | Evolution of QoS to QoE |
| 02-20 W | Lecture 11 | Multimedia / Adaptation - DASH and Beyond |
| 02-20 F | Due Date | Project Proposal (1-2 paragraphs) |
| 02-20 F | Due Date | Course Feedback Survey  (see Canvas or Slack) |