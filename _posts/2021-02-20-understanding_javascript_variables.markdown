---
layout: post
title:      "Understanding JavaScript Variables"
date:       2021-02-20 16:43:20 +0000
permalink:  understanding_javascript_variables
---


This week, my cohort moved on to the JavaScript section and aside from completing the lessons back in bootcamp, this language is basically brand new to me. Many of the concepts are the same in terms of arrays, variables and defining functions. However, from what I've noticed so far, JavaScript isn't as readable as Ruby at first glance and the syntax looks more complicated. 

I want to discuss one of the new things that I found interesting from the basics of JavaScript. In Ruby, if we wanted to define a variable, we could simply write something like ' person = "Jason" ' or 'person = Person.new'. Defining variables in Ruby is pretty straightforward for the most part. After completing the first couple of sections in JavaScript, there are a few ways to accomplish this task using this language. When JavaScript was originally released, a variable was only declared by using *var*. This worked for a while but it proved to not be ideal for all situations. In 2015, a new version of JavaScript was released and included a way to declare variables by using "let" and "const". These allowed developers to have more flexibility with declaring variables. Ultimately, we use "let" to be able to set a temporary value to a variable, if we want the value to change. For example, if we are using a for loop and we want to use a variable for a counter when iterating over a data collection, we would want to use "let". On the other hand, if we wanted to declare a variable and ensure that the value of it does not change, we will want to use const. When a variable is defined in JavaScript, it should look something like, 'let number = 1' or 'const cities = ["New York City", "Los Angeles", "Chicago"]'.

Although I am just starting this new section, I thought it was interesting to examine the difference between these two declaration types. I know that in Ruby, there were also variables called constants which would operate the same way as const does here. I didn't use those too often but I wonder if I will use them more in JavaScript. I am excited to start learning this language now that I have the experience under my belt from the first three sections.
