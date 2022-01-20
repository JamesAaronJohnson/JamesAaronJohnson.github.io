---
name: Substance Map Combiner - Workflow Tooling
tools: [C#, Winforms]
image: https://james-aaron-johnson.github.io/assets/images/Substance-Map-Combiner-Project.jpg
description: A small application made to combine multiple substance exports into a single texture map.
---

<u>Substance Map Combiner</u>
=======================

<br>

![](https://james-aaron-johnson.github.io/assets/images/Substance-Map-Combiner-Overview.gif)
<div class="footnote">
<small>Aplication Usage Showcase.</small>
</div> <br>

Substance Map Combiner is a small application I made to help speed mine and several other artists workflows.

It is made in winforms using C#. After prototyping it with my own image manipulation on bitmaps I ended up using a library called ImageProcessor as it was far faster than my own implementation and has little size cost. The application helped me learn a great deal about creating front-end GUIs for users and how to make things simpler and abstract information so that users can access and do what they need without clutter.

## What Does it Do?
---
The application works by combining the various output texture sets from Substance Painter into one large texture map. It was made for those who use **material ID's** to split their objects into multiple sub-materials to then paint them inside of Substance Painter. 

After finishing Substance Painter exports these with transparency as their various texture set parts and it can be cumbersome to overlay them in photoshop. The application simply requires the source folder of the texture sets and where to place them when combined and it will it overlay them all into one texture map of their relevant channels: _base_color, metallic, roughness etc._
The application also gives the ability to decide what image type to export them as, what background color to give each map to fill the transparent sections and also what order to overlay them in if some things have a higher bleed/dilation than others.

For more information on the application head to the repo
<p class="text-center">
<a href="https://github.com/Chi-Time/Substance_Map_Combiner/tree/dev" class="button" target="_blank">Substance Map Combiner Repo</a>
</p>
