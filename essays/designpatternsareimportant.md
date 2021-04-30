---
layout: essay
type: essay
title: Design Patterns are Important
# All dates must be YYYY-MM-DD format!
date: 2021-04-29
labels:
  - Design Patterns
  - Software Engineering
---

## The Problem with Problems

If you were given 100 problems that were exactly the same, would you rather do it individually everytime, or find a solution the first time so that when you occur the problem again you won't have to go through all the work to get the same answer? 99.9% of people would want the second option. That is where design patterns come in. Design patterns are solutions to common problems that are occured in programming. IT can save a lot of time doing because without it, you would have to change the code over and over again whereas if you implemented a design pattern, which will do the work for you. 

<img class="ui medium right floated rounded image" src="../images/uhcodesubmissions.png">

## UH Code Submissions

For my final project, I and 3 of my classmates created a website called [UH Code Submissions](https://uh-code-submissions.github.io/). This website was designed for the PANDA club to use. Basically, it is a website that Computer Science students can practice coding problems that might come up in interviews. Its a great way for students to get practice with answering questions that might be asked. In our website, we have a profile page for the user, a problems page where they can see all of the problems that they can answer, and a solutions page where they can answer the selected questions. On the other side the admin get a bunch of pages like a profile page, a submit new problems page where they can add new problems to the problems page, and problems page (separate from the users problem page) where they can edit the problems if they find an error or what to change it.

## The Use of Design Patterns in Our Website

At the start of making our website I didn't know what design patterns were. Now with a bit of understanding, I can see that I've been using some patterns all along. For instance, my group was using the observer pattern. The observer pattern is when a single object is change, all other object are notified and they change automatically. You can see this when a student signs-up for the website or when the admin submits a new problem. Also we used the singleton pattern. The singleton pattern is when a class or an object can be used anywhere in our program. An example of this from our website would be the collections where we store 

## Avoid Anti Patterns

Design patterns are very important if you want to make a sucessful project, especially if it will be used for a long time after it is made. This is due to anti patterns. Anti patterns are patterns that aren't very helpful or wrong to the point where if you changed it, it could break your whole program. The one example of anti patterns that we were taught was lava flow. This is when there is dead code in your program and it just sits there. No one wants to touch it because its been there for so long that they don't want to break something so they leave it there. This is very bad and should be avoided if at all possible.

