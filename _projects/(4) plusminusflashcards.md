---
name: Plus/Minus Flashcards
tools: [Articulate Storyline]
image: /flashcards/plus.png
description: Digitalized version of flashcards used to aid early childhood development.
---
# **Plus/Minus Flashcards**
##### An interactive digitalized version of flashcards used to aid early childhood development.

<br>

{% capture carousel_images %}
/flashcards/plus.png
/flashcards/cor.png
/flashcards/inc.png
{% endcapture %}
{% include elements/carousel.html %}

<center> {% include elements/button.html link="https://markyilxd.s3-us-west-1.amazonaws.com/plusMinusFlashcards/story.html" text="View the Project" %} </center>

<br>

## Development Summary

- **Made with:** Articulate Storyline 360
- **Time in Development:** ~8 hours
- **Responsibilities:** LX Design, Graphic Design, Development

<br>

## Overview

For much of my mathematics education, I was memorizing math facts. Whether it was through flashcards or through timed tests, I would practice math facts and needed my teachers to provide me more material. 

Many children become acclamated to technology at a very young age. My adolescence was filled with those flashcards and timed tests but they were all on paper. Children are growing up in a new world where they are surrounded by technology and are incredibly technologically savvy.

<br>

## Challenge

New times call for new resources. It only makes sense that pencil and paper will be boring for a student that has grown up with much more engaging stimulus. Old flashcards require students to sit in place and feel idle while the person in front of them is changing cards after card. The learner has no feeling being in charge of their own learning.

<br>

## Goal

Create an interactive flashcard game which puts the learner at the center of the experience.

<br>

## Design 

Audience: Students learning addition and subtraction facts.

An issue I found with traditional flashcards and math fact sheets was that I always had to replace them. A page of number facts only lasted a minute and I did not have a way of continuously making new problems. I wanted these flashcards to provide an infinite number of problems that the learner could practice with.

The goal required students to be in control of their own experience and so I wanted students to be able to choose simply between their options. There would be no need for a facilitator in their learning and so the flashcards would be self-correcting.

I had two designs that I ended up with:
1. The student would input their own answer.
2. The student would choose whether the answer was correct or not.

The first option presented a more traditional approach to the flashcards. Also, the first option puts a lot of pressure on a student to input an answer. I found the second option to require more from the learner in a less intimidating way however. The second option only required the learner to pick "YES" or "NO". This requires the student to know the answer AND recognize if the answer is right or wrong. There are fewer decisions that the learner must make while processing more information.

<br>

## Development

Storyline 360 was used to develop the flashcards. With my programming experience, I recognized a lot of potential in the random number variable that Storyline has. The left side of the equation used two variables that ouputted random numbers from 0-12. The right side gave a random number 0-24. There were initially two options for problems: addition and subtraction.

However, the development was not so simple.

**Issue 1:**

Since the left side of the equation was random, subtraction problems could result in negative numbers. 

**Solution 1:**

A conditional statement was placed so that if the second number was larger than the first, a larger number would replace the first so that negatives would not show up.

**Issue 2:**

Since the right side was also random, there was only a 1/24 chance that the equation would actually be correct. The learner's experience would be negatively impacted as there should be an equal chance between right and wrong. 

**Solution 2:**

Two extra options for potential problems were added where addition is always right and where subtraction is always right. That means there was a 1/4 chance for each of the problem options (random addition, random subtraction, always true addition, always true subtraction). This provided a nearly equal distribution between true and false problems.

<br>

___

