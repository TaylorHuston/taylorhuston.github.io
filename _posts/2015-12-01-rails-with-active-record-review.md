---
layout: post
title: Rails with Active Record and Action Pack - Review
categories: 
- Review
tags: 
- Rails
published: true
comments: true
---

This is a review of the first course <a href="https://www.coursera.org/specializations/full-stack" target="_blank">Ruby on Rails Web Development Specialization</a>, titled 'Rails with Active Record and Action Pack'.

Second course in the specialization, focusing mainly on Active Record and interacting with the database.

Module 1: Kind of just an overview of how Rails interacts with a database. Also introduces scaffolding but (IMHO) doesn't really do a good job of explaining WHY you would use scaffolding vs just generating the models, controllers, etc by hand. I had to do my own research on the Rails documentation as to what scaffolding actually did vs the other generators. Introduced migrations, SQLite, and some basic SQL commands and concepts. Basic CRUD operations via Rails. It also BRIEFLY covers some advanced-ish Ruby concepts, like dynamic and ghost methods (which are the terms used in the video, not sure if they are correct). While these aren't super complicated concepts, if you're coming from a C-Style background, this brief overview of them probably isn't enough, and most people will have to do some more reading up on them outside of what's covered in the lecture videos.

Module 2: Followed up on most of the concepts from week 1. Touched on SQL injection and some other semi-advanced topics. Showed how to seed a database. Introduced the concepts of the different kinds of relationships (one-to-one, one-to-many, etc) that models can have in Rails. Introduced data validations.

Module 3: Introduction to the basic RESTful actions and how a default Rails Scaffold implements them. Also introduces partials. Pretty short module overall.

Module 4: Last module introduces the very basic concept of security and authorization. I wish it would have gone into greater detail, maybe talked about Devise for example.

Overall I found this course to be very well put together and a nice build upon the previous class. Note how I broke it up into modules, and not weeks. That's because, while the modules are designed to be done one per week, there's really nothing enforcing that. All of the assignments come with an rspec file. You do the tasks and work your way through until you pass all the tests. Since you can do this anytime, the assignment deadlines are really more of a suggestion than a rule. You can really do all of the modules at any time before the course ends. And on that topic, still not sold on if the class is worth the $79. In this case, like I said, all of the assignments come with an rspec file. Now if you've paid for the course, you can also upload your assignment to the server where it (I assume) runs it against the same rspec file. But as long as you passed all of the tests locally, you should pass all of the tests on the server, making it kind of a pointless step. The only other problem I had with the course is there were many cases where the professor would run something from the command like, then jump to a file, and there would already be a bunch of code in the file. This would give the impression that this code should have been generated by the command the professor had just run. If you were following along with the example and building the app on your own, it would be easy to be confused as to why your file didn't already have that code in it and naturally you would assume you did something wrong. Now in reality, this was code that you did have to add on your own and the professor had just skipped that step, which I think should have been made a bit more clear.

The other thing, and this applies to all of these courses in general, is nothing in here teaches you enough to just be 'ready' to go out and start developing on your own. It's like a college lecture. It's a good overiew, a good introduction to topics, but you still have to learn beyond it. If something is mentioned in the lecture you NEED to go out and read documentation on that thing to fill in the gaps in your knowledge. These relatively short lectures can't possibly be even close to enough to teach you everything you know. 