---
name: Sci-Fi Subway - Level Design
tools: [Level Design, Environment Design, Prototyping]
image: /assets/images/subway-level-design-project.png
description: A single-player level, designed and prototyped for a 3rd person shooter experience in mind. Complete with enemy placement and clutter.
---

<u>Sci-Fi Subway - Level Design</u>
===========================
A prototype level design made in Unity and Unreal Engine 4 for a digital prototyping unit at Southampton Solent University with the premise of the game being that of a 3rd person cover based shooter.

## The Task
---

For this unit, we were tasked with making a game as a team from a given gameplay template. The gameplay template was that of a 3rd-Person cover based shooter in the vein of titles such as Gears of War.

As a team, we would come up with an artistic theme and aesthetic, split the game's narrative into 4 acts and 4 levels. This means that each of us got to create a separate level and show our design skills and we had to link them up with each other some way.

After discussions we settled on a sci-fi dystopian theme and a story about a freedom fighter. I was given the second level in which the character is trying to sneak into the enemies base. I chose an underground railway as the setting as it fit nicely with my previous team members level which took them from an abandoned factory.

### Level Layout
---

With the idea down. I iterated on my level design. I worked through roughly 30 odd layouts and came up with a design that composed those that I liked together.

My criteria for design and selection were designs that offered variance to the player for them to express themselves and feel less linear. A problem with 3rd-person cover shooters is how often they can leave a very linear feel in the players gameplay, so I felt it important to offer the player a clear, but optional route with a scalable challenge as well, with one path being harder than the other. I also tried to focus on a design that was manageable in scope and look. Having iterated, I came upon what is my final design below.

<figure>
    <a class="image-link" href="/assets/images/subway-level/level-layout.png">
        <img src="/assets/images/subway-level/level-layout.png" alt="level layout image" title="Level Layout">
    </a>
    <figcaption text-align="center">Level Layout (Click image to open.)</figcaption>
</figure>

### Level Graph
---

With my level design down, I progressed onto creating a level flowchart to help showcase in a simple form, the level's gameplay elements and matchups. The flowchart shown below details each room the player will move through from start to finish as well as the enemy AI types they will encounter in each and any pickups that may be in each room. This helps to distil the essence and flow of the player through the level.

<figure>
    <a class="image-link" href="/assets/images/subway-level/level-graph.png">
        <img src="/assets/images/subway-level/level-graph.png" alt="level graph image" title="Level Graph">
    </a>
    <figcaption text-align="center">Level Graph (Click image to open.)</figcaption>
</figure>

### Level Storyboard
---

With the level design and flowchart down. I had to create a storyboard to show the gameplay narrative and flow to our lecturer. I had to pitch the level and show how the player moved through and the various scenes they would see.

The storyboard is not a final reflection and only serves to help think through what various scenes the player might see and how I want to direct them with the level's objects and design. It helped me a great deal before I went into grey boxing as it helped inform me how various segments might look and what objects required prominence or changing in position. Embedded below is a carousel of the level's storyboard.

{% capture carousel_images %}
/assets/images/subway-level/page-1.jpg
/assets/images/subway-level/page-2.jpg
/assets/images/subway-level/page-3.jpg
/assets/images/subway-level/page-4.jpg
/assets/images/subway-level/page-5.jpg
/assets/images/subway-level/page-6.jpg
/assets/images/subway-level/page-7.jpg
/assets/images/subway-level/page-8.jpg
{% endcapture %}

{% include carousel.html %}

### Level Creation
---
With the level design, flowchart, and storyboard complete. I then proceeded on to grey boxing the environment first in Unreal 4 using BSP's. This was a time intensive task and took a great deal to get used to, but once I had it down it became a breeze to use. With my grey box complete in UE4 I then proceeded on to create my models in 3DS Max and Blender which I then used to replace my grey box designs with some of my realised assets from my storyboard.

After having finished the level layout and lighting in UE4 I then proceeded onto Unity and its Pro-builder tool. I found this far more comfortable than UE4's BSP's almost immediately as it functions like a fully-fledged modelling package inside of the engine. I very quickly grey boxed and imported my created assets into the scene.

### Level Fly-Through
---
With the levels now created. We had to select an engine to finalise and show our level in. Unity was chosen so as to utilise its Cinemachine tooling. So, shown below is a Cinemachine fly-through of the mocked-out level. It is filled with only rudimentary assets to help denote positions and layout of the overall architecture and layout.

The camera shows the path of progression the player will take through the level and also show the second split-path that they can optionally take.

<div class="video-display">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/I9IfO9lWEPk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
</div>
