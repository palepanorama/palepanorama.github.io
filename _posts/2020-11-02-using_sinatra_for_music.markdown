---
layout: post
title:      "Using Sinatra for Music "
date:       2020-11-03 03:45:18 +0000
permalink:  using_sinatra_for_music
---


This project felt far more open-ended to me than our previous CLI project. Rather than being limited by the number of relevant APIs out there, it seemed that I could center my web application around nearly anything since I would be creating my own data for it. Eventually, I found myself lost in the infinite- apprehensive about making a choice as it would limit my choices available...oh, the angst! Eventually, I decided upon creating an app that would allow a user to record different their practice time with different musical instruments. Old Blue Eyes would be proud! Users would be able to sign up, login, access their (and only their!) information, create new instances of instruments and time spent practicing them, edit that information, and delete it. 

The Corneal gem was a lifesaver when creating my app. Being able to create an entire MVC structure with a simple command was so much easier than creating all the directories and files from scratch, not to mention the time it saved. I used Corneal to create Users and Instruments scaffolds which set me up with folders for my controllers, models, and views. A user has many instruments and an instrument belongs to a user. From here, it was a process of using my controllers to render views and redirect routes. I struggled at times with writing my ERB files, I suspect that is because it looks so clunky going back and forth between Ruby and HTML. 

I felt a good deal of strain from this project. I was forced to think, rethink, try again, and learn something new every step of the way. I believe that it helped me not just to apply the knowledge and skills I had, but also to understand that knowledge on a deeper level than I previously did. I feel much more confident in my ability to use Sinatra and ActiveRecord to build a functioning web app and I can't wait to see what's waiting in the Rails module of the course! 
