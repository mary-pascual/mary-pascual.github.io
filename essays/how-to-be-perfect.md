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

## How to go from Simple to Professional

The beautiful thing about creating a website is that it's very straight forward because compared to other languages, HTML is very simple.  Personally, when I was first introduced to the language, I couldn't believe how quickly I could pick it up.  Unlike other programming languages that feel like a foreign language, this language feels as though it's in English.  It's also a difficult language to make mistakes in because a user can automatically see the results of their program unlike other programs where a user has to atempt to pinpoint the exact location that's causing a function not to work (which could be located in a different function).

With HTML if a user needed a header, image, and link in his website, he would just have to type
```
<body> //body of the website
<h2>Table of Contents</h2> //header with number being size
<a href="#IE">Internet Explorer</a>//link to internet explorer header
<h3><a name="IE">A Brief History of IE</a></h3>
<img src="https://upload.wikimedia.org/wikipedia/en/1/10/Internet_Explorer_7_Logo.png" width="100px">//desired image inserted
</body>//close body of website
```
If the user wants to change the design of the website, he can easily do it on the CSS.  For example, if he wanted to change the body's font style and color, he would have to type the following:
```
body{
  font-family: 'Open Sans', sans-serif;
  color: darkblue;
}
```
Though HTML and CSS are very straight forward, it gives the user the result of a plain website created in the 1990s.  However, if we throw in [Semantic UI](https://semantic-ui.com/), we start to see the beginning of a typical website we'd see today.  When I tested out Semantic UI, I tried to recreate the [Breakout Waikiki website](https://www.breakoutwaikiki.com/).  Like most websites, this one included a top menu.  Because I was creating the website with Semantic UI, I could easily create a similar top menu with the class "ui borderless inverted menu", which only affects the top menu and not the whole body.  In the end, [my website](https://github.com/mary-pascual/breakout) looked pretty similar to the original website to the point where my friends honestly thought it was the real one.
```
<div class="ui borderless inverted menu">
    <a class="item"><h1><img src="https://static1.squarespace.com/static/55e7ec25e4b0936846c7ec12/t/564100f8e4b07ea8de5407f0/1484027202845/?format=1500w" width="268px"></h1></a>
    <a class="right item">HOME</a>
  </div>
```

## Don't get too Cocky

Though all three tools are simple to use, don't be fooled.  Website design requires a lot of time and patience, which was tested when I first started the Breakout Waikiki website.  I almost gave up.  Though I tried with a variety of numbers, I could never seem to get the size of the logo or background image right.  After many hours, I gave up and instead, tried to find the exact font family that the website used.  After many more hours spent on that, I finally realized why people hire others to build websites.  Website design requires simple languages.  However, like all of the other coding languages that I've learned, I also need to put in the time and have the patience in order to get the result that I desire.

<img class="ui image" src="http://myindefiniteworld.com/blog/wp-content/uploads/2011/10/FoxTrot-2011-10-02.gif" style="width: 425px; height: 198px">
