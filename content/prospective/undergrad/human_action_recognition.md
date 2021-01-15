---
title: Human Action Recognition from AD Movies
visible: false

links:
- icon: graduation-cap
  icon_pack: fas
  name: CSE Thesis
  url:  https://webcms3.cse.unsw.edu.au/THES0001/16s1/outline 
  
tags:
- machine learning
- robotics
- cse-honours

---

## Context

Action Recognition is curcial for robots to perfoma around humans. 
Indeed, robot need to asses human action and intentions in order to assist them in everyday life tasks and to collaborative efficiently. 

The field of action recognition has  aimed to use typical sensors found on robots to recognize agnts, objects and actions they are performing.
Typical approach is to record a dataset of various action and label them. But often theses actions are not natural and it can be difficult to represent the variety of ways to perform actions with a lab built dataset. 
In this project we propose to use audio desription movies to label actions.
AD movies integrate a form of narration to allow virually impaired veiwers to undertsnad the visual element sowed on screen.
This information often deals with action actually depicted on the scene. 

## Goals & Milestones

During this project, the student will:
- Develop a pipeline to collect and crop clip of AD movies for at home actions. 
This extraction tool should be fexible and allow for integration of next action. It will for instance feature video and text processing to extract [Subject+ Action + Object] type of data.
- Investigate methods for HAR
- Implement a tree model combaning HAR with YOLO to identify agent and objects
- Evaluate the HAR pipeline with the Toyota Robot HSR

## Topics

Human Action Recognition, 

## Prerequisites

- Skills: Python, C++, Git.

## References

- https://www-sciencedirect-com.wwwproxy1.library.unsw.edu.au/science/article/pii/S174228761930283X
- https://openaccess.thecvf.com/content_cvpr_2015/papers/Rohrbach_A_Dataset_for_2015_CVPR_paper.pdf
- https://dl-acm-org.wwwproxy1.library.unsw.edu.au/doi/abs/10.1145/3355390?casa_token=MrZSE8hoPFYAAAAA:rcwHYdISRyLM5OApuN_2SASbwgBsswxx2EPHy9mGP8NaqIdvBj0q5LIa9_ChdyI_Lzfi4GX0PWjhD54
- https://prior.allenai.org/projects/charades
- https://arxiv.org/pdf/1708.02696.pdf
- https://arxiv.org/pdf/1806.11230.pdf


