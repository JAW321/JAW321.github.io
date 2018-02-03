---
title: BuzzFeed Quiz
layout: post
author: james.watson
permalink: /buzzfeed-quiz/
source-id: 1yEWzjQWOoudySWPPviEKzjmQUxUrbRgE0Y-xcf4Wt8k
published: true
---
Date: 29/1/18

Today we all went to the front of the class to get started with our quiz. The teacher gave us some helpful points. He wrote this onto his repl.it,

**def a_new_function(a):**

**print("Answer this question")**

**return input(a)**

This means that when you run the code it defines a function which is a and when it returns the input to what you have the computer to print it will assign that to a_new_function.

**def main():**

**array = []**

**array.append(a_new_function(1))**

**array.append(a_new_function(2))**

**array.append(a_new_function(3))**

**array.append(a_new_function(4))**

**print(array)**

**scores = analyse(array)**

**print("Your final score is {}".format(scores))**

Next we wrote this. This mant there was now 4 functions which I could change for the amount of questions I have. Then underneath this code a question would be assigned to each of the functions and then depending on your answers to the questions it would return a score.

**def analyse(a):**

**score=0**

**for item in a:**

**if item == "hello":**

**score+=10**

**elif item == "please":**

**score += 20**

**else:**

**print("You smell")**

**return score**

This added up your score depending on the answers to the question and returned a comment depending on how many points you got while answering the questions.

