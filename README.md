# Simon Game (Boss Challenge 2)

This [Simon](https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/12407762) project was created following Section 14 of [The Complete 2022 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) by Dr. Angela Yu, available on Udemy. This is the fifth major project in the course. It emulates a game known as [Simon](https://instructions.hasbro.com/en-us/instruction/simon-game). Simon is an electronic game of short-term memory skill invented by Ralph H. Baer and Howard J. Morrison, working for a toy design firm Marvin Glass and Associates, with software programming by Lenny Cope. The device creates a series of tones and lights and requires a user to repeat the sequence. In this project, a similar concept is employed through a website and a set of buttons, colors and sounds.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Improvements](#improvements)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Emulate the Simon game using jQuery.

### Links

- [Repo URL](https://github.com/akcumeh/simon-game)
- [Live Site URL](https://akcumeh.github.io/simon-game)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript + DOM manipulation
- [jQuery](https://jquery.com)

### What I learned

I've been learning a lot in this course, and in the last two sections where we have focused on **jQuery**, I learned...
- a few things about jQuery syntax. It truly makes writing JavaScript so much easier.
- about some simple methods to:
    * add and remove elements (```.before()```, ```.after()```, ```.prepend()```, ```.append()``` and the differences among all of them);
    * edit styles, attributes and content of HTML elements - using ```.css(<property>[, <newValue>])```, ```.attr(<attribute>[, <newValue>])``` and the ```.text()``` and ```.html()``` methods respectively;
    * add event listeners in much more flexible ways - e.g., for a click event, ```.click(<callbackFunction>)```, or a general and more flexible way, ```.on(<event>, <callbackFunction>)```;
    * create basic animations of any HTML element - using methods like ```.fadeIn()```, ```.fadeOut()```, ```.slideUp()```, ```.slideDown()```, ```.animate({<property>: <numericValue>})```, etc.
    among other tricks.
- a reinforced understanding of anonymous functions declared with ```function() {}```.

### Improvements
- **I included a "How to" section in the website.** Before this project, I had never encountered the Simon game, so I found it quite annoying, both to play and to code. So I've decided to make it easier and more accessible for those who are like me in having never played the game, by making it easy for them to understand right off the bat.
- **I sped up the game a little bit.** One of the things I found pretty bothersome about the game was how slow it was in producing the next sequence for the user to continue playing. Staying true to my improvmement mission included speeding up the game for a better experience.

I also planned to change the sounds of the game as they were too jarring, but that may have to be for some other time.

### Continued development

I would like to expand my knowledge of jQuery. By applying this library to more projects in the future, I can be more efficient in writing code because of how smoothly it simplifies JavaScript.

## Author

Thanks for reading this far! You can view and follow my profiles:

- GitHub - [@akcumeh](https://github.com/akcumeh)
- Twitter - [@akcumeh](https://www.twitter.com/akcumeh)