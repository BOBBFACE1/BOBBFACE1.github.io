---
title: Creating a Buzzfeed Quiz
layout: post
author: joe.burton
permalink: /creating-a-buzzfeed-quiz/
source-id: 1nkuHhFkcb_6TAftaIE4xn9jsas6-wYtV1lGiLF8jzHw
published: true
---
Our final project of this year is to create a Buzzfeed - style quiz, that will ask you a series of questions, and tell you something about yourself at the end. I decided to make my quiz "Which Star Wars Species Are You?". The first thing we did was to write eight or more questions for the quiz to contain, each with a number of options. For each of these options on each of the questions, I then assigned the different end results that each answer would give points toward. Once this was completed, we started the code on repl.it in python3. Each question required the answer to be stored, so I used the “input” function, with the input being the reply to the question, in which I also included the possible answers that they could choose. This would then be the value of a variable with a name of answer (question number) e.g answer1. There was then a series of an “if” and “elifs”, which would each check if one of the multiple choice answers had been picked, and then adding value to the required variables, in this case Star Wars species. After these would be an else which said that the answer was not valid. After this, the question needed to be asked again, so I put the entire chunk of code for the question in a “while True” loop, and added breaks in each  of the ifs. I then repeated this for the ten questions. The next step is to use the points each of the species variables contains, to give a species that they are most like.

