+++
title =  "IRadiance - RayTracer"
date = 2019-08-12T21:16:07+02:00
draft = false
description = "IRadiance Engine is a software Raytracer that can render a varierty of scenes. The software also allows to visualize the progress of an image being raytraced and not only the final result. This is only a work in progress of the project."
tags = ["rendering", "graphics", "raytracer", "software-rendering", "c/c++"]
image = "raytracer/raytracer_thumbnail.jpg"
+++

IRadiance Engine is an open-source software raytraced renderer written in C++11.
This project is still <b>in development</b>, more features are about to come!

Previously I've written a raytracer based on the implementation of 
<a href="https://github.com/RayTracing/InOneWeekend">Ray Tracing in One Weekend, from Peter Shirley</a> and 
Paul Heckbert's business card raytracer. 
What I did back then was writing the output to a simple image format, .PPM, which requires a specialized software to view the image.
I used Photoshop for the above because I already had it available on my computer. 
This is a simple approach but I found it very inconvenient to open Photoshop everytime, 
especially with the long loading times on my computer. Alternatively, I could download some other lightweight software that supports PPM. 
But I decided to utilize a graphics API, OpenGL in this case, to send the imagebuffer to the GPU for an immediate feedback.
This approach enables us to get intermediate render results by sending the partial imagebuffer every 16ms.
This might look like a small feature difference but seeing the the image being raytraced is really satisfying.

Definetely worth the time and effort!


<br/>
Features

<li>Simple Raytracer</li>
<li>Visualize Render Progress</li>
<li>Save Render to File</li>

<br/>


If you're interested to know more, you can the find source code on this github <a href="https://github.com/Nickelium/IRadiance">[link]</a>.

<br/>
<img src="/img/raytracer/raytracer_thumbnail.jpg" width="100%">	 

