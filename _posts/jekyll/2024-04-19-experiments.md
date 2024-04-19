---
title: Experiments
author: dan
layout: post
date: 2024-04-19 02:09 PM
categories:
  - Jekyll
tags: 
mermaid: true
---
```mermaid
 gantt
  title  Adding GANTT diagram functionality to mermaid
  Fiverr :a, 2024-01-11, 3w
  YouTube :crit, b, 2024-02-02, 2w
  cherry :active, c, after b a, 3d
```
```mermaid
graph TD;
    A-->B;
    A-->C;
    A-->R;
    A-->V;
    A-->N;
    B-->D;
    C-->D;
    C-->X;
    D-->Q;
    X-->Q;
    N-->Q;
    V-->X;
```