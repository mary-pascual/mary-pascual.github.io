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

The beautiful thing about creating a website is that it's very straight forward because compared to other languages, HTML is very simple.  For example, if a user needed a header, image, and link in his website, he would just have to type
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
Though HTML and CSS are very straight forward, it gives the user the result of a website created in the 1990s.  However, if we throw in [Semantic UI](https://semantic-ui.com/), we start to see the beginning of a typical website we'd see today.  When I tested out Semantic UI, I tried to recreate the [Breakout Waikiki website](https://www.breakoutwaikiki.com/).  Like most websites, this one included a top menu.  Because I was creating the website with Semantic UI, I could easily create a similar top menu with the class "ui borderless inverted menu", which only affects the top menu and not the whole body.  In the end, [my website](https://github.com/mary-pascual/breakout) looked pretty similar to the original website to the point where my friends honestly thought it was the real one!
```
<div class="ui borderless inverted menu">
    <a class="item"><h1><img src="https://static1.squarespace.com/static/55e7ec25e4b0936846c7ec12/t/564100f8e4b07ea8de5407f0/1484027202845/?format=1500w" width="268px"></h1></a>
    <a class="right item">HOME</a>
  </div>
```
<img class="ui image" src="http://myindefiniteworld.com/blog/wp-content/uploads/2011/10/FoxTrot-2011-10-02.gif" style="width: 400px; height: 200px">
