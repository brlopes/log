---
title:  "Post"
categories: clog
image: none
---

# side projects

 __ LISTS are mutable __

 ##### Table of Contents
 [tldr;](#tldr;)
 [latest](#latest)

## tldr;

`how started`  
me, looking to design a better web interface for an old ip camera  
have, raspberry pi and LAMP stack (+ perl/python..)

`#what happened`  
then developed web server using python & flask    
then found out the url for stream  
then setup the stream using python *mjpeg* library  
then added web interface for stream  
then with gabe's help found out how to POST php requests to move camera (PTZ) from html buttons  
then pushed the latest code revision to .github and left the project on standby
[reference pdf documentation saved on root]


`#andthen...`  
The initial plan was to build a better web interface for an IP camera, but Synology updated their nice SurveillanceStation software making it compatible with my IP camera model, and at this point a better interface is already designed..


`what might still happen`  
The final plan is to use this python code to create and upload automated 3D [ ] photo sphere images,  
and then later use google cardboard to augment the environment from a file  
I've recently got a Nexus 5 and Im bidding time (this year!) to get back to the final plan

## latest
Im forking this code to stream my home whiteboard updates on my site,   
:D  

```python
#!/bin/python
'''
captures
'''
# camera video stream
# http://192.168.x.x/mjpeg
# static
# http://admin:admin@192.168.x.x/oneshotimage.jpg
```
