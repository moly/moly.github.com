---
layout: flat
title: Gorillas Online
---

# Flash Gorillas Online

<object width="640" height="350"><param name="movie"
value="gorillas.swf"></param><embed
src="gorillas.swf" type="application/x-shockwave-flash"
width="640" height="350"></embed></object>

## Description

Flash Gorillas Online is a multiplayer enabled re-make of the classic turn based artillery game [QBasic Gorillas](http://en.wikipedia.org/wiki/Gorillas_\(video_game\)). I was inspired to start this project after remembering how I permanently broke my copy of the original game when I was about eight years old, by trying to modify the source code without first making a backup (rest assured, I have since learnt from my mistake). 

The aim of Flash Gorillas is to hit your opponent with an exploding banana by varying the angle and power of your throw, taking into account wind speed, gravity, and the city skyline. There are three rounds in each game, with the overall winner being the player who wins the most. Winning games earns you experience points and makes you gain levels, which in turn unlocks costumes for your gorilla.

This project was my first time working on a networked multiplayer game. I started out by first creating an [offline single player version](https://github.com/moly/Flash-Gorillas), and then implemented the online features afterwards. In hindsight, this was probably not the best approach. The project became a little difficult to manage towards the end as the newer networking code occasionally had to be shoehorned in around the old offline code. If I were to work on a similar project again, I would definitely plan it as a online game from the get go.

Instructions not in the game; X or ESC cancels searching for opponents, T opens chat messages (while in game)

## Source Code

[github](https://github.com/moly/Flash-Gorillas-Online)

## Technical Details

**Language:** ActionScript 3.0 (Client), C# (Server)
**Tools:** FlashDevelop, Visual Studio, Photoshop
**Libraries:** [player.io](http://player.io)