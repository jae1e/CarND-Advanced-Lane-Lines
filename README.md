## Advanced Lane Finding
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


In this project, your goal is to write a software pipeline to identify the lane boundaries in a video, but the main output or product we want you to create is a detailed writeup of the project.  Check out the [writeup template](https://github.com/udacity/CarND-Advanced-Lane-Lines/blob/master/writeup_template.md) for this project and use it as a starting point for creating your own writeup.  


Camera calibration
---

* chess board image

<img src="./output_images/1_calibration_chess.png" width="800">

* lane image - distortion correction

<img src="./output_images/2_calibration_road.png" width="800">

Color transform
---

* color transform image

<img src="./output_images/3_color_transform.png" width="500">

Perspective transform
---

* perspective square finding image

<img src="./output_images/4_perspective_finding.png" width="500">

* unwarped image

<img src="./output_images/5_unwarp_lane.png" width="650">

Rectified binary lane image - birds-eye view
---

* rectified binary lane image

<img src="./output_images/6_unwarp_binary_lane.png" width="650">

Lane detection
---

* lane detection image

<img src="./output_images/7_lane_detection_binary.png" width="500">

* lane detection process

<img src="./output_images/8_lane_detection_process.png" width="800">

Curvature and vehicle position
---

* calculation method

Lane marking
---

* lane marking image

<img src="./output_images/9_lane_marking.png" width="800">

Result (Video)
---

* output result image

* project video

* challenge video

* harder challenge video

Discussion?
---

If you're feeling ambitious (again, totally optional though), don't stop there!  We encourage you to go out and take video of your own, calibrate your camera and show us how you would implement this project from scratch!
