---
title: "The GAMERA MHD code"
excerpt: "High resolving power numerical methods for MHD<br/><img src='./gamera.png'>"
collection: portfolio
---

## The GAMERA MHD code

Yes Gamera is a giant Japanese turtle, for us it's just a piece of elegant code that solves the equations of magnetohydrodynamics (MHD) in non-orthogonal, curvilinear grids. Gamera stands for "Grid Agnostic MHD for Extended Research Applications" Here's the "official" design of the Gamera logo by artist at the Johns Hopkins University (JHU/APL).

<img src='./gamera.png'>

Gamera is a new magnetohydrodynamic (MHD) code for simulation of diverse magnetized plasma environments. It is a full rewrite of the high-heritage Lyon-Fedder-Mobarry (LFM) model. Gamera is a flexible, portable, user-friendly and exascale-capable code designed to take advantage of supercomputer architectures of the future.

## A brief history of the LFM code

* Do you know what's the order of spatial differencing used in the first LFM paper published in Phys. Rev. Lett. in 1982?
  * It's twentieth-order. Yes it sounds crazy but it did get the job done: with 40x50 computational cells, Professor John Lyon and colleagues were able to resolve the structure of the Earth's magnetosphere including the bow shock, the magnetopause and the magnetotail, even created a numerical substorm. This is called "state-of-art". Here is a not-so-complete list of the development of the LFM code in the past three decades:
