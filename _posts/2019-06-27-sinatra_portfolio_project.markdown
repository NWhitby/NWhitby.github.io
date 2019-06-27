---
layout: post
title:      "Sinatra Portfolio Project"
date:       2019-06-27 16:53:23 +0000
permalink:  sinatra_portfolio_project
---


**The Background**

For my second project, I was expected to create a CRUD/MVC app using Sinatra. The app was to be centered around tracking something that was important to me. I couldn't think of any physical things or collectibles that I'd like to track. However, I do love reading and writing and tend to keep a fair amount of notes and lists around me. With that in mind, I decided that a simple note taking app would be perfect and beneficial. 

I titled the app "DigiNote", meaning, a digital version of a written note. DigiNote allows a user to create a new account, authenticate the user and log the user in and out. Once in, users can give their notes a title, as well as create, read, update, and delete their notes. 

**The Process**

To begin, I created a quick mockup denoting how I would like the application to function. This process was a lot easier than my last project because I learned to keep things much simpler (for starters) this time around. Adding new features would probably be easier than subtracting what was already present within the code. 

Next, I attempted to build my projects directory structure from scratch. While this was a great learning experience, I hit a few road bumps along the way and found this setup to be unnecessarily tedious. Midway through structuring the files, I remembered the "Corneal" gem, which was mentioned during my planning meeting. I decided to scratch what I was doing and go with Corneal.  Doing this made getting started much easier, as all the necessary files and settings were provided. Just seeing the available files and folders was incredibly motivating and encouraging.

As for my project, it would need to keep track of a given user and that user's notes. I realized that I would need a users and notes table in the database, users and notes controllers, as well as a user and note model.  I was already familiar with this process thanks to the previous lessons and labs. 

Keeping the models simple made it easier to create the has_many and belongs_to relationships between the notes and user. Once I had a functioning app, I seeded the database to ensure that data was present and actionable upon Active Records provided querying methods. 

When it came time to validate incoming data, I felt a bit unsure. Validation was one of those topics that I had to go back and research further. After I became more aware of the validation helper methods available through Active Record, I added them to the user class, as this model handled the most pertinent and sensitive information. Valid data would be crucial. 

One of the cooler aspects of this project was the opportunity to dabble in HTML and CSS and have something graphical before me. I didn't change much by way of the user interface and design from what was provided by the Corneal gem, as I wanted to keep the app simple and minimalistic. I also didn't incorporate the use of sinatra-flash within the project, but I did learn to use it. I felt that the redirection of views after a given action was intuitive enough and didn't want promptings to become redundant to the user.  However, I can see how it would be beneficial in a more complex application. 

I believe I spent the most time debugging the routes in my controllers and making sure erb templates were responding with the proper views and information after requests. 

**Final Thoughts**

Overall, I'm happy with my project, as I believe it covers the requirements and is something I can use on a daily basis to keep track of my own writings.  In the near future, I'd like to play around with the design and add more features. 

Since creating my Sinatra app, I have a much better understanding of how frameworks are used on the back end of the web and a better grasp of CRUD, MVC, HTTP, and restful routing.
