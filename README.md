
# xtan6626_9103_tut2_quiz8
Here is a repository for quiz 8 of IDEA9103

# Quiz 8

## Part 1
![the first image about installation](readmeImages\installation_1.png)
![the second image about installation](readmeImages\installation_2.png)
"Helix (2020)" (an AudioVisual Installation Directed by KnovCompile)

### A Source of Inspiration

I am attracted by the dynamic interaction of light and shadow, which **creates a visual flow and change**. When the ribbon of light takes on a wavy shape, this change of light and shadow reminds me of the softness and fluidity of fabric, and the effect when it flutters or falls to the ground is a reminder of satin.

### How the Plan is Incorporated into the Project?

The **smooth dynamic changes with form** are what I need.Before creating code, I need to **know what kind of dynamic changes I needed** (e.g. rhythm, amplitude).

## Part2

I will use **Perlin Noise** to simulate fluid dynamics which from part 1.

### Example

![example of Perlin Noise](readmeImages\example_of_perlinNoise.png)

[https://editor.p5js.org/arthurrc/sketches/Bya9WiAnm0]

### Steps

1. Global Variables
2. "setup()": Create the initial canvas and particle array and set the initial properties of the particles.
3. In the draw() function, first create a flow field using nested loops, then update each particle's movement direction and position according to the vectors in this flow field using "follow(flowField)".

### Reflection

Part 1 explores the dynamic interplay in a 3D AudioVisual Installation. However, the code which I found shifts to a 2D plane. Still need the deeper develop how Perlin Noise's running track be more three-dimensional



