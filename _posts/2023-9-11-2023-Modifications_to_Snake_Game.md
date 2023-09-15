---
toc: true
comments: true
layout: post
title:  Modifications to snake game
description: How I changed the snake game
type: plans
courses: {compsci: {week: 3} }
---

# How I Changed The Snake Game
I changed the snake game by first changing to speed of the snake. This is how:
```
 // speed
            setSnakeSpeed(80);
            for(let i = 0; i < speed_setting.length; i++){
```
This modification makes the snake faster making the game a little harder.

The next thing I did was change the background color to purple. This is how: 
```
}
            // Repaint canvas
            ctx.beginPath();
            ctx.fillStyle = "purple";
            ctx.fillRect(0, 0, canvas.width, canvas.height);
```
This makes the game a little more visual appealing.

The final thing I did was change the snake and food red to make it seem more like it is eating apples. This is how:
```
 let activeDot = function(x, y){
            ctx.fillStyle = "#ff0000";
            ctx.fillRect(x * BLOCK, y * BLOCK, BLOCK, BLOCK);
        }
```
This makes the game more realistic.