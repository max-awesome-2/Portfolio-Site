---
layout: page
title: Bullet Hell System (2026)
description: A system for making bullet hell games in Unity, based on the builder pattern.
img: assets/window_warrior/img/window_warrior.png
importance: 1
category: other
related_publications: false
---

<h2>Summary</h2>
<p>The creatively named <b>Bullet Hell System</b> is my most active current project.</p> I played some of the *Touhou* games - which are a series of true bullet hell games - and was inspired to make something similar. I wanted to use Unity, since it's my favourite engine, but, I instantly came upon a dilemma. Each boss in Touhou has several phases, each of which contain up to dozens of groups of uniquely-behaving bullets. Let's say, for example, you want to create a simple boss phase where:
1. The boss shoots a ring of bullets around them that move out a little bit then pause.
2. Each of *those* bullets shoots out another set of bullets at the player in an arc.
3. The original bullets then pick a random direction, and slowly accelerate in that direction, then despawn after 5 seconds.

Just thinking about coding that in the standard component-oriented Unity style gives me a headache. Just for this one phase, how many different scripts would you need to create and keep track of? Well, maybe two, I guess, unless you wanted to do it all in one ugly script. More offensive, though, is the fact that in our steps above, we have a clear chronological picture in our mind of what we want to happen, step by step, but using a typical component-based approach would force us to de-chronologize (yeah, I just made that up) our lovely steps in order to make it actually happen in the engine. 



<h2>Lessons</h2>


