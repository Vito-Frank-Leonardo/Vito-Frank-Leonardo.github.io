---
layout: post
title: Thoughts about Project 1 from ST558!
---

### What I did

In this project, I created a vignette detailing how I created functions to access the NHL Records/Stats API and pull the data into R. In the vignette, I also performed an exploratory data analysis of the data that I accessed in order to show how to use the functions and what can be done with the data. I did not find anything too interesting with the data but I did find that using functions to access API's can be a great tool to use in the future. 

### Project Reflection

I found this project slightly tedious and confusing but not quite difficult. At first, I was having trouble accessing the data but after some googling, I found that the `RCurl` function we were taught in class was supposedly 'outdated' so I used the `GET()` and `content()` function from the `httr` instead. The NHL records resource that was provided also mentioned the `GET` function so I hope that I accessed the data correctly: "All queries are prefixed with https://records.nhl.com/site/api and are GET requests unless otherwise noted, so far I have not seen any thing other than GET requests." I also had to clean my functions many times as I got more comfortable with the data and how R was reading it. Overall, I feel now that I have experienced a project like this, it will make accessing other API's much easier. API's are the most confusing part of this course for me thus far so I will try to practice by accessing data and building models on weekly basis until the end of summer.  

#### What was the most difficult part of the logic and programming for you?

I did not find much of the logic or programming difficult for me. The hardest part was dealing with lists and the levels within the lists. Basically, some of the elements of a list were also lists with elements inside. This was a little tedious because the data was very layered and some of the layers were structured differently. In one function accessing an endpoint, I did not notice that I did not access all the layers of the lists until I was reviewing my results when performing the exploratory analysis. 

#### What would you do differently in approaching a similar project in the future?

If I was doing a similar project in the future, I would not do much different. Hopefully, because I am more experienced now, I would be able to complete the project faster. I would also probably discuss my functions with others to make sure I accessed the data correctly (which I was not able to do for this project). 

### Where to Find the Project

**Github Pages Repo:** [https://vito-frank-leonardo.github.io/ST558-Project1/](https://vito-frank-leonardo.github.io/ST558-Project1/)

**Usual Repo:** [https://github.com/Vito-Frank-Leonardo/ST558-Project1](https://github.com/Vito-Frank-Leonardo/ST558-Project1)

