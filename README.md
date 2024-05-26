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
        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            grid-template-rows: 1fr 1fr;
            gap: 10px; /* Adjust the gap as needed */
            max-width: 800px; /* Adjust the max-width as needed */
        }

        .left-image {
            grid-row: 1 / 3; /* Spans from row 1 to row 3 (2 rows) */
            grid-column: 1 / 2; /* Stays in the first column */
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensure the image covers the entire grid area */
        }

        .top-right-image {
            grid-row: 1 / 2; /* Occupies the first row */
            grid-column: 2 / 3; /* Occupies the second column */
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensure the image covers the grid area */
        }

        .bottom-right-image {
            grid-row: 2 / 3; /* Occupies the second row */
            grid-column: 2 / 3; /* Occupies the second column */
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensure the image covers the grid area */
        }
    </style>
</head>

<body>
    <div class="container">
        <img class="image" src="./images/headshot.jpg" alt="headshot" style="width: 220px;">
        <div>
            <p> 
                Hello! My name is Marcanthony Huang. I am a recent graduate from the University of Illinois Urbana-Champaign. My professional journey and academic experiences have fueled my passion for computer hardware design and system programming. I have had the privilege of collaborating with Google DeepMind researchers on cutting-edge machine learning assisted computer architecture projects and have engineered large-scale microarchitecture design space exploration frameworks. My work spans from modifying HDL compilers for custom RISC-V vector processors to assisting in the development of a Unix-based operating system kernel in C and x86 assembly. 
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

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">Research Project: ML-Driven Hardware Design Space Exploration</p>
  <p style="text-align: right;">Fall 2023</p>
</div>

As a Software Engineer and Research Assistant at the Future Architecture and System Technology for Scalable Computing Laboratory, I collaborated with Google DeepMind researchers on machine learning-assisted computer architecture projects. I engineered a large-scale microarchitecture design space exploration framework using Python and PyTorch, incorporating open-source RTL synthesis tools, reinforcement learning frameworks, and architecture simulators. Additionally, I modified open-source HDL compilers in C++ to create custom SystemVerilog intermediate representations, enabling the integration of custom RISC-V vector processor architectures into machine learning frameworks.





<div style="text-align:center;">
    <img src="{{ "images/orca.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" />
</div>


<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">ORCA-OS: A functional Unix-based OS kernel</p>
  <p style="text-align: right;">Spring 2023</p>
</div>

I embarked on a semester-long project to design and implement the ORCA Operating System, a functional Unix-based operating system kernel written in C and x86 assembly. This project involved creating a kernel capable of paged virtual memory management, interrupt handling, and process scheduling. Key features of ORCA OS include an in-memory file system, user/kernel privileges, multiple terminals, a virtualized clock, preemptive scheduling, USB/PS2 keyboard input, and full-color VGA Mode-X output. 
[GitHub Link](https://github.com/marchuang6272/ORCA-OS/tree/main)


<div class="grid">
        <img src="{{ "images/robot.gif" | prepend: site.baseurl | prepend: site.url}}" alt="Left Image" class="left-image"/>
        <img src="{{ "images/labeler.png" | prepend: site.baseurl | prepend: site.url}}" alt="Top Right Image" class="top-right-image"/>
        <img src="{{ "images/diagram.png" | prepend: site.baseurl | prepend: site.url}}" alt="Bottom Right Image" class="bottom-right-image"/>
</div>

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">Intelligent Motion Laboratory: Image Segmentation Labeler</p>
  <p style="text-align: right;">Spring 2022</p>
</div>


As an undergraduate research assistant at the Intelligent Motion Laboratory, I contributed to the development of computer vision modules for a teleoperated robot, which achieved 4th place in the XPRIZE Global Avatar Competition. I also engineered a browser-based data labeling tool using React and Flask to facilitate computer vision research, focusing on few-shot, incremental, and continuous learning for robotic systems. Additionally, I deployed various PyTorch models using Flask to expose a REST API for model inference and implemented publisher/subscriber communication using ROS and C++ to connect single-board computers with a linear hydraulic actuator system.
[Video Link](https://www.youtube.com/watch?v=dt3At7YwxKM)
[Github Link](https://github.com/RogerQi/XMem)


