---
layout: post
title:      "What I learned from my Rails project"
date:       2019-05-21 21:52:24 +0000
permalink:  what_i_learned_from_my_rails_project
---


Before I go into what I learned, I want to go through the issues that I faced. My rails project is called MacroMeals, a web app to create recipes. It wasn't my first project. I had been working on a different project for 4 or 5 days before I scrapped it and started on MacroMeals. I decided to use Devise and spent 2 to 3 days setting up and debugging. I took notes on the steps for setting up Devise with Omniauth and will write a blog post about it. I also had to delete my virtual machine and install linux again because I had issues with Ruby versions and a whole bunch or crazy bugs. Anyways, here is what I learned from working on my Rails project.

Take Notes 

Taking notes helps more than you would think. Writing code isn't just about typing lines of code, there's a design aspect to it. Thinking  and writing about what models I wanted, what attributes they needed, their relationships helped out to avoid any headaches later on during the development of the app. Planning out what models you want along with the attribues and relationship cements the path that you should head towards. This was one of the reasons I abandoned my first project.  Even if you dont get every attribute you need or have a different data type for an attribute, having the foundations along with the correct relationships makes it easier to make changes later on. This leads to another lesson I learned. 

Don't think ahead

While thinking about my models I found it helpful to only focus on that. When I was working on my first project I would jump all over the place. Create a model, create a controller for the model, add some styling, this approach doesn't work for me. I found it helpful to only focus on one step at a time and worry about the next step when the time comes. If I'm working on login in a user I wouldn't think about passwords. I would make sure the login works before I start worrying about anything else. I would run into bugs If i would try to do too much at once, which leads to one of the most important things I learned. 

Tests are awesome 

There's people that hate tests and people that love them. Ruby is an interpreted language. You won't know of any bugs until that line of code is run. Tests help to make sure everything is working as intended and nothing broke while making changes or adding code. There's another helpful feature of writing tests. It forces you to think about the code you want while writing test code.  If you are writing code to validate your user's username isn't blank, you will think about the steps neccessary to pass the test before even writing code. You are writing the code you wish you had. (These aren't Avi's exact words but this is basically what he said) Tests also help prevent bugs. Often I would start writing code and wonder why my test was failing only to realise I had a logic error. The code looked fine first glance but it would have been a pain trying to figure out what was wrong. Often times I would add a feature and some of my tests would break. Without tests I would not have known about bugs until I encountered it on the browser. I love tests and do not regret the time I spent learning how to test and the time I spent writing tests for my project. 

This project took longer than I wanted to with all the set backs I had. The tests I had to write also took time but it was worth it. If I had to do it all over again I wouldn't change a thing. I learned a lot  despite the headaches. Programming is hard, but it's definitely rewarding. 
