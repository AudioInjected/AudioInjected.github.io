---
layout: post
title:      "My final project, with some sighs"
date:       2019-10-10 19:44:57 -0400
permalink:  my_final_project_with_some_sighs
---


This isn't a  technical blog, it's more about my thoughts during and after the project. My final project at Flatiron school is a CRUD app with Rails in the backend and React/Redux in the front. It's sort of a Craiglist clone but for guitars. You create a post with details on the guitar such as model, spec and price and you can view guitars users are selling and email the seller of the guitar. 

Before I get into my thoughts on the project, here's a quote that sums of my feelings towards my project.

"O then if in my lagging lines you miss	
The roll, the rise, the carol, the creation,	
My winter world, that scarcely breathes that bliss	
Now, yields you, with some sighs, our explanation." 

Gerard Manley Hopkins - 51. To R.B

I worked hard on this project, no one can take that away from me. I have over 250 commits as of now. I learned so much and struggled many times during this project. Since this isn't going to be a technical blog, I'll go over the project and give my thoughts on it. 

The very first thing I did, before writing any code, before creating a repo on github, I planned out my project. I created a notes file and planned out everything, starting with the back end. Writing notes helped plan out what I needed and what I was going to do. For example, I wrote the models that I needed, the relationships, what validations I was going to add, and I added a note to add tests. This doesn't mean that I covered everything, if there was something that I thought of and  didn't have anything in my notes, I will write into my notes what I was going to do next. 

After I wrote some notes, I started with the back end. I created an API with rails and wrote tests for my models and my controllers which renders JSON data. I didn't run into much trouble here. It took time because my project is a CRUD app so I had to write that functionality, plus the tests for it. The headaches came when I started working on the front end. 

The front end consists of React/Redux. This is where the struggle started. I wrote tests for the back end so I wanted to do the same for the front. I tried using jest with puppeteer to write end to end tests. I spent two days looking at documentation, messing with code and looking at StackOverflow posts. I finally got it working, only to scrap it in the end. As of now I only have tests for my reducers but I will add more tests later on. Another issue I faced with React/Redux in the front end is components rendering without waiting for the Redux store. This isn't an issue when clicking links in the app, the issue surfaces when going to the route directly from the browser including page refreshes. This issue doesn't take away any functionality of the app, it's just not a good user experience.

My app does not look good. I used boostrap which allowed me to do some quick styling but it needs a lot of work. I am not a design person. I find design difficult. It requires a different way of thinking compared to programming. Design is my weakest area and eventually I would like to take a UX/UI course to strengthen that area. 

This post isn't meant to just mention my struggles. I will continue to face challenges, I will continue to struggle, but I will continue to grow. The quote that I put towards the beginning captures how I feel about my project. I am not happy with it. This is supposed to be my highlight of my training at Flatiron and this is all that I have to show for it. I present this project with sighs, but this is motivation for me to become better. 
