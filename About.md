---
layout: page
permalink: /admin/
title: About Us
---
<style>
  .adminheading {
    font-size: 35px; 
    color: white; 
    font-family: MyCustomFont;
  }
</style>
<hr>
<div class="veil">
<br>
<p> 
We are the Robotics and Technology Club of NISER, Bhubaneswar. We are a student-run body that functions under Dr. Subhankar Mishra’s Lab, School of Computer Sciences, NISER.


<br>
<br>

Our objective is to learn and propagate the knowledge about current day technology, and the skills required to incorporate it in our daily lives as well as academic curriculum. Our domain includes- Automation, IOT, Machine Learning, 3D Printing etc.
</p>

<br>
<br>

<img src="/images/About1.jpg" height="25%" width="100%" style="border: solid 4px white; border-radius: 40px 40px 40px 40px;">
<br>
<br>

<h4 style="font-size: 24px; color: grey; margin-bottom: 20px; font-family: MyCustomFont">The Story of</h4>

<h3 style="font-size: 35px; color: darkgoldenrod; font-family: MyCustomFont; font-weight: bolder;">RoboTech Club, NISER</h3>
<p style="font-weight: 600px;">This student-run club was established in 2015, along the lines of similar clubs in the IITs and various engineering colleges. In 2019, we started functioning under Dr. Subhankar Mishra’s Lab in the School of Computer Sciences, NISER and we work with cutting edge robotic technologies,  equipment and  modern tools such as 3D Printers, various micro-controllers, machining toolkits and numerous other instruments</p>
<p style="font-weight: 600px;">Initially set up as a means to serve the hobbies of a group of robotics enthusiasts, the club has grown into a much bigger endeavor with numerous achievements, producing highly skilled alumni. We seek to provide the students of NISER with the opportunity to turn their novel ideas into reality. Most of our current projects are direct products of the handwork of such innovative students. We have worked on several fun and useful projects, listed in the projects page. We also love to do competitive robotics and participate in various Robotics Competitions, held around the country. We have a number of projects dedicated to those competitions. We have also collaborated with different clubs and departments of NISER in our ventures.</p>
<br>
<span class="adminheading">Joining the Club:</span>
<hr>
<br>
<p>Each academic year, the RoboTech Club seeks passionate individuals who are eager to contribute to our ambitious projects. While prior technical skills are not mandatory (coding, for example, isn't always our top priority), new members are expected to quickly develop the technical, social, and management skills necessary for the smooth operation of the club.
<br>
<br>
Membership is open to students from NISER who can commit at least 2-3 years to the club, ensuring long-term collaboration and contribution to our goals. To maintain a strong sense of community and ensure the efficient functioning of the club, we limit the number of members. However, we are always open to engaging with people outside the club for discussions, collaborations, and idea-sharing.
</p>
<br>

<span class="adminheading">Our Core Activities:
</span>
<hr>
<br>
<p>
<ul>
<li>Technical projects and experiments in robotics.</li>
<li>Pan-India level competition and platform for robotics idea realization.</li>
<li>Pan-India level publication of magazine which serves as a guide for students to expand their horizons in robotics & technology.</li>
<li>Host robotics competitions in our institute.</li>
<li>Participation [and win ;) ] in robotics competitions.</li>
</ul>
</p>
<br>

<span class="adminheading">Space and Funding:
</span>
<hr>
<br>
<p>
<ul>
<li>RoboTech Club functions at the Robotics Lab, CC-3, School of Mathematical Sciences building</li>
<li>The club is graciously funded by the School of Computer Sciences for all its efforts.</li>
</ul>
</p>
<br>
<span style="color: #ffffff;font-family: MyCustomFont;font-size:35px;">Gallery of our Domain:</span>
<hr>
<br>

<br>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <style>
    .gallery-container {
      border: 2px solid white;
      padding: 20px;
      height: 320px; 
      overflow-y: auto; 
      color: black
      background-color: black;
    }
    .keyword {
      margin-bottom: 10px;
    }
    .keyword button {
      cursor: pointer;
      padding: 5px 10px;
      margin-right: 10px;
      border: none;
      background-color: transparent;
      text-decoration: underline;
      color: white;
    }
    .keyword button:hover {
      background-color: orange; 
    }
    .keyword button.active {
      background-color: blue; 
      color: white;
      text-decoration: underline; 
    }
    .image-container {
      overflow-x: auto; 
      white-space: nowrap;
    }
    .image-wrapper {
      display: inline-block;
      text-align: center;
      vertical-align: top;
      width: 300px; 
      margin-right: 20px; 
    }
    .image {
      width: 100%;
      border: 2px solid black;
      object-fit: cover;
      transition: transform 0.3s ease;
    }
    .image-description {
      margin-top: 5px;
      color: white;
    }
  </style>
</head>
<body onload="showImages('keyword1')">
  <div class="gallery-container">
    <div class="keyword">
      <button onclick="showImages('keyword1')" class="active">Projects</button>
      <button onclick="showImages('keyword2')">Equipment</button>
      <button onclick="showImages('keyword3')">Experiment</button>
      <button onclick="showImages('keyword4')">Workspace</button>
    </div>
    <hr>
    <br>
    <div class="image-container">
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/robsket.jpg" height="200" width="200">
        <div class="image-description">Robotic Sketcher</div>
        <br>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/scop.png" height="200" width="200">
        <div class="image-description">Scorpion</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/radio.jpg" height="200" width="200">
        <div class="image-description">Radio Telescope</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/maze.jpg" height="200" width="200">
        <div class="image-description">Maze Solver Bot</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/remote.png" height="200" width="200">
        <div class="image-description">Remote Site Monitoring System</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/pragyan.jpg" height="200" width="200">
        <div class="image-description">Pragyan Rover</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/smart.jpg" height="200" width="200">
        <div class="image-description"> Smart Mirror</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/line.jpg" height="200" width="200">
        <div class="image-description">Line Follower</div>
      </div>
      <div class="image-wrapper" id="keyword1">
        <img class="image" src="/images/amar.png" height="200" width="200">
        <div class="image-description">AMaR</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq1.jpg" height="200" width="200">
        <div class="image-description">Keysight Model</div>
        <br>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq2.jpg" height="200" width="200">
        <div class="image-description">3D Printer</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq3.jpg" height="200" width="200">
        <div class="image-description">Flashforge Finder</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq4.jpg" height="200" width="200">
        <div class="image-description">FDM 3D Printer</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq5.jpg" height="200" width="200">
        <div class="image-description">Creality CR10S500</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq6.jpg" height="200" width="200">
        <div class="image-description">Flux Beambox Pro</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq7.jpg" height="200" width="200">
        <div class="image-description">SLA Printer</div>
      </div>
      <div class="image-wrapper" id="keyword2" style="display: none;">
        <img class="image" src="/images/eq8.jpg" height="200" width="200">
        <div class="image-description">Laser Workings</div>
      </div>
      <div class="image-wrapper" id="keyword3" style="display: none;">
        <img class="image" src="/images/ex1.jpg" height="200" width="300">
        <div class="image-description">Arduino Teaching Lessons</div>
        <br>
      </div>
      <div class="image-wrapper" id="keyword3" style="display: none;">
        <img class="image" src="/images/ex2.jpg" height="200" width="300">
        <div class="image-description">Tesla Coil Working Demo</div>
      </div>
      <div class="image-wrapper" id="keyword4" style="display: none;">
        <img class="image" src="/images/wk1.jpg" height="200" width="200">
        <div class="image-description">Our Lab with  Awesome Resources</div>
        <br>
      </div>
      <div class="image-wrapper" id="keyword4" style="display: none;">
        <img class="image" src="/images/wk2.jpg" height="200" width="200">
        <div class="image-description">Handy Working Area</div>
      </div>
    </div>
  </div>

  <script>
    function showImages(keyword) {
      const images = document.querySelectorAll('.image-wrapper');
      images.forEach(image => {
        if (image.id === keyword) {
          image.style.display = 'inline-block';
        } else {
          image.style.display = 'none';
        }
      });

      document.querySelectorAll('.keyword button').forEach(btn => {
        btn.classList.remove('active');
      });

      document.querySelector(`.keyword button[data-keyword="${keyword}"]`).classList.add('active');
    }
  </script>
</body>







