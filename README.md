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
    <div class="image-container">
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


