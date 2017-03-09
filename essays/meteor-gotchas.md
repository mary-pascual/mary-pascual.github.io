---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

# Meteor: What's It's Issue?

Many times when a user first uses a new program, he faces many issues.  Some turn out to be a simple issue that can be fixed easily while others take more research in order to be fixed.  The same could be said about me when I first used Meteor.  While researching Meteor, I learned that Meteor is sometimes not Windows friendly, which worried me since my laptop ran on Windows.  It also caused me to always think that whenever I had an issue it was because I was running Meteor on a PC and not because of a simple issue.

## Issue #1: Is it the Computer, Is it the Package, Or Is it Me?

The first issue I faced was trying to invoke a "meteor --settings ../config/settings.development.json" in my command line.  Because the professor provided a video tutorial, I was aware of the amount of time it needed to take to run, which was about a few minutes.  Knowing that, I was horrified when thrity minutes passed by, and the screen didn't change.  It was still extracting meteor tools.

I started to panic, and my first thought was to just go to my task manager and shut down everything that was running (including my McAfee application).  Though I could tell it was starting to run a little faster, I was still convinced that my computer was stuck on extracting meteor tools.  Frustrated, I left my computer for a few hours because I decided that I was done with my useless laptop.  However, when I finally calmed down and came back, I was surprised to see that it was done running.  My mistake was thinking that my laptop was stuck when in actuality, it was just taking a long time to run!

As said before in my other essays, I am a type A, and therefore, if one thing goes wrong, I have a breakdown.  I had a breakdown over this simple situation.  Even though I don't know what caused the package to take that long to run, I do know now that if I had the patience, everything would've worked itself out.

## Issue #2: So Picky!

Another issue I faced was trying to get my home-page.html to get it's data from Contacts.js instead of putting the data in the html page itself.  However, when I deleted the contacts in my home-page.html and put that it needed to get the data from Contacts.js instead, I got a blank page.  I freaked out.  How was I supposed to get all my data back?  I tried to double check everything, but everything seemed fine.  I looked at the solution, but it seemed to be exactly alike.  However, then I discovered this:

{{#each contact in contactList}} 

It's a small thing, but it turned out that I accidentally called for "contactList", when I actually named it contactsList!  I spent hours on something that was a small error!
