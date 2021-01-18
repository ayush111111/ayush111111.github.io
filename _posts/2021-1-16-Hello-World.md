---
layout: post
title: PD Control line follower
published: true
---

Follow line behaviour in a Formula-1 car, using images as input
It has two controllers, for rotation and speed.

## Image Processing
# 1. Colour filtering
	The red line present on the formula track is to be followed.
    A "mask" is developed using the RGB values of the input image are thresholded such that only red colour is highlighted.
    Overlaying this mask over the input image gives us a red coloured blob representing the line to be followed.
	

# 2. Finding a single point to be tracked
## PD control

[![gazebo simulation of Formula Car](https://yt-embed.herokuapp.com/embed?v=PHs2H54jiRc)](https://www.youtube.com/watch?v=PHs2H54jiRc "gazebo simulation of Formula Car")

[![camera feed along with processed image](https://yt-embed.herokuapp.com/embed?v=4kmUJu2Xqlg)](https://www.youtube.com/watch?v=4kmUJu2Xqlg "camera feed along with processed image")

**above project is a solution to exercise problems on [JDE Robotics Academy](http://jderobot.github.io/RoboticsAcademy/)**