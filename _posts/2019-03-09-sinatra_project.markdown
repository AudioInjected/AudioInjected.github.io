---
layout: post
title:      "Sinatra Project"
date:       2019-03-10 00:31:41 +0000
permalink:  sinatra_project
---


One of the suggestions for the Sinatra project was to create an MVC CRUD app to track video games so I went with that. I still have my Nintendo with a bunch of games in the closet so I thought it would be fun.

The hardest part was setting up the structure of the project. I had to look at other labs I did to see what code I was supposed to add to the config ru file. It look longer than needed because I had an issue with sqlite3. Luckily, stackoverflow saved the day. I specified that I wanted sqlite version 1.3.6 (I had 1.4 installed) and I ran 'gem uninstall sqlite3' followed by 'bundle update'. 

I had the structure set up, next it was time to take care of the models. I had a Users table, Games table, Genres table, GameGenres table and GameUsers table. There's a lab before this project where you make a twitter clone so my thought process was still stuck there. Eventually I dropped the GameUsers table because my project was getting more complex than it needed to be. I didn't need to see games owned by all users or view a particular users page and see what game that user owns. I saved the code I got rid of because I plan to add that functionality later on, along with some css for style. 

My app was now simple. I still had the GameGenre tables because a Game can have more than one Genre and a Genre can have more than one game. Coding the routes were easier because the only thing being created, (besides a User when you sign up) read, edited or deleted was a game.  I also added flash messages when a user logs in or out, edits or creates a game. Whenever you enter an incorrect username or password you get an error as well. If you have validations in your model, for example a username must not be blank, you can call the #errors method on that object.  If you enter an incorrect password when trying to authenticate a user, there will be a message that you can display on the view page. Calling full_messages returns an array which you can iterate over to display all the error messages. Flash messages and calling the error method on the object is enough for you handle messages for  different user actions. I also added a route to handle 404 errors. 

Before I started the CLI gem project I was nervous, wondering if I made a mistake enrolling in this bootcamp. I didn't feel this way starting the Sinatra project. I was anxious to get started. If i didn't know something I just looked it up. I'm human, I don't know everything, and I'm not supposed to know everything. I'm supposed to know how to ask the right questions and understand what I'm doing and what I want.
