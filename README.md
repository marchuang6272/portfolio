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
         .rounded-image {
            border-radius: 20px; /* Adjust the value to change the roundness */
            flex: 1;
            margin-right: 35px; /* Adjust the margin as needed */
        }

        .grid {
            display: grid;
            grid-template-columns: auto; /* Left takes 2/3, right takes 1/3 */
            grid-template-rows: 2fr 1fr; /* Auto height rows */
            gap: 10px; /* Adjust the gap as needed */
            max-width: 800px; /* Adjust the max-width as needed */
            height:100%;
        }

        .left-image {
            height: 100%;
            width: auto; /* Automatically adjust height */
            grid-column: span 2; /* Spans both rows */
        }

        .bottom-right-image {
            height: 100%;
            width: auto; /* Automatically adjust height */
        }

        .bottom-left-image {
            height: 100%;
            width: auto; /* Automatically adjust height */
        }
    </style>
</head>

<body>
    <div class="container">
        <img class="rounded-image" src="./images/headshot.png" alt="headshot" style="width: 300px;">
        <div>
            <p> 
                Hello! My name is Marcanthony Huang. I am a recent graduate from University of Illinois Urbana-Champaign’s Grainger School of Engineering. Within software engineering, my skills and interests revolve around computer hardware, systems programming, and machine learning. Outside of industry, I am passionate about computer engineering research, specifically in computer architecture and robotics. Currently, I work as a software engineer and researcher at the Future Architecture and System Technology for Scalable Computing Laboratory. 
            </p>
        </div>
    </div>
</body>
---

<p style="text-align: center; font-size: 36px"> Projects</p>





<body>
    <div class="text-align:center;">
        <img src="{{ "images/codegen.gif" | prepend: site.baseurl | prepend: site.url}}" alt="zigzag" />
    </div>
</body>

<br>
<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">Research Project: ML-Driven Hardware Design Space Exploration</p>
  <p style="text-align: right;">Fall 2023</p>
</div>

As a software engineer and research assistant at the Future Architecture and System Technology for Scalable Computing Laboratory, I collaborated with Google DeepMind researchers on machine learning-assisted computer architecture projects. I engineered a large-scale microarchitecture design space exploration framework using Python and PyTorch, incorporating open-source RTL synthesis tools, reinforcement learning frameworks, and architecture simulators. Additionally, I modified open-source HDL compilers in C++ to create custom SystemVerilog intermediate representations, enabling the integration of custom RISC-V vector processor architectures into machine learning frameworks.


<br>



<div style="text-align:center;">
    <img src="{{ "images/orca.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" />
</div>

<br>

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">ORCA-OS: A Functional Unix-based OS Kernel</p>
  <p style="text-align: right;">Spring 2023</p>
</div>

I worked on a semester-long project to design and implement a functional Unix-based operating system kernel written in C and x86 assembly. This project involved creating a kernel capable of paged virtual memory management, interrupt handling, and process scheduling. Key features of ORCA OS include an in-memory file system, user/kernel privileges, multiple terminals, a virtualized clock, preemptive scheduling, USB/PS2 keyboard input, and full-color VGA Mode-X output. 

[GitHub Link](https://github.com/marchuang6272/ORCA-OS/tree/main)

<br>

<div class="grid">
        <img src="./images/robot.gif" alt="Left Image" class="left-image"/>
        <img src="./images/diagram.png" alt="Top Right Image" class="bottom-left-image"/>
        <img src="./images/labeler.png" alt="Bottom Right Image" class="bottom-right-image"/>
</div>

<br>
<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">Intelligent Motion Laboratory: Image Segmentation Labeler</p>
  <p style="text-align: right;">Spring 2022</p>
</div>


As an undergraduate research assistant at the Intelligent Motion Laboratory, I contributed to the development of computer vision modules for a teleoperated robot, which achieved 4th place in the XPRIZE Global Avatar Competition. I also engineered a browser-based data labeling tool using React and Flask to facilitate computer vision research, focusing on few-shot, incremental, and continuous learning for robotic systems. Additionally, I deployed various PyTorch models using Flask to expose a REST API for model inference and implemented publisher/subscriber communication using ROS and C++ to connect single-board computers with a linear hydraulic actuator system.

[Video Link](https://www.youtube.com/watch?v=dt3At7YwxKM)

[Github Link](https://github.com/RogerQi/XMem)

<br>

<div style="text-align:center;">
    <img src="{{ "images/he_project.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" width="900"/>
</div>

<br>
<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">Class Project: Homomorphic Encryption Hardware Accelerator</p>
</div>

[Github Link](https://github.com/marchuang6272/HE_project/tree/main)

<br>

<div style="text-align:center;">
    <img src="{{ "images/presentation.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" width="900"/>
</div>

<br>
<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">SIGARCH presentation on High Performance Computing</p>
</div>

[Video Link](https://youtu.be/4Nr2-94_ksU)





