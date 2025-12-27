---
layout: project
type: project
image: img/ics481_thumbnail.png
title: "Custom OpenGL 3D Rendering Software in Lisp"
date: 2025
published: true
labels:
  - OpenGL
  - Lisp
  - Graphics Programming
summary: "A 3D rendering software supporting lights and shading using OpenGL, written in Lisp."
---

<video src="https://github.com/user-attachments/assets/b623ce66-2e53-4f2b-8161-f1ede34a6586" width="1280" height="720" controls="controls"></video>

## Overview
A rendering software written with Lisp in Emacs that supports 2D and 3D drawing of shapes. You can toggle between smooth shading and faceted shading in real time, and lights are also supported. 3D objects are constructed by drawing a list of polygons, similar to how modern rendering software create polyhedrons under the hood. However, polygons are not simplified to quads or tris in this program, and faces can be a polygon of any number of vertices.

## Role and Responsibilities

A solo project, under the supervision of an instructor. The project was created over the course of a semester, and each homework built upon the last and added new features to the software.

## The Takeaways

I learned about the backend of modern day modeling/rendering software like Blender and Maya by implementing it myself--mainly, how 3D shapes are constructed from polygons, as well as the importance of normals and keeping them pointing in the right direction. It was also my introduction to using OpenGL and Lisp.
