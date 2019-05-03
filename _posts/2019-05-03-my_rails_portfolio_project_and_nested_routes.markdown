---
layout: post
title:      "My Rails Portfolio project and Nested Routes"
date:       2019-05-03 20:47:31 +0000
permalink:  my_rails_portfolio_project_and_nested_routes
---


My Rails portfolio project was an interesting learning experience. I had all kind of issues to solve with my code, besides sticking to what the requirements are asking you.

I decided to expand my Sinatra project, which is a Financial Institution Rollover App.

I set up three tables, for user, rollover and institutions. Then, three corresponding models, where I established the relationships: a user has many rollovers and many institution through rollovers, a rollover belongs to a user and to an institution, and an institution has many rollovers, and many users through rollovers.

Understanding and applying the nested route to my project was more challenging. Nested resources are used to reflect the has_many relationship between our models in the routes, allowing our code to stay DRY. They give us a way to document that parent/child relationship in our routes and our URLs.

In my case, institutions were the parent (has many rollovers) and rollover the child (belongs to an institution).
First thing you want to start is setting up the nested resource in routes. First thing you want to start is setting up the nested resource in routes. This declaration in routes will also create routes for rollovers, each of which requires the specification of an institution in the URL.

Once we set up the nested resource, we need to update the specific controllor, to handle it. 

Study groups for Rails project preparation were key to the resolution of many of the issues I had, together with all rails documentations online.
 





