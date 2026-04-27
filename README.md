# CS-330
This is my journey into the wild world of 3-D graphics rendering using OpenGL and C++.

## I was given these questions for my reflection for the last week of this course.

1. How do I approach designing software?
- - What new design skills has your work on the project helped you to craft?
- - What design process did you follow for your project work?
- - How could tactics from your design approach be applied in future work?
2. How do I approach developing programs?
- - What new development strategies did you use while working on your 3D scene?
- - How did iteration factor into your development?
- - How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?
3. How can computer science help me in reaching my goals?
- - How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?
- -  How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?


## Here are my answers to those questions.

When I approach designing software, I focus on breaking down a visual idea into basic geometric shapes using OpenGL and Visual Studio. For my 3D farm scene, I needed to figure out how to build normal objects like a workbench out of simple meshes. I built the legs, frame, pegboard, and top of the bench by putting several boxes together. Then I used a half sphere mesh to act as a metal bowl sitting on top. I had to be flexible with my design process. I originally wanted to use a plane for the barn backdrop, but I could not get the scaling and positioning right, so I used a box instead. The original plane became the grass for the farmland. To get everything looking right, I practiced a specific design process where I aligned the edges of each object to figure out exactly where the next one should start and end. After that, I applied scaling parameters to each object to get the exact dimensions and shapes I wanted. These spatial design tactics will be incredibly helpful in my future work because they teach me how to arrange and scale different components within a larger environment.

My strategy for developing programs relies heavily on analyzing existing code and reusing it to build new features. To implement camera navigation, I looked at predefined functions to figure out what I needed to write. I copied and reengineered an existing function four times so I could use the Q, E, O, and P keys to move the camera up and down and switch between display modes. I used a similar strategy for the mouse controls. By comparing the existing mouse functions for moving the camera side to side, I was able to write a new callback that recognized mouse wheel actions to control the camera speed. Iteration was also a massive part of my development, mostly because of unexpected roadblocks. The lighting portion of the project completely derailed me. I spent twelve days stressing over whether my lighting was correct, and I got so distracted that I forgot to build the vise for the workbench. I waited for feedback that came at the very last minute, which forced me to rethink my plan and consider building an outside canister light instead of the vise to meet the deadline. Over the course of the milestones, my approach to writing code evolved to focus heavily on modularization. I used a preparation scene function in the scene manager class to assign a single mesh for each shape into a container called m_basicMeshes. This evolution allowed me to continuously redraw the meshes, which made computations much faster, used fewer resources, and kept my code much cleaner.

Working through these computational graphics challenges has given me skills that directly apply to my future goals. Educationally, learning how to manipulate meshes, handle key presses, and set up scene managers gives me a strong foundation in writing efficient and reusable code. The struggle I went through with the lighting, where I felt confused by different YouTube videos and lacked direction, taught me how to push through difficult concepts even when the resources are overwhelming. Professionally, the modular strategies I learned are exactly what I need to build software at scale. By learning how to assign assets to containers to reduce the number of load calls, I now know how to optimize performance and save computing resources. Even though the stress of waiting for feedback was a terrible experience, receiving confirmation that I had done the work correctly showed me that I can successfully develop complex 3D visualizations. These are the exact problem solving and optimization skills I will need in my career as a software developer.
