---
title: Learned
header: Things I Learned
layout: page
permalink: /learned
---

## Things I Learned
These are some programming related things that I learned.

## Hour of Code - [code.org](https://www.code.org)
![Example Screenshot](/assets/img/code.org.jpg)

The first programming related thing I learned was at school. In my school, once or twice every year we did a things called [*hour of code*](https://code.org/learn) on code.org. This was when I was in 5k. In code.org, I did things like moving an object up, down, left, and right to get out of a maze. Code.org has drag and drop blocks that you can adjust. Code.org has small coding tutorials that are for teaching little kids some simple coding.

### What I learned
I learned how to make a sequence of tasks that get run. In the maze course, they were blocks called `forward`, `backward`, and `turn` (for turning left and right).

I also learned that tasks can be repeated multiple times. There was a `loop` block, which you can choose how many times it gets run. I learned that things inside the `loop` block get run multiple times, while things outside the `loop` block get run a single time. I also learned about conditionally doing things, such as turning left or right based on whether there is a wall ahead or not.


### Projects
When learning coding on code.org, I did many puzzles where you have to move a character through obstacles, going from a starting point to a destination point.

## Intro to JS: Drawing & Animation - [Khan Academy](https://khanacademy.org)
![Example Screenshot](/assets/img/khan-academy.jpg)

When I was in 2nd grade, my friend talked about a thing called *javascript*, which he was learning on Khan Academy. I got interested, and I also started doing a course called [*Intro to JS: Drawing & Animation*](https://www.khanacademy.org/computing/computer-programming/programming). The course was a set of videos, challenges, quizzes, and projects. The course was based on drawing and animating shapes with javascript.

### What I learned
I learned what javascript is. I learned the syntax, such as declaring and using variables, and calling functions. At first, the course taught how to call some functions that Khan Academy provided. Example:
``` js
rect(0, 0, 400, 400);
```
This drew a rectangle on the screen, which had a total size of 400 by 400 pixels. The course also taught how to use different types of data, like numbers, strings, objects, and arrays. I learned how to declare variables and change them. An animation looked like this.
``` js
var x = 100;

var draw = function(){
    ellipse(x, 200, 50, 50);

    x += 1;
};
```
Any function named `draw` was called automatically by Khan Academy, which made a circle go from left to right on the screen. I also learned how you can make a game by detecting mouse clicks and key presses.

### Projects
- [The Maze Roller Game](/projects/the-maze-roller-game)
- [Digital Stick Picker](/projects/digital-stick-picker)

## Intro to HTML/CSS: Making webpages - [Khan Academy](https://khanacademy.org)
![Example Screenshot](/assets/img/html-course.jpg)

After I did the javascript course on Khan Academy, I started doing an html course. The course was similar to the javascript course.

### What I learned
I learned what html is, and how to set up a simple html page. I learned how the syntax for elements is, and how at the top of the file there is 
``` html
<!DOCTYPE html>
```
. The first part explained how there is a `<html>` tag, and the `<head>` and `<body>` tags are inside the `<html>` tag. The course then taught about `<h1>`, and `<h2>` tags, and how there are header tags up to `<h6>`, which are used for headers. I also learned about `<p>` and `<img>` tags, and how some tags, such as `<br>` don't get closed. I also learned about css, and how you can change the colors and sizes of html tags. I didn't learn that much css, mainly about the selectors, such as all elements, based on id, and based on class names. 

### Projects
I didn't start any projects when I learned html, but I made some things later using what I learned.
- [Idioms Game](/projects/idioms-game)

## HTML/JS: Making webpages interactive - [Khan Academy](https://khanacademy.org)
![Example Screenshot](/assets/img/html-js.jpg)

I continued exploring programming courses in Khan Academy, and I started a course called [HTML/JS: Making webpages interactive](https://www.khanacademy.org/computing/computer-programming/html-css-js). 

### What I learned
I learned that javascript can be put in an html `<script>` tag, and it can be used to change html elements. I learned how to use `document.getElementById()` and `document.getElementsByClassName()`. I learned about changing an elements `innerHTML`, adding event listeners, and using `console.log()`. At first I got a little confused, because I was used to javascript drawing shapes in the other course that I did.

### Projects
I didn't do any projects specifically while I learned this course, but I used what I learned in this course in my future projects
- [Idioms Game](/projects/idioms-game)