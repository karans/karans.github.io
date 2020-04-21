---
layout: page
title: Purdue Aerial Robotics IEEE
description: 2014-2016
img: /assets/img/projects/PARTIEEE/plane.jpg
---

Purdue Aerial Robotics is part of Purdue's IEEE branch and we worked on making an autonomous plane to fly in the [AUVSI SUAS](http://www.auvsi-suas.org/) competition. When I joined the club had just restarted and we were essentially working from scratch.

<figure>
    <img src="/assets/img/projects/PARTIEEE/plane.jpg" style="width:500px;height:375px;">
    <figcaption>The first flying prototype</figcaption>
</figure>

During the initial stages I was working on getting some lower level software to achieve stable flight with a waypoint system and tx/rx buffer controllers from the ground. I would later take on working on what we called the "ground station", which displayed flight diagnostics and plane location on a map overlay. From this station we would preprogram coordinates that the plane would have to fly to, but it would be up to the planes systems to figure out an efficient way to navigate to these coordinates.

Once we a plane up and running, I wrote a communication API to talk to the competition server. The server hosted a Django framework and could be accessed by HTTP calls while being reasonably secure (part of the competiton).