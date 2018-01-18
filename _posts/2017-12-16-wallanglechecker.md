---
layout: post
title:  "Wall Angle Checker"
date:   2017-12-16
excerpt: "Revit API Development"
project: true
tag:
- revitapi
- c#
- revit
- high-rise
- residential
- new york city
- architecture
- bim implementation
- troubleshooting
comments: false
feature: "/projects/20171216_wallanglechecker/wallanglechecker.png"
---

# Wall Angle Checker
<figure>
<a href="/projects/20171216_wallanglechecker/wallanglechecker.png"><img src="/projects/20171216_wallanglechecker/wallanglechecker.png"></a>
<figurecaption><i>Screen grab of the Dockable Pane Inteface( Click to enlarge! )</i></figurecaption>
</figure>
Wall Angle Checker is an application built for identifying walls and lines that do not confirm to standard project angles.

## Description
The Wall Angle Checker was comissioned by a firm for a very large project with several walls with non-standard angles.
The tool is designed to identify elements for review and correction on a view-by-view basis.

## Features
* Text file to store approved angles for walls in a project
* Fast detection of off-angle walls because the app works only on the current view
* Ability to choose highlight colors
* Tolerances can be varied according to the needs of the project
* Prevents occurrence of Off-Axis Warnings in the project
* Can be extended to detect off-angle model lines and room separation lines
