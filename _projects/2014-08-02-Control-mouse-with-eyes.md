---
layout:     project
title:     Control mouse with eyes
date:       2014-11-2
code:
doc:
demo: CunvE5Qi5hQ
best:       true
image_small: /files/projects_files/2014-08-02-Control-mouse-with-eyes.png
short: Controlled the mouse pointer by detecting user's gaze direction

---
I used eye tracking to control mouse using OpenCV. First, using a Haar Cascade classifier we detect the pupils. Then we callibrate the position of the pupils with the screen size by asking user to look at four corners of the screen.
