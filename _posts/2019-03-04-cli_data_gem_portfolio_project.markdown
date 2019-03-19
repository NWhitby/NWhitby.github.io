---
layout: post
title:      "CLI Data Gem Portfolio Project"
date:       2019-03-04 11:54:05 -0500
permalink:  cli_data_gem_portfolio_project
---


**The Background**

Originally, my CLI project was centered around etymology and was an application that returned the word of the day and its associated information. It required a lot of refactoring in order to avoid common anti-patterns as well as implement new features. While refactoring and attempting to add new features, I felt that the project was becoming a little too difficult and scaling back didn't seem to be a viable solution at the time. Ultimately, I decided to start anew using another domain. I still plan to return to my previous project for practice and self-learning in the near future.

RandomFacts, my current CLI Data Gem Portfolio project scrapes "The Fact Site" and returns a list of random fun facts for the user's consumption. It's an amusing way to learn obscure, random and interesting information right from the command line.

**The Process**

To begin, I grabbed a paper and pen and casually sketched and pseudocoded the interface and logic of my project. In taking the advice of my educational coach and various sections within Learn, I decided to keep the project very simple while ensuring that I covered all major requirements. 

The CLI uses Nokogiri and Open-Uri to scrape live data from the internet. I decided to use "The Fact Sites Top 100 Random Fun Facts" website as the basis for my external data. The site is well structured, easy to navigate, and most importantly, scrapeable. Now that I had my website and an idea of how I wanted my project to look and function, it was time to begin coding. 

For starters, I used Bundler to generate the project structure for my Ruby gem. I'd never used Bundler before, so there was a slight learning curve in seeing all the new files and directories. I struggled a bit with understanding and setting up my environment, so I took some time to read a few tutorials and familiarize myself with all of the happenings. I think this was one of the most important aspects of my project because it made moving forward a lot less overwhelming. 

Next, I proceeded to watch Avi's CLI Data Gem Walkthrough (which was superbly helpful), as well as clone and play around with the recommended student projects.  I also watched the refactoring walkthrough's to make sure that I was keeping with OOP Ruby best practices. 

I took some time to really think about Object Oriented principles and relationships and how I would need to iterate over a collection of objects (an aspect that was missing from my 1st idea). I then proceeded to code my cli class, scraper, and fact class. This time around, I separated concerns by placing the logic and data in their associated classes. It's much clearer and more concise to allow the scraper class to handle scraping the site, leaving the fact class to focus on fact instances. After some time and (various helpful errors), I had a working web application.

RandomFacts CLI displays a welcome message to the user and numbered titles of fun facts that the user can select. In a menu-style choice, the user is able to enter the number associated with a given fun fact, which will return detailed information (a more in-depth summary) about the fact. The CLI also has an option for redisplaying the list of facts, as well as a message that prompts the user when an invalid selection occurs. Upon exiting, a thank you message is displayed.

RandomFacts is currently an unpublished gem, but I have researched regarding how to build/publish a ruby gem and I feel confident that I will be able to move forward in that process should I decide to in the future. 

**Final Thoughts**

Overall, I'm very pleased and proud of my project. This was my first introduction to the back-end and programming/designing, essentially, from "scratch." I believe that I have a better grasp of OO programming and I'm finding it easier to understand/visualize why we program in an object-oriented paradigm. 

Having the freedom to code an application that is of interest to yourself is pretty cool. I hope those who use the CLI have as much fun discovering random facts as I do. 

 









 









