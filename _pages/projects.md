---
layout: page
title: Projects
permalink: /projects/
description: Here are some personal projects I’ve worked on over the years. While some of the older projects may not have the cleanest code, I’m still proud of all of them; especially the early ones, where I overcame the biggest challenges as a young beginner :). The projects are roughly in the order I completed them, though I’ve lost track of the exact years for some. Some of the project's interfaces are in German language. I hope to extend this list with more cool ideas soon.
nav: true
nav_order: 3
display_categories:
horizontal: false
---

<details>
    <summary>PPO Implementation from Scratch</summary>
        <p>
To gain a deep understanding of the PPO algorithm in RL, I implemented it from scratch using PyTorch.
Following the <a href="https://iclr-blog-track.github.io/2022/03/25/ppo-implementation-details">37 key implementation details of PPO</a>, I fine-tuned my implementation.
In the final stages, I compared my version with stable-baselines3 to resolve any performance differences and bugs.
</p>
<p>
This project provided great insights into the inner workings of RL algorithms and the importance of attention to detail.
You can find the code in my <a href="https://github.com/LabChameleon/PPOScratch">GitHub repository</a>.
        </p>
</details>

<details>
  <summary>Hungry Geese Kaggle Challenge Solution</summary>
<p>
During a university lab, I participated in the <a href="https://www.kaggle.com/c/hungry-geese/overview">Hungry Geese Kaggle Challenge</a> alongside three teammates.
The goal was to train RL agents to compete in a multi-player variant of <i>Snake</i> against other participants' agents.
</p>
<p>
We built everything from scratch without using RL libraries, so we could fully understand the underlying algorithms.
While this approach left us at a slight disadvantage compared to teams using more sophisticated libraries, it was a very cool experience.
You can find more details in our <a href="https://github.com/LabChameleon/Hungry-Geese">GitHub repository</a>.
</p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0"> 
        {% include figure.liquid loading="eager" path="/assets/img/hungry_geese.png" class="img-fluid rounded z-depth-1" max-width="700px" %}
    </div>
</div>
</details>

<details>
  <summary>Heiko Hamann's "Swarm Intelligence" Book Solution</summary>
  <p>
A while ago I read Professor Heiko Hamann's book <i>Swarm Intelligence</i>, which I found to be a very good read.
I worked through several of the exercises, and you can find my solutions in this <a href="https://github.com/LabChameleon/SwarmIntelligenceSolutions/tree/main">GitHub repository</a>.
</p>
<p>
Below is a video demonstrating one of the exercises where I implemented a simple flocking model:
</p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0"> 
        {% include video.liquid path="/assets/video/flocking_application.mov" class="img-fluid rounded z-depth-1" autoplay=true controls=false max-width="300px" %}
    </div>
</div>
</details>

<details>
  <summary>Simple Pong</summary>
  <p>
Most of my projects have focused more on deepening my understanding of specific concepts rather than building fully finished applications.
At one point, I decided to complete a full project and chose to create a simple version of Pong to keep things simple.
The key difference from the classic Pong game is that the ball doesn’t stop when a point is scored.
Instead, it's deflected off the opponent’s goal and continues, which adds a faster and more dynamic pace to the gameplay.
</p>
<p>
The project is implemented in C++ using the SFML library.
You can check out the <a href="https://github.com/LabChameleon/SimplePong">GitHub repository here</a>, and below is a little video showcasing the game:
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include video.liquid loading="eager" path="/assets/video/pong_application.mp4" class="img-fluid rounded z-depth-1" autoplay=true controls=false max-width="640px"%}
    </div>
</div>
</details>

<details>
  <summary>Fire Particle System</summary>
  <p>
In this project, I explored how effects like fire and water are created in video games.
For simulating fire, I discovered that particle systems are a common solution.
</p>
<p>
The project was implemented in C++ using the SFML library, and I gained valuable experience in programming shaders along the way.
You can find the GitHub repository <a href="https://github.com/LabChameleon/FireParticleSystem/tree/main">here</a>, and below is a fire animation—though it may not look entirely realistic just yet. ;)
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include video.liquid loading="eager" path="/assets/video/fire_particle_system.mp4" class="vid-fluid rounded z-depth-1" autoplay=true controls=false max-width="300px" %}
    </div>
</div>
</details>

<details>
  <summary>Rigid Body Simulation</summary>
  <p>
I've always been fascinated by the simulation of physics in games, and with this project, I aimed to better understand the underlying mechanics.
I implemented a simple rigid body simulation involving circles that can collide with each other and with static squares.
Throughout this process, I gained a better understanding of the many small details that must be handled to make a simulation look convincing to the human eye.
</p>
<p>
The project is written in C++ using SDL.
I initially planned to extend the simulation to handle arbitrary convex bodies, but I haven't yet completed that part.
The physics become much more complicated in this case.
</p>
<p>
You can find the code <a href="https://github.com/LabChameleon/RigidBodySimulation">here</a>, and below is a preview of the simulation in action.
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include video.liquid loading="eager" path="/assets/video/rigid_body_simulation.mp4" class="vid-fluid rounded z-depth-1" autoplay=true controls=false max-width="640px" %}
    </div>
</div>
</details>


<details>
  <summary>Conway's Game of Life</summary>
  <p>
For a time, I was very interested in Conway's Game of Life.
I created a simple implementation of the game using C++ and SFML.
You can find the code <a href="https://github.com/LabChameleon/ConwayGameOfLife">here</a>.
  </p>
  <!-- todo: add video if available -->
</details>

<details>
  <summary>German Computer Science Competition (2016)</summary>
  <p>
I participated in the 34th <i>Bundeswettbewerb Informatik</i>, a nationwide computer science competition in Germany.
The competition involved solving a series of exercises and submitting a final write-up of the solutions.
I ranked in the top 5% of participants in the end.
</p>
<p>
One of the exercises was about implementing an ant simulation, where ants forage randomly for food and leave pheromone trails after finding it, signaling other ants in the area.
You can find my C++ solution in this <a href="https://github.com/LabChameleon/AntSimulation">GitHub repository</a>.
  </p>
  <!-- todo: add image/video if available -->
</details>

<details>
  <summary>Supreme Risk Commander</summary>
  <p>
This is one of the projects I invested a significant amount of time into.
I initially began developing it in C++ with OpenGL to better understand the fundamentals of graphics programming.
Later, I transitioned to Java once I had a clearer vision for the project.
</p>
<p>
The game was designed to be a blend of two of my favorite strategy games: <i>Supreme Commander</i> and <i>Risk</i>.
From <i>Supreme Commander</i>, I borrowed the large-scale zoom, unit types, and overall scale.
The twist in my game was that new units could only be produced by capturing squares on the game field and holding them exclusively for at least 30 seconds, after which a new unit would spawn.
This mechanic gives credit to <i>Risk</i>, where new units spawn only in captured territory.
This could lead to rapidly escalating numbers of units, requiring significant tuning to keep the game running efficiently.
In particular, I had to implement smart strategies for relocating units to avoid overlap.
</p>
<p>
You can find the GitHub repository <a href="https://github.com/LabChameleon/SupremeRiskCommander">here</a>.
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/supreme_risk_appilcation.jpg" class="img-fluid rounded z-depth-1" max-width="700px" %}
    </div>
</div>
  <p>
The light squares represent territory currently controlled by the player and are used to produce new units.
The light dark green squares indicate contested territory, controlled by both the player and the enemy, making it unavailable for unit production.
The dark green squares represent the fog of war, where the player has no information.
</p>
<p>
In the center of the map, a small skirmish can be seen between the red and blue armies.
However, in its current state, the game remains somewhat dull, as the enemy lacks an AI and simply remains stationary to produce as many tanks as possible.
I consider the AI future work ;)
  </p>
</details>

<details>
  <summary>Android Black Jack Application</summary>
  <p>
Together with my Computer Science teacher, Susanne Terveer, I co-authored the iBook <i>Die App Black Jack und der Android Stack</i>.
The book is designed to help students learn about basic data structures by guiding them through the hands-on process of developing an Android application for playing Black Jack.
</p>
<p>
The book is supposed to allow for both self-study as well as to guide teachers according to the German Computer Science curriculum.
The iBook can be found <a href="https://books.apple.com/de/book/der-adt-stack-und-die-app-black-jack/id1021379694?l=en-GB">here</a>.
</p>
<p>
I contributed by helping to write the book and preparing many of the Android implementations.
You can find the GitHub repository for the project <a href="https://github.com/LabChameleon/BlackJack_Android">here</a>.
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/black_jack_book.jpg" class="img-fluid rounded z-depth-1" max-width="300px" %}
    </div>
</div>
</details>

<details>
  <summary>Assembly Arduino Projects</summary>
  <p>
I started with an Arduino starter kit that included a booklet of simple projects using Arduino C libraries.
To make things more interesting, I decided to implement some of the projects in Assembly directly on the Atmega328p microprocessor.
This turned out to be a surprisingly fun challenge, and I learned a great deal about low-level computing in the process.
It also involved plenty of confusing and painful hours spent digging through the microprocessor's technical documentation!
</p>
<p>
You can check out the GitHub repository for this project <a href="https://github.com/LabChameleon/ArduinoProjectsBook_Assembler/tree/main">here</a>.
Here is an image of one of the project's setups:
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/arduino_project.jpg" class="img-fluid rounded z-depth-1" max-width="300px" %}
    </div>
</div>
</details>

<details>
  <summary>VisualSort</summary>
  <p>
My Computer Science teacher wrote an official textbook for high school students, which was used in schools across the state of North-Rhine Westphalia to teach Computer Science.
To support students' understanding, I developed a Java application that visualizes different sorting algorithms.
The program was featured in the book and included in the official supplementary material.
</p>
<p>
Below is a preview of the application:
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/visual_sort_application.jpg" class="img-fluid rounded z-depth-1" max-width="700px" %}
    </div>
</div>
  <p>
The GitHub repository can be found <a href="https://github.com/LabChameleon/VisualSort">here</a>.
  </p>
</details>

<details>
  <summary>Quadtree Visualisation</summary>
  <p>
When I first started programming games, I became particularly curious about collision detection between agents.
As my games grew to include thousands of agents, all of which needed to check for collisions with each other, performance quickly became an issue, significantly slowing down my code.
To address this, I began exploring solutions for handling large numbers of agents and discovered that Quadtrees offer an efficient approach.
</p>
<p>
Quadtrees recursively partition the space into quadrants, so collisions only need to be checked between agents within the same leaf nodes.
This drastically improves performance when dealing with large numbers of agents.
I developed a small Java application to visualize how space is partitioned using Quadtrees and how this method can be applied for efficient collision detection.
</p>
<p>
A preview of the application can be seen here:
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/quad_tree_application.jpg" class="img-fluid rounded z-depth-1" max-width="700px" %}
    </div>
</div>
  <p>
The GitHub repository is <a href="https://github.com/LabChameleon/QuadTree_Visualization/tree/main">here</a>.
  </p>
</details>

<details>
  <summary>Gilbert-Johnson-Keerthi Algorithm Visualisation</summary>
  <p>
During school, I worked on a project focused on the Gilbert-Johnson-Keerthi algorithm for collision detection between arbitrary convex sets.
My write-up on the project won first prize in a mathematics competition, which came with a $500 award.
You can find the corresponding PDF <a href="/assets/pdf/Der_GJK_Algorithmus.pdf">here</a>, though it is in German.
</p>
<p>
As part of the project, I developed a Java tool that generates random two-dimensional convex sets and allows the user to arrange them on a plane.
The application then visualizes the intermediate steps of the GJK algorithm to check for collisions, as shown below:
  </p>
<div class="row">
    <div class="col-sm mt-3 mt-md-1"> 
        {% include figure.liquid loading="eager" path="/assets/img/gjk_application.jpg" class="img-fluid rounded z-depth-1" max-width="700px" %}
    </div>
</div>
  <p>
The GitHub repository can be found <a href="https://github.com/LabChameleon/GJKAlgorithm_Visualization">here</a>.
  </p>
</details>
