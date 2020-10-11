---
layout: post
title:      "CLI Project"
date:       2020-10-11 19:52:16 +0000
permalink:  cli_project
---


I have finally finished my Command Line Interface (CLI) project and it has been one of the most satisfying things that I have ever done. Prior to starting the project, I felt overwhelmed with how I would complete it and where to even begin. When I look back on the hard work that I put in during the past two weeks, I'm very happy with how the project turned out.

This project taught me first hand about the full scope of building a basic program. It taught me how I can use data from an API and incorporate it to create a new program. The data used from the API allowed me to take that data and manipulate it in a way that made it useful and relevant for the user. The program facilitated the user's interactions through a CLI by prompting them to enter in different inputs. Finally, I created objects with specific attributes based on the data pulled from the API. When these three key components came together, I truly began to see my project come to life. 

There were definitely areas of this process that I struggled with and needed to think through in order to solve them. One in particular for me was understanding when and when not to call the on the API to extract information. We should not call the API from anywhere other than the API tab in our program. In general, we should make calls to the API as little as possible as this causes our program to work harder to retrieve the data. At first, I made the mistake of calling on the API in my CLI tab (four times in one method to be specific) to define object attributes once a user entered in a specific input. I learned that there was a better way of achieving the same result by also making it easier on my program. I needed to do some refactoring and changed my program to define object attributes all within a single API call. This made much more sense to do because if we make the API call for certain pieces of data one time, we may as well set an object's  attributes in that same call instead of doing it separately in another method.

The inspiration for my project came from something that I had heard on the news months ago. It said that New York State would begin to waive all entrance fees for state parks during the pandemic. In doing this, it encouraged people to visit the parks safely and continue to be active during the lockdown. This gave me the idea to create a program that allowed all Americans to search for National Parks in their home state and give them something fun and exciting to do, while doing it safely. When I came up with the idea for my program, I wanted to tell my coach to see what she thought about it. When she said that this idea had never been used for the project before and that she was excited to see the final project, I knew I was on to something good. This gave me the encouragement to take this idea and run with it. 

I'm very happy with the end result and am proud of myself for working hard during these past two weeks. I hope people will use my program to continue to make fun memories, share new experiences and radiate positivity even during the pandemic. 
