---
layout: project
type: project
image: img/ics685_proj2_thumbnail.png
title: "3D Puzzle-based Game for CyberCANOE 3D Wall"
date: 2025
published: true
labels:
  - Games
  - XR
  - Unity
  - C#
summary: "An interactive, first-person puzzle game where you play as the Big Bad Wolf trying to blow down the three pigs' houses."
---

<div class="text-center p-4">
  <img width="500px" src="../img/ics685_proj2_thumbnail.png">
</div>

<video src="https://github.com/user-attachments/assets/1c63ac21-8793-4114-b35f-6b3d8aea8067" width="1280" height="720" controls="controls"></video>

## Overview

A Unity-based puzzle game where you take the role of the Big Bad Wolf from The Three Little Pigs and attempt to use your breath to solve puzzles and enter the pigs' homes. For example, the pig with the brick house is protected by a drawbridge and a moat--to cross it, the player must blow the nearby torches to the drawbridge's suspension ropes to light them on fire, which will lower the drawbridge. The game utilizes Unity's built-in physics system to have the wolf "blow" air by applying a force to each targetable objects' Rigidbody. For more difficult interactions, like with the fire, an animation is used instead.

## Role and Responsibilities

Though technically a group project, I ended up programming the overwhelming majority of it. This included shader creation (particularly the skybox and water), event management, breath force logic using Unity's physics system, animation, visuals and postproessing, and the UI, among other things. Assets were found from the Unity Asset Store and Sketchfab, though I also edited a few to suit our needs.

## The Takeaways

I delved more into Unity's Shadergraph with this project, referencing tutorials to create the water and sky shaders. For the water, a Fresnel node was added to make the water more reflective when viewed from certain angles, and it supported UV distortion to mimic the refraction present in real-life water.
