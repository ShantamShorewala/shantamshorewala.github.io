---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Website under work!

<p align="justify">
I am a robotics enthusiast currently working as a research associate at the Autonomous Robotics Laboratory, IIT Delhi. Within robotics, my research interests include computer vision, motion planning, artificial intelligence and autonomous systems. I graduated from Manipal Institute of Technology in 2019 with a B.Tech. in Electronics & Communication. Previously, I have worked as a research intern at the <a href="https://cps.iisc.ac.in/">RBCCPS Lab</a> at IISc, Bengaluru and also at <a href="http://robotics.iiitd.edu.in/coral/">[IIIT, Delhi]</a>. I also was the team lead of a robotics team, <a href="http://www.marsrovermanipal.com/">Mars Rover Manipal</a>, which develops Mars rover prototypes to compete at <a href="http://urc.marssociety.org/">University Rover Challenge</a>. 
</p>

Projects:
<p align="justify">
 <ul style="list-style-type:disc;">  
   <li>Past</li>
    <ul style="list-style-type:circle;">
      <li> <p align="justify"> Link Speed estimation : The aim was to develop an algorithm to estimate link speeds from a calibrated monocular camera. Our approach leveraged deep learning for tracking a specific class of vehicles popular on Indian roads (autorickshaws) and detecting specific keypoints on the tracked vehicles. The 2D keypoints in the image, complemented by a 3D model of the vehicle, were used to compute the pose of the vehicle in multiple frames. Using the computed pose, we were able to estimate individual vehicle speeds which were averaged to get link speeds. This work was included in a pilot deployment in Bengaluru, India. 
      
<div class="slideshow-container">

  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="images/index.jpg" style="width:100%">
    <div class="text">Caption Text</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="img2.jpg" style="width:100%">
    <div class="text">Caption Two</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
</div> 

* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
} 

      </p></li>
  
      <li> <p align="justify"> Target detection and tracking: As a part of the vision and machine learning team  at IISc for Mohammed Bin Zayed International Robotics Competition 2020, I worked on detecting and tracking a high-speed dynamic target (a ball suspended from an autonomous drone) for distances upto 20 m. </p> </li>

    </ul>
  <li>Current</li>
</ul> 
</p>

<p align="justify>

* Current
  - Unsupervised image segmentation for precision agriculture
  - Autonomous calibration of mobile manipulators

</p>
