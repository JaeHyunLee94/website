---
title: Material Point Method Framework
summary: C++ , CUDA , OpenGL based MPM framework
tags:
  - PBA
date: '2023-05-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Link
    url: https://github.com/LEE-JAE-HYUN179/mpm_solver
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

This is the simple CUDA, OpenMP, OpenGL based MPM(Material Point Method) Engine.

This Project is under developing.

## Build instruction
Make sure that your system has CUDA.
```
mkdir build
cd build
cmake ../
make
```
(or give -G option depending on your preference.)

## Features
- [x] [MLS-MPM](https://yzhu.io/publication/mpmmls2018siggraph/paper.pdf)
- [x] Mesh Importer
- [x] CUDA 
- [x] OpenMP
- [x] OpenGL Renderer
- [x] GUI Widget
- [ ] Mesh Exporter
- [ ] Cross platform
- [ ] Mesh Obstacle
- [ ] 2D Cloth, Hair

## Sample Scenes
These scenes are in the src/scene folder


## Dependencies
All the dependencies are in the external folder.
