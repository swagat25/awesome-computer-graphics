# Awesome Computer Graphics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="./media/rtow.jpg" align="center" width="1000">](https://github.com/petershirley/raytracinginoneweekend)

The Awesome CG List! A collection of various resources to learn computer graphics, including books, tutorials, online courses, and more. Name a CG topic, chances are this list contains some stuff about it (if not, it will someday!).

**If you want to contribute, please read the [Contribution Guidelines](contributing.md)**


## Contents

* **[What is computer graphics?](#what-is-computer-graphics)**
* **[How to get started?](#how-to-get-started)**
* **[I want to learn more advanced stuff](#i-want-to-learn-more-advanced-stuff)**
* **[Books](#books)** 
* **[Libraries](#libraries)**
* **[Courses](#courses)**
* **[Sites](#sites)**

### What is computer graphics?
Computer graphics is a knowledge area about how to create images using computers, to put it simply. Generally this is done by processing data representing information what you want to draw, for example: objects, colors, light. Anything about visual and digital creations have used CG in some way: games, movies, etc.

### How to get started?
Before showing a lot of books, videos, and materials, first you need to know what is bare-minimum to begin with computer graphics. It boils down to two main topics: programming and math. About programming, learn the basics, it's recommended 
to learn C/C++ as they are used frequently in this area. Concerning math, learn linear algebra and geometry, there are books in this list focused on math fundamentals for CG, pick one and work on it.

### I want to learn more advanced stuff
Assuming you know programming and math, then you can get more practical. It's a good approach to get a project about a topic 
like global illumination, or GPU programming to deepen your knowledge on this area. Examples of projects are: path tracers, 
photon mapping, shader programming. Recommended projects are the PBRT, the ray tracer from the [Physically Based Rendering](http://www.pbr-book.org/3ed-2018/contents.html) book, and the ray tracer with photon mapping, from the [Realistic Image Synthesis Using Photon Mapping](https://www.amazon.com/Realistic-Synthesis-Mapping-Revised-Paperback/dp/B011DC2J3O/ref=sr_1_1?s=books&ie=UTF8&qid=1540518657&sr=1-1&keywords=photon+mapping).


### Books
* [Real-Time Rendering](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003/ref=sr_1_1?s=books&ie=UTF8&qid=1540516813&sr=1-1&dpID=51iw1UWKNhL&preST=_SX218_BO1,204,203,200_QL40_&dpSrc=srch), by Tomas Akenine-Moller, one of the best on high performance graphical applications, very detailed explanations and contains many examples to illustrate its topics.

* [Ray Tracing in One Weekend](http://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf), by Peter Shirley, a free book to get you implementing a basic ray tracer in C++, the catch is: this one is very short (about 40 pages), you'll learn the mininum to create a ray tracer to generate amazing images in a very short ammount of time!

* [Ray Tracing: The Next Week](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20The%20Next%20Week.pdf), by Peter Shirley, builds on top of the first books's project, adding more effects, like textures and motion blur.

* [Ray Tracing: The Rest of Your Life](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20the%20Rest%20of%20Your%20Life.pdf), by Peter Shirley, last book of the series, exposes more mathematical themes necessary to build more complex and complete renderers.


* [Physically Based Rendering: From Theory to Implementation](http://www.pbr-book.org/3ed-2018/contents.html), by Matt Pharr, teaches how to create a ray tracer to render realistic images. A thorough explanation of the technique, with as much code the theory behind it, and has a free online version!

* [3D Math Primer for Graphics and Game Development](https://www.amazon.com/Math-Primer-Graphics-Game-Development/dp/1568817231/ref=sr_1_1?s=books&ie=UTF8&qid=1540517337&sr=1-1&keywords=3d+math+prime), by Fletcher Dunn, this book gives more focus to the math necessary for game development.

* [Fundamentals of Computer Graphics](https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/1482229390/ref=sr_1_1?ie=UTF8&qid=1541094572&sr=8-1&keywords=fundamentals+of+computer+graphics), by Steve Marschner, introduces graphics concepts. 

* [Ray Tracing from the Ground Up](http://www.raytracegroundup.com/), by Kevin Suffern, guides you through the task of implement a ray tracer, starting with a bare-bones project, and every chapter introduces a new conpect to add to the renderer.

* [Advanced Global Illumination](https://www.amazon.com/Advanced-Global-Illumination-Philip-Dutre/dp/1568813074/ref=sr_1_1?s=books&ie=UTF8&qid=1540517779&sr=1-1&keywords=advanced+global), by Philip Dutre, its focus are fundamentals to understand realistic image synthesis, such as light transport.

* [Realistic Image Synthesis Using Photon Mapping](https://www.amazon.com/Realistic-Synthesis-Mapping-Revised-Paperback/dp/B011DC2J3O/ref=sr_1_1?s=books&ie=UTF8&qid=1540518657&sr=1-1&keywords=photon+mapping), by Henrik Jensen, teaches math and algorithms to implement the photon mapping rendering process. It even has a complete C++ inplementation of the technique!

[//]: # ( * Computer Graphics: Principles and Practice, by James Foley.)

[//]: # (* Foundations of 3D Computer Graphics, by Steven Gortler.)

[//]: # (* Computer Graphics Through OpenGL: From Theory to Experiments, by Sumanta Guha.)

[//]: # (* Interactive Computer Graphics: A Top-Down Approach with WebGL, by Edward Angel.)

[//]: # (* OpenGL Programming Guide: The Official Guide to Learning OpenGL, by Dave Shreiner.)


### Libraries
* [OpenGL](https://www.opengl.org/), one of the most, if not the most popular graphics API.

### Courses
* [Computer Graphics - San Diego](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x-3), by Ravi Ramamoorthi, this course focus on learning the necessary math to program a offline ray tracer.

* [SIGGRAPH University](https://www.youtube.com/playlist?list=PLUPhVMQuDB_aWSKj7L_-3Ot_nxBze_YMy), playlist with popular courses from the annual SIGGRAPH Conference.

[//]: # (* [Computer Graphics & Imaging - Berkeley](https://cs184.eecs.berkeley.edu/, by Ren Ng (Spring 2018.)


### Sites
* [ScratchAPixel](https://www.scratchapixel.com/index.php?#_=_), teaches image redering from basic to advanced.
* [Learn OpenGL](https://learnopengl.com/), resource site, contains tutorials by topic, code examples and even has a pdf version of its contents.
* [OpenGL tutorial](http://www.opengl-tutorial.org/), tutorial for learning OpenGL 3.3 or higher.
* [Learn Vulkan](https://vulkan-tutorial.com/), teaches the modern API, created by the same team that created OpenGL.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luís Santos](https://github.com/lhns) has waived all copyright and related or neighboring rights to this work.

