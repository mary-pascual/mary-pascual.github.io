---
layout: essay
type: essay
title: The Scoop on ESLint with IntelliJ
date: 2017-02-09
labels:
  - Software Engineering
---

## What in the World is IntelliJ and ESLint?

IntelliJ is the Java integrated development environment that my software engineering class currently uses to code.  With it, we are given an easier time to write a code and save it to our GitHub in order for other people to see our code.  ESLint is a tool we use in IntelliJ that is designed to check a user's code.  For example, if we use "let" when the item is only used once, it will give us an error message to change "let" to "const" instead.

### Here's the 411

ESLint does not only check to make sure your code is written correctly.  It checks to make sure your code fits it's standards, which I learned are very high.  I have written codes in JavaScript that had no errors and displayed in the console correctly that ESLint would have said were wrong.  The first time I noticed this is when my partner and I were trying to write a simple code where we use the fibonacci sequence for the array [0, 1].  The goal was to print the first hundred numbers in the sequence.  My partner and I quickly figured out the code, but unfortunately, mine showed errors while hers did not.  However, it still printed out the same.  It later turned out that my partner did not have ESLint installed.  We learned quickly that we had to write a code a certain way in order for ESLint to leave us alone.  For example, we couldn't type
```
for(i = 0; i < max; i++){
```
Instead, we were expected to type
```
for (i = 0; i< max; i + 1) {
```
The difference between the two is that the second has spaces around the parentheses and has to increment i by doing i + 1 instead of i++.  Do these changes change the result of my solution?  No, but apparently, it's important to ESLint.

<img class="ui medium right floated rounded image" src="http://img.scoop.it/EpP2iMz2XJ-uLM9dhj4MqDl72eJkfbmt4t8yenImKBVvK0kTmF0xjctABnaLJIm9">
### What Does This Mean?
Would I rather work without ESLint?  Yes.  However, I do think ESLint is a useful tool.  While it's desire to be nit-picky makes me roll my eyes, it needs to be like that.  By doing so, it helps me to stop making common errors that may not do anything to what my code print in order to become a better software engineer.  For all of my computer science classes, I have learned it's better to write a code as nit-picky as possible.  I have not been doing that so maybe now I can get into that good habit.
