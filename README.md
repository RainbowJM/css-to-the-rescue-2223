# Table Of Content
* [The Firework Show](https://github.com/RainbowJM/css-to-the-rescue-2223#the-firework-show)
    * [Progress](https://github.com/RainbowJM/css-to-the-rescue-2223#progress)
        * [Week 1](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-1)
        * [Week 2](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-2)
        * [Week 3](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-3)
        * [Week 4](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-4)
    * [Reflection](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#reflection)
    * [Source](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#source)
---
# The Firework Show

In this repository, you will be able to follow my progress is gaining more knowledge in CSS in general. At the beginning of this course, my knowledge of CSS was to only use `<div>` with `id` and `class`. But in this project you will see how I gained more knowledge about CSS, starting with CSS selectors. 

In this project, you will see how I learned to use all the different CSS selectors. All of this I have done it in an interactive firework show.

Main Goal:
Learn how to work with different CSS Selector and create a show with the knowledge that I get while learn CSS.

<img width="1352" alt="Screenshot 2023-03-08 at 10 11 46" src="https://user-images.githubusercontent.com/59873140/223681461-d73908e2-9392-4d35-a416-507b202a2c39.png">

## Progress
- [Week 1](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-1)
- [Week 2](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-2)
- [Week 3](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-3)
- [Week 4](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-4)
---
# Week 1
In the first week, we had to choose an assignment out of the 4 options.

The options were:
- 'Modulair bediennings paneel'
- 'Interactieve vuurwerkshow'
- 'Maak een 3D rubrik's kubus
- 'Tailwind zonder tailwind, met moderne CSS'

After checking all the options, I went with the *Interactive Firework Show*.

Techniques that I think I will use for this assignment:
- Grid
- Scroll snap
- Animations
- Keyframes

At first, I wanted to make a show with only emoji's. When I was browsering to find all the possibilities, I saw that there were so many things that you can do with CSS. That is why I decide to create a slideshow where I can show different show and techniques that I have learn. 

<img width="783" alt="Screenshot 2023-03-08 at 15 29 27" src="https://user-images.githubusercontent.com/59873140/223739680-24331541-f971-49c7-922d-0c6cc03c2961.png">


My biggest changeling will be to not use `id` or `class` in the HTML or CSS.

The first thing that I did was to figure out how to make a slideshow. This is when I find out about `scroll-snap`. After I got that working, I started with the first show. In this show, I wanted to let something move. 
After the workshops and a little bit of research. I find out that you can do that by making an animation and by using `transform`.

<img width="1164" alt="Screenshot 2023-03-08 at 11 51 59" src="https://user-images.githubusercontent.com/59873140/223696449-250d4fe1-536f-4aa5-9c0b-2f9b7d1adeee.png">

What I did was that the box goes up, and then you have two others will move from the middle to the side and only a green box will be in the middle. It keep repeating itself.

To make an animation in CSS you have to use `keyframes`. With this, you can tell the object what to do at what time.

<img width="1158" alt="Screenshot 2023-03-08 at 12 29 29" src="https://user-images.githubusercontent.com/59873140/223702272-79862b47-09e0-4da7-80ad-a081a8688abb.png">

---
# Week 2
One of the workshops I got the idea to make an animated pixel art.

For the pixel art I used `box-shadow` to create the heart shape and I used again `keyframes` to animate the colors of the heart shape.

Also, this week I tried to create e bouncing show of color. When I was making it, something  unexpected happened. Because I didn't use the correct CSS Selector, it effected the first two shows also. Check the pictures below.

<img width="1122" alt="Screenshot 2023-03-08 at 12 52 51" src="https://user-images.githubusercontent.com/59873140/223706634-44d6ad02-0308-40a1-8400-11feb8282aef.png">

<img width="1119" alt="Screenshot 2023-03-08 at 12 53 11" src="https://user-images.githubusercontent.com/59873140/223706676-c3cc3018-e0b2-420b-83d8-e304b9db2bce.png">

When I updated the CSS Selector for the bouncing show of color, I got another shape than what I was expecting. See below.

<img width="1121" alt="Screenshot 2023-03-08 at 12 58 19" src="https://user-images.githubusercontent.com/59873140/223707553-4dfcb71e-93b9-4b01-ba24-18f2a583a40a.png">

<img width="1010" alt="Screenshot 2023-03-08 at 13 12 26" src="https://user-images.githubusercontent.com/59873140/223710521-ed36abc3-e0cd-4b94-89fd-752e33ba764f.png">

<img width="1013" alt="Screenshot 2023-03-08 at 13 12 38" src="https://user-images.githubusercontent.com/59873140/223710539-09565740-b392-40d1-86bd-e6456079f423.png">

This saw because I didn't use the correct child of the `div` for this show, after a while discovered the error and fixed it.

I made a branch of this also:
- [Damage heart](https://github.com/RainbowJM/css-to-the-rescue-2223/tree/damage-heart)
- [Pixel-heart-damage](https://github.com/RainbowJM/css-to-the-rescue-2223/tree/pixel-heart-damage)
- [Firework-to-confetti](https://github.com/RainbowJM/css-to-the-rescue-2223/tree/firework-to-confetti)
---
# Week 3
Now that I had 3 of the shows done, now I wanted to add the interactive part of the show. Where you can click on something and it changes the show. 

One of the interaction that I have applied is that when you check the box, the background changes.

This is the part where gradients come to play. All the background has a gradient effect.

There are 6 type of gradient:
- Linear-gradient
- Radial-gradient
- Conic-gradient
- Repeating-linear-gradient
- Repeating-radial-gradient
- Repeating-conic-gradient

For the shows I only used:
- Radial-gradient
- Linear-gradient
- Repeating-linear-gradient

I wanted to experiment with all six, but in the end I chose to only use three.

For the interaction I used `:has()`, basically I did that each time that you check a box it changes the background to the gradient version. 
Also, I used the `:has()` for that animation of almost all the shows.

This caused some color mixed that did not match with what I wanted. 
<img width="1352" alt="Screenshot 2023-03-08 at 10 11 46" src="https://user-images.githubusercontent.com/59873140/223720079-e3722845-e252-455d-8254-718ab239f5e6.png">

<img width="1116" alt="Screenshot 2023-03-08 at 14 00 48" src="https://user-images.githubusercontent.com/59873140/223720101-c4f16fa7-2491-4f2c-b0ad-08362853bb4a.png">

<img width="1108" alt="Screenshot 2023-03-08 at 14 01 04" src="https://user-images.githubusercontent.com/59873140/223720125-ff7fab7d-cb59-45f3-846d-ec3ef4cec81f.png">

In the 4th show, I did the show by using `clip-path`

---
# Week 4 
This is the last week of the project. 

My goals for this week is/was to add one last section of firework show. And do the last final touch ups.

For the 5th section, I wanted to create a realistic firework show with gradient. When I was creating it, I got in trouble. The whole show started glitching, and I couldn't figure out why. 
So I meant a branch of the show and created another show.

The branch:
- [Unexpected](https://github.com/RainbowJM/css-to-the-rescue-2223/tree/unexpected)
---
# Reflection

Like I said in the beginning, at first I did not know anything about CSS selectors. All web application that I have made I used `id` and `class`. 
For me, this was a very interesting and educative. I learned a lot about the CSS selector.

It was very challenging to only work with CSS selector, but I did it and make something out of it. 
That works and does what it was intended to.

Once I understood how CSS selector works it was pretty easy to work with it. The part that I find difficult was gradient to understand it when you start using more then one together. But I did make something with it.

Things that I did not get a changes to learn are SVG and 3D.

For the final result please check this 
[THE SHOW](rainbowjm.github.io/css-to-the-rescue-2223/fireworks)

---

# Source
- [:has()](https://codepen.io/shooft/pen/NWLWLdP)
- [:has() checkboxes](https://codepen.io/shooft/pen/zYJYmGJ)
- [intro :has()](https://www.matuzo.at/blog/2022/100daysof-day6/)
- [gradient](https://codepen.io/shooft/pen/YzpVjOw)
- [intro gradient](https://css-tricks.com/css3-gradients/)
- [shapes](https://codepen.io/shooft/pen/zYoBXzj)
- [clip-path](https://davesmyth.com/clip-path-scaling)
- [intro clip-path](https://ishadeed.com/article/clip-path/)
- [animation](https://codepen.io/shooft/pen/eYBdvey)
