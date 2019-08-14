+++
title =  "Radiance - Graphics Engine"
date = 2019-08-05T21:16:07+02:00
draft = false
description = "Radiance Engine is a graphics engine, build with intent to support multiple graphics API. In it current state, it only supports OpenGL. This is only a work in progress of the project."
tags = ["rendering", "graphics", "hardware-rendering", "c/c++", "graphics api", "opengl", "d3d11", "game engine"]
image = "graphicsengine_thumb.png"
+++
Radiance Engine is a graphics engine built currently on top of OpenGL but with the intent to eventually support more APIs.
This project is still in development, more features are about to come!

Initially this project was mostly intended as a practical exercise to reinforce the things I've learned on LearnOpenGL. 
The goal has evolved into an API agnostic renderer with a clear software architecture. 
Next up is providing a simple but nice API to the user. An API that allows the user to build their graphics application quickly, 
while the engine handles all the other low-level necessities.

<style>
ul
{
	columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
}

#container 
{
    column-count: 2;
    -moz-column-count: 2;
    -webkit-column-count: 2;
    width: 100%;
}

.item, .dummy {
    display: inline-block;
    width: 100%;
	padding-left: 15px;
}
#container:after
{
    column-count: 1;
    -moz-column-count: 1;
    -webkit-column-count: 1;
    width: 100%;
	display: inline;
}
</style>

<br/>
<ul style="list-style-type:none;">
<li>Graphics Features</li>
<li>General Engine Features</li>
</ul>

<div id="container">
    <div class="item"><li>Material System</li></div>
    <div class="item"><li>Support Custom Shaders</li></div>
	<div class="dummy"></div>
	<div class="dummy"></div>
	<div class="dummy"></div>
	<div class="dummy"></div>
    <div class="item"><li>Multiple Loggers</li></div>
    <div class="item"><li>Component System</li></div>
    <div class="item"><li>Event System</li></div>
    <div class="item"><li>Window Handling</li></div>
    <div class="item"><li>User Interface Layer</li></div>

</div>



If you're interested to know more, you can the find source code on this github <a href="https://github.com/Nickelium/Radiance">[link]</a>.

Render Samples
<img src="/img/rasterizer/16.png" width="100%">	 

