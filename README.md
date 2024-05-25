<head>
    <style>
        .image-container {
            display: flex;
            justify-content: space-between; /*Adjust this property to control spacing */
        }
        .image-container img {
            max-width: 45%; /* Adjust image width as needed*/
        }
    </style>
</head>

<head>
    <style>
        /* Add CSS styles here */
        .container {
            display: flex;
            align-items: center;
        }

        .image {
            flex: 1;
            margin-right: 15px; /* Adjust the margin as needed */
        }
    </style>
</head>

<body>
    <div class="container">
        <img class="image" src="./images/IMG_18077.jpg" alt="Image Description" style="width: 300px;">
        <!-- <img src="{{ "images/IMG_18077.jpg" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" /> -->
        <div>
            <!-- <h1>Benjamin C Yang</h1> -->
            <p> 
            I am currently a Masters student in the Mechanical Engineering Department of the University of Illinois at Urbana Champaign. I am a graduate research assistant in the Reliable Autonomy Group @ UIUC. I aspire to become a full stack robotics engineer, working with both software and hardware. <br> 
            
            In my free time I love to build and ride bikes, and apply endless upgrades to my ender3 printer.

            Thingiverse Designs: https://www.thingiverse.com/byang11259/designs
            </p>
        </div>
    </div>
</body>
---

<p style="text-align: center; font-size: 36px"> Past Projects</p>


<div style="text-align:center;">
    <img src="{{ "images/orca_os.gif" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" />
</div>



<body>
    <div class="image-container">
        <img src="{{ "images/NeRF_decreasingLight.gif" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" />
        <img src="{{ "images/NeRF_increasingFog.gif" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" />
    </div>
</body>

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">UAV Simulation: Vision-based Closed Loop Navigation</p>
  <p style="text-align: right;">Fall 2023</p>
</div>

Closed loop vision-based simulation for quadcopter. Images generated from NeRF model of the flying arena. Quadcopter running monte carlo particle filter localization. 

TACAS Submission 2024  <br />
[GitHub Link](https://github.com/byang12159/NeRF_UAV_simulation)





<div style="text-align:center;">
    <img src="{{ "images/ME446_robotpath.gif" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" />
</div>

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">ME446 Project: 6DOF Manipulator Scripting</p>
  <p style="text-align: right;">Spring 2023</p>
</div>

Complete the test environment while demonstrating task space PD and feed forward control tracking, force control, and impedance control.


