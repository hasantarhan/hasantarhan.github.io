---
title: Carvival Dev diary 1
layout: post
post-image: "https://cdn.cloudflare.steamstatic.com/steam/apps/2626430/header.jpg?t=1699369431"
description: Hello folks, today I will tell you about my game idea and how I started this game.
tags:
- carvival
- indiegame
- game
- steam
- action roguelite
- bullet-hell
---

My game is called Carvival, and this game is actually a spontaneous project. One day I decided to develop vehicle physics in unity just for fun. Making vehicle physics is a very enjoyable thing for me, because I know a lot about vehicles and I want to simulate them realistically.

That's when a game called Brotato caught my eye on youtube, it's a very fun top down-bullet hell game where you manage a potato and blast incoming aliens. After watching the video of the game I immediately fell in love with it and I bought the game and started playing it. The graphics, sounds, music and controls of the game were very good, but what I liked the most was that we can add new weapons to the potato, we can attach 6 weapons to the potato and each weapon has different properties, which makes the gameplay very fun.

And that's when I had an idea: What if instead of a potato we could drive a fast car? I was very excited about this idea, because I could make a game like this using my vehicle physics. I immediately opened unity and started to develop my vehicle physics a little bit more. I added a drift feature to my vehicle physics, so the car could slide around corners and make it a more fun driving experience. I never thought an arcade car physics could be so fast and beautiful.

<iframe width="560" height="315" src="https://www.youtube.com/embed/H8pgxRVePRY?si=Nsg8J2prBECszV_X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
So how did I make this vehicle physics? It's actually very easy, everyone who develops games in unity has made a ball rolling game, so I made a ball in the same way and made the vehicle body follow it. So the movements of the ball were reflected in the movements of the vehicle.

<iframe src="https://giphy.com/embed/FY7eCXJr3GBsA0MUx9" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/FY7eCXJr3GBsA0MUx9">via GIPHY</a></p>
But is that enough? I mean, we just put a ball and we connect the car to it, but I can't adjust how much the car turns, how much the car drifts, so I thought about it and decided to use animationcurves. With animationcurves, the game could dynamically change values like friction and drag, so I could have full control over the physics of the car.