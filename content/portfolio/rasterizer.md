+++
title = "Rasterizer"
date = 2019-07-12T12:32:46+02:00
draft = false
description = "A realtime software Rasterizer that emulates typical hardware graphics pipeline. It contains the following graphics features but it is not exhaustive: backface culling, depth buffer, perspective correct interpolation, extendable vertex and fragment shaders and of course Rasterization"
tags = ["rendering", "graphics", "software-rendering", "c/c++"]
image = "rasterizer/rasterizer_thumbnail.png"
+++

<div style="position:relative;padding-top:56.25%;">
<iframe width="100%"  frameborder="0" allowfullscreen
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
src="https://www.youtube.com/embed/7sPPdtgjI90">
</iframe>	
</div>

<br/>
This is a simple realtime software renderer that emulates the typical graphics pipeline.
Therefore, it doesn't use the help of any Graphics API such as D3D11/12, OpenGL or Vulkan.
The software is built mostly from 'scratch', written in standard C++98/C++11.
To be more precise, the renderer tries to mimic the OpenGL pipeline by providing its implementation instead of relying on the GPU.

The goal of this project is to learn and uncover what's behind the blackbox of a Graphics API that is often untold (to me at least) 
and taken as it is. Also to learn how one might write a renderer back in the day. Although, raycasting or so was probably more appropriate than this renderer. 
Initially, I planned to implement only a few trivial graphics features, but it somehow grew more than expected.
<style>
ul
{
	columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
}
</style>

<br/>
<ul style="list-style-type:none;">
<li>Features:</li>
<li>Back End Features:</li>
</ul>

<ul>
<li>Wireframe Rendering</li>
<li>Flat Shading</li>
<li>Gouraud Shading</li>
<li>Phong Shading</li>
<li>Diffuse Texture Mapping</li>
<li>Scene Switching</li>
<li>Rendermode Switching</li>
<li>OBJ file Parser</li>
<li>JSON file Scene Description</li>

<li>Backface Culling</li>
<li>Depth Buffering</li>
<li>Perspective Correct Interpolation</li>
<li>Extendable Vertex and Fragment Shaders</li>
<li>Linear Algebra Library</li>
<li>Rasterizer</li>
<li>Line Rendering</li>
</ul>

<br/>
I'm actually glad I finish this project because it allowed me to gain a deeper and richer understanding of hardware rendering 
and as result made me appreciate it more.


If you're interested to know more, you can the find source code on this github <a href="https://github.com/Nickelium/Rasterizer">[link]</a>.
     
<br/>
Render Samples

<img src="/img/rasterizer/16.png" width="100%">	 

<img src="/img/rasterizer/28.png" width="100%">	 

<img src="/img/rasterizer/23.png" width="100%">	 

<img src="/img/rasterizer/21.png" width="100%">	 




