---
layout: post
title:      "CLI Data Gem Portfolio Project"
date:       2019-03-04 11:54:05 -0500
permalink:  cli_data_gem_portfolio_project
---


**The Background**

I have always been fascinated by etymology. Words allow us to communicate and express ourselves to others. As a shy and introverted kid, vocabulary was my best friend. The internal friend that was always there and one that I desired to get to know better. I would sit for hours at a time, reading books, writing and creating my own short stories. Often, I'd come along a word that was a little too big for me, one that I did not recognize. I'd go to my mom and ask her for information about the word and she would lovingly point me in the direction of the family dictionary.  Thus, started my love of all things dictionary and the tremendous power it unlocks. 

Before reaching the CLI Data Gem Portfolio project, I already knew that, in some way, my project would be centered around learning and vocabulary. Throughout my life, I've been going to various dictionary websites to look up the word of the day. It's been a fun way to learn something beneficial that would quickly translate to my everyday life. I decided that a word of the day CLI would be both fun and interesting as my personal project. 

**The Process**

To begin, I grabbed a paper and pen and casually sketched and pseudocoded the interface and logic of my project. In taking the advice of my educational coach and various sections within Learn.co, I decided to keep the project very simple. Sure, my head was buzzing with ideas. But I knew that meeting the minimum project requirements would be most important as I could expand my project with refactoring and new features at a later date. At this time, priority number 1 was a working project.

The CLI project uses Nokogiri and Open-Uri to scrape live data from the internet. I decided to use Merriam Webster's word of the day website as the basis for my external data. The site is well structured, easy to navigate, consistent, and most importantly, scrapeable. Now that I had my website and an idea of how I wanted my project to look and function, it was time to begin coding. 

For starters, I used Bundler to generate the project structure for my Ruby gem. I'd never used Bundler before, so there was a slight learning curve in seeing all the new files and directories. I struggled a bit with understanding and setting up my environment, so I took some time to read a few tutorials and familiarize myself with all of the happenings. I think this was one of the most important aspects of my project because it made moving forward a lot more concise and a lot less overwhelming. 

Next, I proceeded to watch Avi's CLI Data Gem Walkthrough (which was superbly helpful), as well as clone and play around with the recommended student projects. These steps were informative because they gave me suggestions for structuring my CLI but also a little daunting (momentarily) because my project didn't function exactly like the examples. I found myself scaling up when I should have been scaling back and it was at this point that I gained more clarity.

My idea was now simpler and the site I was using was created in such a way that I wouldn't need to iterate over a collection of objects nor create too many classes. I took some time to really think about Object Oriented principles and relationships. I believe I was unknowingly over complicating my project by forcing a "has many" and "has many through" relationship where it wasn't actually needed. Realizing that I would be displaying the day's word and returning information about the word, I figured it would be best to have one word.rb scraper class and a cli.rb class. I proceeded to code both classes and after some time and (various helpful errors), I had a working web application.

The WordOfTheDay CLI displays a welcome message to the user, the current date, and the current word of the day. In menu-style choices, the user is able to enter a number to request and view more detailed information such as the words "part of speech", pronunciation, definition, did you know (fun facts about the word), 2 examples of word usage, and redisplay the word. The CLI also has an option for redisplaying the menu and a message that prompts the user when an invalid selection occurs. Upon exiting, a message is displayed, welcoming the user to return for tomorrow's word of the day. 

It is currently an unpublished gem, but I have researched regarding how to build/publish a ruby gem and I feel confident that I will be able to move forward in that process should I decide to in the future. 

**Final Thoughts**

Overall, I'm very pleased and proud of my project. This was my first introduction to the back-end and programming/designing, essentially, from "scratch." 

Although it has a simple design, it took well over a week of planning and figuring and is a true labor of love. Having the freedom to code an application that is of interest to yourself is pretty cool. I hope those who use it have as much fun learning about new words as I do.  

 









