---
title: The Maze Roller Game
layout: project
permalink: /projects/the-maze-roller-game
---
## [The Maze Roller Game](https://www.khanacademy.org/computer-programming/the-maze-roller-game/5158338680651776)
A game where you control a ball going through a maze full of obstacles.

![Screenshot](/assets/img/the-maze-roller-game.jpg)

### Technologies Used
JavaScript, Khan Academy Javascript

### When
When I was in 3rd grade.

### Why
When I was learning javascript, I really wanted to make a game. I like playing video games, so I wanted to make them too. When I started making *The Maze Roller Game*, I showed it to my friends. They helped me test them, suggested new features, and designed levels in the game.

### Challenges
- When I was making the level selection scene, clicking on the play button would also click on a level button (for example, if the mouse position clicked the play button, and then also clicked the *1* button, which started level one.). I avoided this problem by using number keys, 1 - 9, to select levels.
- To store the data about the walls in different levels, I had an array called `cell`. This array had levels in it, and each level as an array containing arrays. I got confused when referencing nested arrays. At first, I would do:
``` js
cell[0[0]]
```
Then I realized that I needed to do:
``` js
cell[0][0]
```

### What I Learned
- How to manage having different scenes in the game (such as the *start scene* and *how to play scene*).
- How to use arrays inside of arrays for rows and columns.
- How to check if pressing a key is valid (like not moving the ball if it would run onto a wall).
- How to detect when one object hits another.
- How to animate many moving objects.