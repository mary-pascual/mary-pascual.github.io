---
layout: essay
type: essay
title: How to Create a Perfect Website
date: 2017-02-23
labels:
  - Software Engineering
  - UI Frameworks
---

# Time for Change!

After months of learning different languages in order to get a program to do something as simple as adding together two numbers a user inputs, it's nice when the professor offers a change of scenery by introducing a subject that more than half of the computer science majors were looking forward to: website design.  Unlike programming, website design allows us to satisfy our creative side.  For once in our lives, it felt as though we were creating what we wanted to create and that we weren't just doing it to complete an assignment.

## Creating a Website: Idealism vs Realism

The beautiful thing about creating a website is that it's very straight forward and with some patience, even a beginner can make it look professional.  Through my own experience, I learned that [Semantic UI](https://semantic-ui.com/) is a good starting part because the website displays the code and the results of the code.  I also discovered that I could easily see the results of my work whenever I made even the slightest change so it makes it easier to know what is working and what needs be changed.

When I tested out Semantic UI, I tried to recreate the [Breakout Waikiki website](https://www.breakoutwaikiki.com/).  Like most websites, this one included a top menu, and because I was creating the website with Semantic UI, I could easily create the top menu with the class "ui menu", add another class called "items" under it to list the things I want in that menu, and change the font color to white by changing the class name to "ui borderless inverted menu" as show below.  In the end, [my website](https://github.com/mary-pascual/breakout) looked pretty similar to the original website to the point where my friends honestly thought it was the real one!
```
<div class="ui borderless inverted menu">
    <a class="item"><h1><img src="https://static1.squarespace.com/static/55e7ec25e4b0936846c7ec12/t/564100f8e4b07ea8de5407f0/1484027202845/?format=1500w" width="268px"></h1></a>
    <a class="right item">HOME</a>
    <a class="item">BOOK A GAME</a>
    <a class="item">PRESS</a>
    <a class="item">GIFT CARD</a>
    <a class="item">PARKING</a>
    <a class="item">FAQ</a>
    <a class="item">WORK HERE!</a>
  </div>
```
For the longest time, I was on cloud nine thanks to Semantic UI to the point where I worshipped it.  Then, reality struck.  Though I succeeded in tricking people to think my website was the real website, it's difficult to copy a website exactly.  When I first started the Breakout Waikiki website, I almost quit because I could not match the font style and correctly size the background and logo.  Frantically, I played around with every different font I could find and with every different size I could come up with, but it was never an exact replica.

## Is Semantic UI the Only Way?

As I'll probably learn throughout my programming career, there are always more than one way to do things and building websites is included.  Before being introduced to Semantic UI, my Software Engineering class taught a different way to create websites using HTML and CSS.  Though both play a role with Semantic UI, without the Semantic UI, the website looks plain.  It was also very difficult to achieve certain things without Semantic UI.  For example, when you try to replicate a website, more than likely, you will need columns.  With HTML and CSS, my friend and I groaned in fustration when we could not for the life of us figure out why the columns kept looking weird.  We had to put each paragraph in its own column and dictate to the column where it would go (left, center, or right).  However, if one column was not done right, it screwed up all the columns.

On the other hand, Semantic UI has an easy way to include columns.  Simply, insert the class "ui [number of columns desired] column grid container".  Then, you can create a class called "column" and indicate what you want inside each column.  By doing so, less time can be spent on easy tasks that Semantic UI can handle and more time can be spent on other feautures.

<img class="ui image" src="http://www.silkstream.net/blog/wp-content/uploads/2014/12/red-blue-web-design-comic.gif">
