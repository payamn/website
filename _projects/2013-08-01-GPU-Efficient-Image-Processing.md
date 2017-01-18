---
layout:     project
title:     GPU Efficient Image Processing 
date:       2013-08-01
code:  
doc:        
demo:
best:       true
image_small: /files/projects_files/2016-11-02-Person-ReIdentification-using-Point-Cloud.png

---

I did this project with my classmate, Tina Khaje, regarding the slow speed of image processing specially for big images. In this project we tried to improve the speed of some image effects using GPU. first, we started using CUDA platform to implement Grayscale, Blurring, Edge detection effects. Then we used GPU optimization techniques to speed up the process, so we achieved 30x speed up for 290 MB image. After that, we learned how to use OPENCL and write our code in OPENCL platform