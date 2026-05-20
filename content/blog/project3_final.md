---
title: Project 3 Final
description: Project 3 - Final
date: 2026-05-20
---

<h2 class = "header-title-alt"> My Contribution </h2>

<p> 
    I focused on the background audio and the 3D positional audio for the duck. I wanted the environment to feel alive even before users interacted with ducks, so I added looping ambient background music. I used this website as a reference for the <a href = "https://threejs.org/docs/#Audio"> background audio </a>. The only difficult part of the background audio was the browser autoplay restrictions, which blocked out the audio. I overcame this hurdle by resuming only after the user clicked(main.js: Lines 119 - 135).
</p> 

<p>
    My secondary goal was to make the duck object emit a sound in a 3D Space, while tailoring the sound volume to camera distance. Or in simple terms: <i>The closer the duck, the louder the audio.</i> Initally, this was not a part of the plan but an add-on, something I wanted to try out frantically. Originally, I wanted to add this with the tree, cat, and duck, but I focused solely on the duck because I thought it would overwhelm the user with all those sounds hitting simultaneously. I experimented with the Core Spatial Settings(setRefDistance(), setRolloffFactor() and setMaxDistance() <b>Lines 24-26</b>). Which worked, but the duck audio began to loop infinitely. Ultimately, this part for me was the most difficult, and I was just stumped for a while. Eventually, I had created a workaround by making the duck loop the audio a finite amount of times(3 times specifically), but then I changed it by using raycasting(Making the duck object itself clickable) instead as a smoother method.
</p>

<h2 class = "header-title-alt"> My Teammates </h2>
    <p>
        <ul>
            <li> <a href = "https://judyzhang05.github.io/web-design-blog/blog/99_project3Final/"> Judy Blog Post </a></li>
            <li><a href = "https://jorgevin74.github.io/web-design-blog/blog/project-3-final/
            "> Jorge Blog Post </a></li>
            <li><a href = "https://krisswan253.github.io/web-design-blog/blog/Project3/"> Kris Blog Post </a></li>
        </ul>
    </p>

