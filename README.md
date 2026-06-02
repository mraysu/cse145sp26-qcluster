# Qualcomm Clustering

## Links
Benchmarking Scripts: https://github.com/AlainZhangStudent/cse199-benchmarking-scripts

OpenCL Docker Image: https://github.com/KastnerRG/qualcomm-docker-image

Initial Proposal: https://github.com/KastnerRG/qualcomm-cluster

Autograder Setup: https://github.com/junkyard-computing/junkyard-autograder

Project Specification: https://docs.google.com/document/d/1bGuacAcaV2-XZTo-KWgVFfr9i1XaQ5Ia_mERNPMgnqo/edit?usp=sharing

Oral Report Presentation: https://docs.google.com/presentation/d/1_RRs3qRQV2yop3uGqzG5ULQS8ev7lnmhPA6lSn4YTX0/edit?usp=sharing

Milestone Report: https://docs.google.com/document/d/1Z4VhqCuE6MwD5AjcHFxpnRuKAo-5iLU9fI9hVrGW4mo/edit?usp=sharing

## Abstract

Embedded development boards such as the Rubik Pi 3, designed by Qualcomm, are powerful devices that, when joined together to form a unified cluster, can perform as an efficient and alternative way to construct a data server. Qualcomm is searching for a way to develop its own server cluster made up entirely of its Rubik Pi 3 development boards, to study how they perform in union, and what a Qualcomm Cluster is capable of doing when put together. Server clusters, such as the one we're developing, take advantage of an array of computing nodes to balance workloads and manage the resources available to them when running tasks. We have continued to develop on this idea by preparing for the assembly of a V1 of the Qualcomm Cluster, building off of the current V0 that only contains 14 Rubik Pis, a rudimentary/inefficient power system, and an oversized chassis. Our progress on V1 of the Qualcomm Cluster consists of preliminary testing/documentation on 5V GPIO power, which showed that the initial 15W for testing resulted in shutdown during stress testing, and a new power system proposal consisting of a power distribution PCB and PiHats to distribute 20W to a potential full tray system of 24 Rubik Pis, complete with a bill of materials needed. We have also conducted testing and benchmarking of the current V0 of the Qualcomm Cluster to provide some data/results on how an early iteration of the cluster handles workloads

## Setup

2 additional folders store the files used to progress this project in different ways. The hardware folder contains anything related to the development of the power system, including PCB files and spreadsheets related to the testing of 5V GPIO on the Rubik Pi. The software folder contains any scripts or data from benchmarking of the V0 cluster. 

## Team Members
- Aarnav Gujjari - CSE 145 Student
- Alain Zhang - CSE 199 Student
- Ferrari Guan
- Michael Sullivan- CSE 145 Student
- Yian Zhuang - CSE 145 Student
- Yves Mojica - CSE 145 Student
