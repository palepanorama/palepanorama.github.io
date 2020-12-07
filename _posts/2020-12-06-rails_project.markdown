---
layout: post
title:      "Rails Project "
date:       2020-12-07 03:28:10 +0000
permalink:  rails_project
---


What a learning experience this project has been! It seems I truly nail down and understand the material we cover when I am forced to build these projects from the ground up. From the time I began building this app, I knew I wanted it to be centered around football since watching it takes up so much of my time during the fall (whether these games ought to be held at all in the midst of a pandemic is another matter entirely.) Originally, I intended to build a roster of my favorite team, the Auburn University Tigers, containing a full and accurate roster. Once I looked up the Auburn roster and saw that there are 85 scholarship players, not to mention walk-ons, I decided against that route - besides, I thought, that app already exists! 

So instead I decided to build an application which would allow someone to create their own football team, creating players which belong to specific position groups. Players would belong to users and positions, while a user would have many positions through players and a position would have many users through players. I used the omniauth-github gem to allow users to login with their GitHub accounts, or they could create an account with an email and password. Upon logging in, users are greeted and given three different prompts: to create a new player, create a new position, or view their team as it currently stands. Players and positions must have input for their names to be validated. To create a player, users must give a name, select a position from a dropdown box, then check a box certifying they want that player to be added to their team. Creating a position requires the user to submit a name for that position, which then appears within the dropdown box when creating a player. Users are then able to view the players they have assembled on their team and what positions they play. If given more time, I would like to limit team size to 24 (enough to fill out an entire offense, defense, plus a kicker and punter) and give users an account of exactly how many players they had and what positions they lacked.

As this project week comes to close, I am encouraged by the progress I continue to make. So much of my learning in this course has come from actually creating these projects and I grow more and more proud with every project. 


