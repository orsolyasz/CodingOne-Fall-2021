# Final Project Coding One Fall 2021


### "Fall 2021 FINAL Project by orsolya" on Mimic
https://mimicproject.com/code/692bdb58-3a88-9fe4-22a3-aea3548b1172

Video documentation: https://drive.google.com/drive/folders/1QHb8t1nwpbGjNig3Gi6-ZmihNCwNy0PB?usp=sharing


For my final project, I decided to create a surreal/magical 3D scene using Three.js, accompanied by a fitting soundscape. 

![3D scene with a tree on a globe on top of the ocean](https://github.com/orsolyasz/CodingOne-Fall-2021/blob/main/Week%2009-10%20Final%20Project/FinalProject.png)

My inspiration for this project was actually the drum machine I created as one of the earlier homework assignments. Interested in using natural sounds as digital samples, for this experiment I used short clips I cut out from recordings of ocean waves, rustling leaves, and birds chirping. These clips all served as “samples” in that they are all only a few seconds long and are being played back algorithmically. The resulting soundscape creates the feeling of a strangely digital-natural landscape, which is what inspired my design for the final project.

In the final project itself, I used the 3D model of a tree I built for another earlier homework exercise as the centerpiece of my design, and I created a large body of water to surround it - inspired by the wave sounds of the soundscape I wanted to use. To highlight the surreal, digitized nature of the landscape, I decided to place my tree on top of a transparent glass globe - to appear almost like an inverted snow globe. In technical terms, the tree is parented to the globe so as the globe floats, moving into and out of the water, the tree consistently sits atop.

When I set out to create a body of water in my scene, I looked around and found a great demo/example on the Three.js GitHub for a basic ocean scene. After figuring out how to actually work with this code (in Mimic) and what it required, I largely relied on this example to build my design, but shifted a lot of the design to match the mystical night scene I had in mind. I played around with different properties of the sky and ocean elements to create a vibrant sea in a dark, glowing night.

Using the point light example I explored for my previous Three.js homework exercise, I added in lights to float around the tree I decided to create them in  a uniform size and color to keep the design minimalistic, except for the light that is most directly influenced by the user’s cursor position - which is larger so as to be more clearly noticeable and allow more control of the lighting in the scene. The lights are set to orbit around the tree by default, but a lot of their orbits are somewhat affected by how the user’s mouse moves. The position of the main, largest light is determined directly by the cursor position -- but instead of placing the light exactly where the cursor is, the cursor movements push and pull the light based on the camera position, moving it around in a kind of dance.

Some improvements or further experiments I would love to explore with this basic scene are the addition of stars in the scene, or perhaps a slow sunset into a starry night that evolves over time. I have also found some people working on more advanced water effects - such as having water ripple when other bodies get submerged in it - which could be an interesting addition around the central tree/globe.
