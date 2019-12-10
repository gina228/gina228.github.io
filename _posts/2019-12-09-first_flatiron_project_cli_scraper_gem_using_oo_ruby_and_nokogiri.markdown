---
layout: post
title:      "First Flatiron Project! CLI scraper gem using OO Ruby and Nokogiri"
date:       2019-12-10 03:21:33 +0000
permalink:  first_flatiron_project_cli_scraper_gem_using_oo_ruby_and_nokogiri
---


The first project at Flatiron school, what a task! I had an...interesting time working on it for the past couple of weeks. I'll admit, I restarted this project about 5 different times. I started with trying to work with an API, but I just wasn't quite grasping it. So after a few tries and a few different repositories, I decided on a scraper that scrapes a web page for cool facts about dogs!

Before I get into my actual project...

**What is Nokogiri?**

Nokogiri is a ruby gem that describes itself as an “HTML, XML, SAX, and Reader parser.” In other words: It will serve almost all of our HTML scraping needs .

**What is web scraping, and why do we need it?**

Scraping is the process of taking output that was originally intended to be human readable and extracting data from it so you can use that data in your program. We data scrape to extract data from something that is not providing information that we need — where no API or RSS feed is available to give us raw information.

Now, into the project!

**Overview of the application**

One of the most challenging tasks for me as a new programmer was to scrape a website with hierarchical structure and nested data that are linked to external pages. I definitely tried that a few times, but ended up going with a much simpler page with mostly headlines and paragraphs. The application I built gives a list of fun facts about dogs, and when selected, gives more information about that fun fact. I used an Object-Oriented programing Ruby to build this application.

**Step 1: Planning**

Before getting into planning my own project, I looked into past projects from both students and instructors. I watched a  project code-along by Avi Flobaum called Daily Deals. This video helped me essentially set up my own project. I definitely looked up other students projects and their coding process on Youtube and spent hours watching these videos. I also looked through project repos on github. I wanted to see how they defined their classes and methods, and how they distributed the responsibilities of each. This all helped me to start forming my own plan for my project.

**Step 2: Starting the project**

Now that I had a pretty good idea of how to start defining classes and methods for my project, it was time to start building. I watched another video of someone at Flatiron school explaining how to start a gem. They had said to use Bundler, so I used bundle gem fun_dog_facts to create the shell of my gem. Tip: I found out to use underscores instead of dashes, because dashes kind of messed up the name of my classes. 

At this point, the most important task was getting all the files to connect and communicate with one another so that my code could run from the terminal. I went back and watched Daily Deal (many times) on how to get started from the gem shell that Bundler creates. I watched Avi and followed along as he started his project and worked through and debugged the initial steps of requiring the proper files and creating the necessary connections to start the project.

**Step 3: Finding a site to scrape**

Before working on my scraper, I needed to find a website that would provide me with the necessary information I needed on fun dog facts. I wanted to make sure the website wasn't too complicated, as I was having a bit of trouble getting going with these projects and time was running out. Tip: Make sure a website is able to be scraped by putting/robots.txt at the end of the url, I found that some sites were not able to be scraped way after I had built a class and methods for them. 

**Step 4: Code, code, code**

Next, I began to figure out and code all of my classes and methods so that they would work together and function as a single machine. Code, test, fix, repeat. I'd code something to add a new method or feature to a class, and then I would go to my terminal to run my program to see if the feature worked. It was always such a relief when it worked! Much more often, it did not work, and I would have to go back and fix the method, often using debugging tools such as pry. Eventually, after many hours of working, all the functionality was complete and working.

**Step 5: Work out the kinks**

In terms of coding, the final step for me was to polish the user interface and experience, at least as much as I could for a simple command line interface gem. At the same, time I did not want to spend too much time on this, as this was not necessarily a requirement for the project. I worked hard on this and I feel it is still a bit messy. I still have some work to do in this aspect, as I know that the code and understanding are a bit more important than a pristine looking interface, at least on the first project. I will probably update this blog as I get my project reviewed and code refactored to look prettier :)

This first project was definitely a learning experience., from applying object-oriented programming fundamentals to learning how to start and publish a ruby gem. I have not published the gem, as I feel I still have some work to do on it. I would love to eventually submit it to say that I did. 

If you’d like to check out my github repo:

https://github.com/gina228/fun_dog_facts.git

Feedback and constructive criticism are always welcomed!

