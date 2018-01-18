---
layout: post
title:  "Building Performance Analysis Using Modeling Tools"
date:   2018-01-15
excerpt: "A demonstration of model generated workflows for energy and environmental analysis"
project: true
tag:
- revit 
- energy
- lighting
- wind
- performance
- LEED
- BIM
comments: false
---

# Lighting Analysis
<figure class="third">
<a href="/projects/20180117_environmental_analysis/img/01_lighting.png"><img src="/projects/20180117_environmental_analysis/img/01_lighting.png"></a>
<a href="/projects/20180117_environmental_analysis/img/02_lighting.png"><img src="/projects/20180117_environmental_analysis/img/02_lighting.png"></a>
<a href="/projects/20180117_environmental_analysis/img/03_lighting.png"><img src="/projects/20180117_environmental_analysis/img/03_lighting.png"></a>
<figurecaption>Analysis Outputs from Autodesk Revit's Lighting Analysis Tool <i>( Click to enlarge! )</i></figurecaption>
</figure>
Using the built-in Lighting Analysis Tool within Autodesk Revit, lighting intensity levels are easily simulated for a given space. The calculations encapsulate daylight factors using Standard Sky conditions and gives a fairly good sense of available lighting levels at different locations within the space. Artificial lighting is also included within the calculation based on the photometric data provided within light families.
<br />
The accuracy of the luminous flux values depend in large part on the diffusion characteristics of the surface finishes. However, this tool has a built-in component to check whether a given space satisfies the requirements for the LEED Environmental Quality (EQ) rating.

# Wind Analysis
<figure class="half">
<a href="/projects/20180117_environmental_analysis/img/04_wind.png"><img src="/projects/20180117_environmental_analysis/img/04_wind.png"></a>
<a href="/projects/20180117_environmental_analysis/img/05_wind.png"><img src="/projects/20180117_environmental_analysis/img/05_wind.png"></a>
<figurecaption>Contextual models generated using Autodesk Infraworks <i>( Click to enlarge! )</i></figurecaption>
</figure>
Autodesk Vasari (no longer available) has a built in function to perform wind analysis by simulating a virtual wind tunnel. The site context was generated using Autodesk Infraworks. Autodesk Infraworks pulls data from local building authorities' online repositories to generate three dimensional contextual models.

# Energy Analysis
<figure class="half">
<a href="/projects/20180117_environmental_analysis/img/06_energy.png"><img src="/projects/20180117_environmental_analysis/img/06_energy.png"></a>
<a href="/projects/20180117_environmental_analysis/img/07_energy.png"><img src="/projects/20180117_environmental_analysis/img/07_energy.png"></a>
<figurecaption>Whole Building Analysis <i>( Click to enlarge! )</i></figurecaption>
</figure>
Whole Building energy analysis uses Rooms, Zones, and Spaces within the Revit model to estimate the annual energy costs for a particular site, orientation, and form. While this is an estimate, the engine behind the analysis is the widely used DOE2.2 Energy Analysis tool. Once again, the accuracy of the output varies with the quality of the input.
