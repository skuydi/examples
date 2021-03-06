# Praxis LIVE example projects

This repository contains some example projects which should give you a basic introduction to Praxis LIVE - if reading on GitHub, use the `Download ZIP` link to the right.

These projects can be opened in the Projects tab in Praxis LIVE.  Once the project is open, right click on the project and select `Run` to run it, or use the play button in the toolbar. The easiest way to stop everything is to restart the hub (red circular arrow).

NB. Closing a window will not remove the project components from the Praxis LIVE hub - you can see the various root components within the Hub Manager tab at the bottom left.  Make sure to use the `Restart Hub` action between running each example. This will be the most likely reason a project will appear not to run (it is possible to run multiple projects at once, as long as they don't try to create components with the same address, but it's better to ignore this for now!). You can double-click on individual root components within the Hub Manager to stop and restart them.

With all of these projects, you can open the .pxr files into the graphical editor and play around with them as they run.  Highlight or double-click a component to change its properties.  Drag components from the palette to add them to the graph, drag to connect ports together, or right-click and select `delete` to remove any highlighted components or connections.  Hover over the top tab of a component to find out its type (as shown in the palette), or connections to find out where they go.  Ctrl-mousewheel to zoom in and out, or navigate using the satellite view at the bottom right.

Many components you can access and alter their code on-the-fly. Right-click on the top tab of the component and click `Edit code`.

## Examples

#### Hello World PL2

Say hello to Praxis LIVE version 2! Showcasing some new features including revised shader (GLSL) and Processing 3D support.

### Basics /

#### hello world

A simple patch which runs white noise through a mask image to spell out "Hello World" (well, there had to be one! :-) ).  Open up video.pxr to see the graph.

#### slideshow

A simple slideshow demonstrating how to use `core:array:iterator` to cycle through a folder of images, and `video:snapshot` to fade between images.

#### audio gui

Demostrating Praxis LIVE's audio playback and custom GUI control panels.  Try triggering sounds with the buttons, altering the filter on the drumbeat with the XY pad, and controlling gain and distortion with the sliders.

Open audio.pxr to play with the audio graph, or gui.pxr to edit the control panel.  Notice how the GUI editor hijacks the control panel from its separate window.  Switch on the `edit` overlay to modify the GUI.

#### video input

**Requires webcam**

Simple webcam input with a couple of animated "negative" bars.

#### video player

Video playback on to a number of 3D transformed surfaces.

**No video file included!** Select one of your own using the GUI.

### Video

#### Kaleidoscope

**Requires webcam**

Simple GLSL video filter with animated shader values.

#### Smoky 3D

"Smoky" shader effect textured on to a 3D shape using `video:gl:p3d` to access the Processing renderer.

Shape ported from http://processing.org/examples/texturecylinder.html

### Audio

#### audio seq

Praxis LIVE is not really aimed at sequencing music, but this project provides a simple drum machine and bass line with changing FX, as well as a visualization of the sound.

#### blob theremin

**Requires webcam**

A simple blob tracking example controlling a sine wave. Give the camera 10s to adjust to the background before you start moving!

### TinkerForge

Praxis LIVE interfaces with TinkerForge (sensors, servos, LCD screens and more) - http://www.tinkerforge.com

#### hello world

Simple interfacing with LCD screen. Requires LCD20x4 bricklet and (optional) rotary poti bricklet.

#### hello world adv

Control audio and text using the buttons on the LCD module. Requires LCD20x4 bricklet.

#### io16

Simple flashing LED example. Requires IO16 bricklet hooked up to an LED!

#### tf custom code

Using `core:custom` module to translate audio levels for the LCD display. Requires LCD20x4 bricklet.

### Misc

#### Magoria

Simplified reworking of _Magoria_ - a generative portrait of the people of Oxfordshire.

#### RAM

Live loop sampler used in performances of _Radio Access Memory_ (predates Praxis LIVE). https://youtu.be/sMx6E6PoC4o

 

