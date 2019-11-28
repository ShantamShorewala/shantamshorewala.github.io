---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p align="justify">
I am a robotics enthusiast currently working as a research associate at the Autonomous Robotics Laboratory, IIT Delhi. In particular, my research interests include <b> computer vision, motion planning, artificial intelligence and autonomous systems </b>. I graduated from Manipal Institute of Technology in 2019 with a B.Tech. in Electronics & Communication. Previously, I have worked as a research intern at the <a href="https://cps.iisc.ac.in/">RBCCPS Lab</a> at IISc, Bengaluru and also at <a href="http://robotics.iiitd.edu.in/coral/">IIIT, Delhi</a>. Before that, I also was the team lead of a robotics team, <a href="http://www.marsrovermanipal.com/">Mars Rover Manipal</a>, which develops Mars rover prototypes to compete at <a href="http://urc.marssociety.org/">University Rover Challenge</a>. 
</p>

Projects:
<ul style="list-style-type:disc;">  
   <li>Past</li>
    <ul style="list-style-type:circle;">
      <li> <p align="justify"> <b>Link Speed estimation</b> : The aim was to develop an algorithm to estimate link speeds from a calibrated monocular camera. Our approach leveraged deep learning for tracking a specific class of vehicles popular on Indian roads (autorickshaws) and detecting specific keypoints on the tracked vehicles. The 2D keypoints in the image, complemented by a 3D model of the vehicle, were used to compute the pose of the vehicle in multiple frames. Using the computed pose, we were able to estimate individual vehicle speeds which were averaged to get link speeds. This work was included in a pilot deployment in Bengaluru, India. </p>

<div class="w3-content w3-section" style="max-width:500px" align="right"> 
  <img class="mySlides1 w3-animate-fading" src="images/example_speed-min.png" style="width:100%" align="center">
  <img class="mySlides1 w3-animate-fading" src="images/speed_example_2-min.png" style="width:100%" align="center">
</div>

<script>
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides1");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 9000);    
}
</script>

      </li>
  
      <li> <p align="justify"> <b>Target detection and tracking</b>: As a part of the vision and machine learning team  at IISc for Mohammed Bin Zayed International Robotics Competition 2020, I worked on detecting and tracking a high-speed dynamic target (a ball suspended from an autonomous drone) for distances upto 20 m. The system used a Kalman filter to track the target, segmneted by color and shape features, continuosly at even larger distances from a monocular view.</p> 
      
      <img src="images/img115.jpg" style="width:60% height:60%" align="center">
      
      </li>

      <li><p align="justify"><b>Mars Rover Manipal</b>: Competing at the University Rover Challenge 2018, led a team of 23 undergraduatre students to develop a Mars rover prototype. Our rover had a 6-DoF robotic manipulator which could be teleoperated from a remote base station. The rover was also capable of autonomous traversal in extreme terrain relying on GPS, IMU and a vision system. We have established ourselves as the leading Asian team in this competition over the last few years in face of exceptional competiton. You can see some of the rovers developed by our team <a href="https://www.youtube.com/channel/UCFDob5Vn5xccQ1T3_cnt8CA">here</a>. 
      
<div class="w3-content w3-section" style="max-width:500px" align="right"> 
  <img class="mySlides w3-animate-fading" src="images/intro-bg.jpg" style="width:100%" align="center">
</div>

<script>
var myIndex = 0;
carousel_2();

function carousel_2() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 9000);    
}
</script>
      </p>
      </li>
      
      <li><p align="justify"><b>Aerial Image Segmentation for Precision Agriculture</b>: Implemented multiple supervised deep learning models to segment aerial images to identify crop and weed plants. Worked with multispectral images such as NIR, NDVI and RGB. The work done was completed as a part of my summer internship at IIIT, Delhi. </p>
    </li>
    </ul>
    
  <li>Current</li>
  
  <ul style="list-style-type:circle;">
    <li><p align="justify"><b> Semi-supervised Image Segmentation for Precision Agriculture </b> : My previous work on supervised learning for aerial image segmentation required large amounts of labelled data for training the models. Since there are a large number of crop and weed plants species, I am working on a semi-supervised approach to the problem to reduce the dependency on data for each new crop/weed plant. The objective is to build a pipeline that can quickly adapt to new plant species without the need for a large amount of labelled masks as ground truth so as to further advance the feasibility of precision agriculture. </p> </li>
  
    <li><p align="justify"><b> Autonomous Calibration of Mobile Manipulators </b> : Robotic manipulators are used significantly in assembly lines. However, these manipulators are stationary and inherently more accurate as compared to mobile manipulators. Since, mobile manipulation has the potential to further aid a variety of tasks as compared to  the scope of a stationary manipulator, we are working to develop an approach to self-calibrate these robots to achieve higher accuracy. </p> </li> </ul> 
  
</ul> 



  
