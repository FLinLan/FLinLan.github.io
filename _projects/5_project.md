---
layout: page
title: FPGA Taiko No Tatsujin Rhythm Game
description: FPGA-based rhythm game with synchronized VGA display and state machine logic
img: assets/img/fpga_taiko.png
importance: 5
category: work
github: https://github.com/FLinLan/FPGA-Taiko-No-Tatsujin
---

**[View on GitHub](https://github.com/FLinLan/FPGA-Taiko-No-Tatsujin)**

## Project Overview

Developed an FPGA-based rhythm game on the DE1-SoC platform, rendering scrolling musical notes from ROM-preloaded frames synchronized to song rhythm via VGA display. Implemented sophisticated algorithmic state machine, key synchronization with edge detection, and combinatorial collision detection for scoring on 7-segment displays.

## Technical Specifications

- **Platform:** DE1-SoC FPGA board
- **Display:** VGA output with scrolling note rendering
- **Audio Sync:** ROM-preloaded frames synchronized to song rhythm
- **Display Output:** 7-segment displays for scoring
- **HDL:** SystemVerilog/Verilog

## Key Features

- **State Machine:** Algorithmic state management for gameplay flow and note tracking
- **Key Synchronization:** Edge detection for precise timing of player inputs
- **Collision Detection:** Combinatorial logic for scoring based on hit accuracy
- **Graphics Rendering:** ROM-based note frame preloading and VGA scrolling implementation
- **Score Display:** Real-time score output on 7-segment display arrays

## Accomplishments

- Developed FPGA-based rhythm game on DE1-SoC with real-time VGA rendering
- Implemented ROM-preloaded frame scrolling synchronized to song rhythm for smooth gameplay
- Designed sophisticated state machine for comprehensive gameplay state management
- Created edge detection logic for precise key input synchronization with note timing
- Implemented combinatorial collision detection algorithm for dynamic scoring based on hit accuracy
- Successfully integrated multiple hardware components: VGA controller, ROM memory, and 7-segment display drivers
<div class="col-sm mt-3 mt-md-0">
{% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
<div class="col-sm mt-3 mt-md-0">
{% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
<div class="col-sm mt-3 mt-md-0">
{% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
