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

        .justified {
        text-align: justify;
        }
        
        /* Indent text */
        .indented {
        text-indent: 20px; /* You can adjust the value as needed */
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
            <p class="justified indented"> 
                Hello! My name is Marcanthony Huang. I am a recent graduate from University of Illinois Urbana-Champaign’s Grainger College of Engineering. Within software engineering, my skills and interests revolve around computer hardware, systems programming, and machine learning. Outside of industry, I am passionate about computer engineering research, specifically in computer architecture and robotics. Currently, I work as a software engineer and researcher at the Future Architecture and System Technology for Scalable Computing Laboratory. 
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
  <p style="text-align: center; font-size: 24px;">Current Work: Machine Learning for Computer Architecture</p>
  <p style="text-align: right;">Fall 2023</p>
</div>

<p class="justified indented"> 
    As a software engineer and research assistant at the Future Architecture and System Technology for Scalable Computing Laboratory, I collaborate with Google DeepMind researchers on machine learning-assisted computer architecture projects. We developed an open-source framework for generating processor microarchitectures at the RTL level, featuring a graph-based model with nodes for hardware modules and edges for interfaces. This model enables rapid evaluation of design points using graph neural networks (GNNs) or HDL generation for synthesis and simulation, exploring both hardware parameters and graph structures. I contributed by developing a design space exploration framework using Python and PyTorch and modifying HDL compilers in C++ to integrate custom RISC-V vector processor architectures, enhancing computer architectures for efficient performance estimations and HDL generation.
</p>

<br>



<div style="text-align:center;">
    <img src="{{ "images/orca.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" />
</div>

<br>

<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">ORCA-OS: A Functional Unix-based OS Kernel</p>
  <p style="text-align: right;">Spring 2023</p>
</div>
<p class="justified indented"> 
    I worked on a semester-long project to design and implement a functional Unix-based operating system kernel written in C and x86 assembly. Features of the kernel include paged virtual memory management, interrupt handling, and process scheduling. In addition, ORCA-OS includes an in-memory file system, user/kernel privileges, multiple terminals, a virtualized clock, preemptive scheduling, USB/PS2 keyboard input, and full-color VGA Mode-X output. 
</p>
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

<p class="justified indented"> 
    I initially came to university with an interest in robotics, and it was working in a robotics lab that sparked my interests in system software and computer architecture. As an undergraduate research assistant at the Intelligent Motion Laboratory, I contributed to enhancing the computer vision system by creating a real-time image segmentation labeler that connected to the robot's camera feed and backend computer vision models. This tool allowed a robot operator to improve image segmentation models in real time during a robot's operation. 
</p>
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
<p class="justified indented"> 
    My group developed a hardware accelerator in SystemVerilog to enhance the performance of the BFV homomorphic encryption scheme, focusing on accelerating the computation bottleneck: polynomial multiplication. By parallelizing this process, our accelerator significantly speeds up computations. Key primitives for encryption and decryption are stored in hardware registers to support efficient operations. Homomorphic encryption is significant because it allows secure computations on encrypted data without the need to decrypt it, protecting data privacy in untrusted environments.
</p>
[Github Link](https://github.com/marchuang6272/HE_project/tree/main)

<br>

<div style="text-align:center;">
    <img src="{{ "images/presentation.gif" | prepend: site.baseurl | prepend: site.url}}" alt="orca" width="900"/>
</div>

<br>
<div style="display: flex; justify-content: space-between;">
  <p style="text-align: center; font-size: 24px;">ACM SIGARCH Presentation: High Performance Computing</p>
</div>
[Video Link](https://youtu.be/4Nr2-94_ksU)





