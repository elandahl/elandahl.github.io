---
layout: post
title: DePaul Maker Spotlight on Fabricio Marin, Engineering Physics student and Telescope Maker
---

*Auto-tracking telescope using 3D printed gears and controlled using a Raspberry Pi*  

Fabricio S. Marin is a fifth-year student at DePaul University where he is majoring in Physics with a concentration in Electrical Engineering. In the 2015 he worked at DePaul University’s laser laboratory and at Argonne National Labs the next year. His interests gravitate towards controls systems and automation. In his spare time, he makes devices used for imaging and home automation.

### Telescope Tracker Project

This project was motivated by the need for precise control over a telescope’s orientation. In astrophotography or long-exposure imaging, the object of interest needs to stay in frame for long intervals of time, but due to the earth’s rotation and the telescope’s magnification, the image quickly drifts out of frame. Astrophotography becomes increasingly difficult to do unless the motion of the object in frame is offset by some tracking mechanism.

![Original Telescope](/images/FM1.jpg "Original Telescope")

The altazimuth and azimuthal axis both need to be motorized.  Fabricio designed and 3D-printed a geared ring to be connected to the altazimuth axis and secured a timing belt to the outer edge of the base of the telescope mount to serve as a geared ring for the azimuth axis. 

![3D printed gear](/images/FM3.jpg "3D printed gear")

The motors are controlled using a Raspberry Pi. 5V steppers were used because the power supply needed to drive them could also be used to power the Pi, and because they were inexpensive and repeatable.  

![Telescope with controls](/images/FM4.jpg "Telescope with controls")

Bearings were added to each axis to reduce the friction and torque needed.  The telescope can be controlled remotely or manually (using a secondary controller with an Arduino). 

![Making the telescope](/images/FM5.jpg "Making the telescope")

*We are looking for a student, staff, or faculty member to feature each month*  
