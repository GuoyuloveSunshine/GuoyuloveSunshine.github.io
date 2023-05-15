---
title: "Detection and Imitation of human mouvement by humanoid robot"
collection: experience
permalink: /experience/ENSTA
date: "Sep. 2022"
venue: 'The research in ENSTA Paris, France'
---

The Keraal project aims to develop a physiotherapist robot called Poppy capable of “coaching” patients during their rehabilitation sessions. Our work is a part of the Keraal project to improve the capability of the Poppy robot. The objective of our work is to detect and imitate human movements by the Poppy robot. Firstly, we try the Blazepose library to detect human skeletons in the collected videos, and we compare the results with those made by the Kinect, Openpose and Vicon library and calculate the differences. We choose the Kinect library as the most suitable library for imitation work. After obtaining the human motions, we build a learning model to apply motion retargeting between two characters. We test the model on animation data from Mixamo, then analyze the performance and propose a method to improve. 


### Movement detection and comparison
![](../images/skeleton.png)
> The skeleton detected by Blazepose, Openpose, Kinect and Vicon.
![](../images/comparison.png)
> The comparison of error between Blazepose-Vicon, Openpose-Vicon and Kinect-Vicon 

### Motion retargeting
![](../images/cycle-en.png)
![](../images/ende-en.png)
> The architecture of two networks

[Download paper here](http://GuoyuloveSunshine.github.io/files/PRe.pdf)
[Download poster here](http://GuoyuloveSunshine.github.io/files/Poster.pdf)