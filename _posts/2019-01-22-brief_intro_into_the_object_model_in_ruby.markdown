---
layout: post
title:      "Brief Intro into the Object Model in Ruby"
date:       2019-01-23 00:39:22 +0000
permalink:  brief_intro_into_the_object_model_in_ruby
---


Besides studying and working on labs for the Full Stack Web Dev course, I have also been studying stuff outside of the bootcamp. I got a book on Metaprogramming in Ruby and even though I'm only a few chapters in, it made me look at Ruby differently. I will only go into a few things from the begining of the book, otherwise the blog will be too long. If you decide you want to read more about this, then pick up Metaprogramming in Ruby second edition by Paolo Perrotta. Even though I am in the beginning of the book, I have enjoyed what I read so far, 

In Ruby, everything is an object. Objects are instances of classes and classes are blueprints or factories that create each individual object. When we define a class, we can write instance methods and class methods. Instance methods are used by instances of that class, and class methods are used by the class. Here is one thing I didn't know. Instances of classes don't have methods. All they have are instance variables and a reference to a class. Open IRB and create an array and assign it to a variable: 

a = Array.new 

then type 

Array.instance_methods == a.methods 

The return value will be "true" but how? Methods don't live inside instances, there is something called the method lookup chain that will make sense of this. if you create an array and assign it to a variable:

b = Array.new 

then type 

a.methods == b.methods

The return value will be "true"

Methods don't live on instances, if it did then how does array "a" have the same methods as array "b"? The method lives in the class of "a" and "b" as instance methods. When you call a method on an instance, Ruby will look at the class of the object and look for the instance method. If it doesn't find it, Ruby will look at the superclass, which is the parent class of the class and so on until it finds the method. Here's a cool thing I learned. Classes are objects. Class methods on a class are just instance methods of the "Class" class. 

 In Ruby, everything is an Object. All you are doing is calling methods on objects. There is a whole lot more to this, but once you read more into classes, modules, prepend and include, and self, this will make sense. I want to write more about this but again, the blog will be maybe 2 or 3 times longer. This book sparked an interest in Ruby for me and I will continue to learn more about it. Check out the book if you are interested and also see what topics I butchered in the blog. I just started the book after all.
