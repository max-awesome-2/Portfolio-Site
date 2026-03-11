---
layout: page
title: Monkey Fight (2020)
description: The ultimate simian showdown.
img: assets/img/monkey_fight.png
importance: 1
category: just-for-fun
related_publications: false
---

<h2>Summary</h2>
<p><a href="https://maxy3702.itch.io/monkey-fight">Monkey Fight</a> is a simple multiplayer Quake-esque shooter that I made using Unity and the Mirror networking package. It was my first 'published' game (I put it up on itch.io). I made it over <b>two weeks</b> around the start of the pandemic.</p> 

<h2>Notable Features</h2>
* A launch screen where players can input their usernames and either host a server or join another player's server by IP
* Two gamemodes - elimination and deathmatch, both playable as teams or free-for-all
* Four unique weapons - a shotgun, assault rifle, rocket launcher, and sniper rifle - all modelled by yours truly!
* Fully animated characters (I made the animations, but the model is from TurboSquid)
* Animations and sounds synced over the network

<h2>Lessons</h2>
1. This was my first encounter with multiplayer programming & networking. The Mirror paradigm was a real challenge to wrap my head around, but I grew fond of it fast. I want to make more multiplayer games...
2. It's not as hard as I thought to make a nice(-ish) looking UI. I made the UI box and banana button images myself in Photoshop - all it took was a little bit of shading to get them looking surprisingly good.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/titlescreen_early.png" title="early title screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/titlescreen.png" title="title screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The title screen early on in development, vs. the final version.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/firstpersonview_early.png" title="first person view early" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/firstpersonview.png" title="first person view" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    These two first-person view shots show how the UI and lighting evolved throughout the game's development.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/sniper1.png" title="sniper1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/sniper2.png" title="sniper2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A before-and-after of a player getting a kill with the sniper rifle. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/mapdesign.png" title="original map design" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/courtyard.png" title="courtyard" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/monkey_fight/courtyard_final.png" title="courtyard final" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The image on the left is the original design I drew up for the map. I designed the map in 'floors', with each level of verticality of the map being represented by a different color. The two images on the right show the first and final versions of the map.
</div>

<h2>Fun Facts </h2>
* I had decided on making a multiplayer shooter game, but couldn't choose beetween theming it around monkeys or cockroaches (yeah). I had a friend choose for me. If not for a simple twist of fate you could be looking at a game called "Roach Fight" right now.
* I have a lot more granular commentary on the creation of Monkey Fight on my Blogger blog that I wrote as I was making the game in 2020. It's very interesting. I'll probably transpose it here at some point, for the sake of historical preservation.
* The source code for the game was on my hard drive that crashed, and for some reason I never put it in version control, so it's gone forever :(