---
title: Rosona - Robot's Social Navigation
summary: Investigate how robots could be made aware of social navigation
tags:
- social navigation
- human-robot interaction
- group
date: 'Jan 2021'
showthedate : false

# Optional external URL for project (replaces project detail page).
#external_link: http://example.org
links:
- icon: user
  icon_pack: fas
  name: Wafa Johal
  url: 

- icon: user
  icon_pack: fas
  name: Oltan Sevinc
  url: 

- icon: user
  icon_pack: fas
  name: Claude Sammut
  url: 

- icon: user
  icon_pack: fas
  name: Andrew Haigh
  url: 

- icon: user
  icon_pack: fas
  name: Andrew Haigh
  url: 

image:
  caption: 
  focal_point: 

---

# Join the group

## Project overview
Enabling robots to navigate in indoors environments in a safe and socially acceptable manner around groups of humans is still an open research area. Socially aware navigation considers the multi-modal assessment of the group dynamics, group formation inferring, path planning, real-time path adaptation, and human-robot communication.
Up to now the research in the field has considered a couple of classical scenarios such as crossing a group in a corridor or passing a door. Limitations in terms of lack of realistic datasets is often mentioned in the field. In this research project, we will aim to design several scenarios involving groups of humans in realistic settings. Our work will focus on three main tasks for the robot: 
1) approach and join a group, 2) passing by a group and 3) greeting a group. A first step of the project will be to record a novel dataset with rich interactions between the humans (H-H scenarios) and between humans and a teleoperated robot (H-R scenarios). The dataset will be collected at the HRI facility allowing multimodal synchronous recording. After that, a new model for path planning} will be developed. For the model, we will explore rule-based constraints (i.e. not passing between two persons speaking together) and learned constrained using the dataset recorded to infer implicit social norms. Finally, the model will be tested empirically with new users in which the robot will have to take real-time path planning decisions.

## Schedule

{{< figure library="true" src="schedule.PNG" title="" >}}



## Expected Outcomes
- A dataset featuring different scenarios of groups and spatial interactions will be recorded at the HRI facility in Paddington. After anonymization, the dataset will be made open.
- Development of a novel socially aware module allowing the robot to approach and leave groups using a hybrid method (rule-based and data-driven)
  - Empirical evaluation with end-users in the National Facility for HRI
- Report or conference publication at CoRL (Conference on Robot Learning – July 2021) or at the Robotics and Automation-Letters (RA-L)
 - The code implemented during this project must be fully documented