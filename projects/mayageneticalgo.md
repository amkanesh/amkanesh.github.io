---
layout: project
type: project
image: ../img/milestone4_c.jpg
title: "3D Puzzle-based Game for CyberCANOE 3D Wall"
date: 2025
published: true
labels:
  - Genetic Algorithms
  - Autodesk Maya
  - Python
summary: "A Python application for Autodesk Maya to create generations of customizable, pseudo-randomized shaders using genetic programming."
---
<video src="https://github.com/user-attachments/assets/278f351b-6f63-4bac-a6d6-01280d54bf9b" width="1280" height="720" controls="controls"></video>

## Overview

A Python program that genetic programming to create an interactive system to make procedural shaders in Autodesk Maya. Genetic programming concerns a type of algorithm that mimics biological evolution, including concepts like genetic crossovers and mutations. Instead of genes, the things being modified are shader attributes: things like base color, specular values, textures, and displacement. 
<img width="954" height="748" alt="hypershade_tree" src="https://github.com/user-attachments/assets/f2ef70ea-92da-40c0-9bc4-d8801856f756" />
<img width="1127" height="176" alt="genetic_tree" src="https://github.com/user-attachments/assets/ede21bbf-bc7d-40ff-929d-58a65d1c639f" />
The first step was to convert the different nodes of a Maya material into a tree structure, which I could then apply mutations to (i.e. adding, mixing, replacing, or removing nodes). 

The system uses custom-made classes and performs all genetic combinations in the code, then re-converts the new properties to new Maya materials and applies them to objects in the scene. The first pass generates 5 completely random shaders applies to 5 spheres, but the real heart of program lies when you start selecting for shaders to keep, thus acting as the program's equivalent of a "best-fit" function. Up to 5 shaders can be generated at a time, and each of them will take on characteristics of their "parents"--for example, if you delete 3 of the 5 spheres in the scene and run the program once more, 3 new shaders with mixed attributes from the remaining 2 shaders will be created. The video goes into more detail as to how that works.

## Role and Responsibilities

This was a solo project. With some guidance from the professor, I was free to develop the system however I wanted.

## The Takeaways

I was introduced to the concept of genetic algorithms through this project, which is something I've never even heard of before taking this course. Additionally, I got to better know the Maya Scripting API to create custom programs and plugins.
