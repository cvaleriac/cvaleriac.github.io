---
layout: post
title:      "Sinatra Portfolio Project "
date:       2019-02-19 14:06:34 +0000
permalink:  sinatra_portfolio_project
---


For my Sinatra CRUD App Portfolio Project, I made an app that allows users to see, edit, create and delete their financial institutions rollovers.
 

The homepage has a welcome message, a sign up and a login link. 

Once you are logged in, you see a link to a list of all your rollovers, which are divided per incoming and outcoming. You can click any of your rollovers to be able to visualize the info (amount, origin, destination bank, and type). Then, you can edit an existing rollover, create a new one or delete.


After installing all the gems needed, like pry, shotgun, sinatra-activerecord, require_all, rake, rack, sinatra, sqlite3, and bcrypt, I create Models and setting up their relationships. 
I went for a simple has_many and belongs_to relationship. User has_many rollovers and rollovers belongs_to user. 

I made sure to add has_secure_password method to User Model to secure user’s password.  I created migrations for user and rollovers.

Then, it was time to create views for users and rollovers (including new, edit, and show) and create the corresponding controllers for both.


This has been a fantastic learning experience, which challenged my knowledge of what I studied till now in the course. Portfolio projects are always a special moment in the course, because it's when you really feels like a developer in front of a blank project, giving you a more realistic idea of what the day-to-day would be!

After this experience, I feel I still have to learn a lot, but manage Sinatra and ActiveRecord much better than before.

