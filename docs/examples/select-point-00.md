---
layout: default
title: Camera Animation
parent: Examples
---

# Select Point 00
***tox: container_selectPoint_00***  

[Load Example](?remoteTox=https://github.com/raganmd/touchdesigner-community-examples-code/raw/main/tox/container_selectPoint_00.tox){: .btn .btn-green} [Open Network](?openNetwork=True){: .btn .btn-blue}


This component allows you to select the closest point to your mouse on Geometry without needing a render pick. It uses a a python script in this network called selectPoint.

It loops through each point in the mesh and as it finds the closest point it sets it, however if the next point is not as close then it ignores that id.

---
#### Created 09.26.16
*Richard Burns*