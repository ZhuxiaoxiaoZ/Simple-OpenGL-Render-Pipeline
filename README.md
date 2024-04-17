# Simple-OpenGL-Render-Pipeline

## Introduction
The objective of this project is to construct a simple rendering pipeline from scratch using OpenGL(Open Graphics Library) and C++, capable of accurately rendering and displaying a model on screen. The project was executed in three main phases: Transformation, Rasterization, and Shading. Initially, I utilized freely available models (typically in .obj format) as input and positioned the camera and model in the visual scene through computations involving model, viewport, and projection transformations. Subsequently, the rasterization process rendered the object on the screen by determining whether each pixel in the viewport resides within a triangle on the x-y plane and if its depth is the closest to the viewport. Finally, to enhance the visual impact of the model, I applied a simple shader to assign colors to each pixel for display. 

## Instruction
1.transfer the project to your local machine and launch it using Visual Studio 2022, though the 2019 version is also compatible. 
2. navigate through the menu: Tools -> NuGet Package Manager -> Manage NuGet Packages for Solution. 
3. In the Browse window, search for "nupengl" and install both of the packages that appear. 
4. After this setup, you should be able to compile and execute main.cpp. Upon running the project, you'll see a window where a cow model rotates over time.

## Output Result
https://youtube.com/shorts/uhbV_-Jzg1E?feature=share
