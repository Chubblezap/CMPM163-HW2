# CMPM163-HW2
Homework 2 for CMPM163.

Contains two scenes. Flip between them with right and left arrow keys.

Scene 1: Outline + Bloom shaders
Not much to say here other than it looks neat. I used a two-pass hull shader instead of viewport normals.

Scene 2: Heightmap + Skybox reflection
Press R to reroll the mountain configuration.
WASD controls the water; A and D control the flow speed, and W and S control the wave intensity.

Mountain generation uses the last-rolled height value in addition to the average height value of the last vertex row in a somewhat-poor attempt to make more 'natural' hills instead of being spiky and random.
