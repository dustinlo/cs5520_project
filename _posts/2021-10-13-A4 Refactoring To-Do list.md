---
layout: post
title: "Refactoring To-Do list"
date: 2021-10-13
---

# Refactoring To-Do list
## link
[Github Link](https://github.com/dustinlo/NEUSEA-Chih-WeiLo/tree/c79be105c9fcd23a5728323465c807e1376d47d5/TodoApp)

[Updated Github Link](https://github.com/dustinlo/NEUSEA-Chih-WeiLo/tree/bab60d002003a91c692af1a92ca3d98ee762f2ff/TodoApp)

[Android link (Updated on 2021/11/1. Not sure if it's published yet or not.)](https://play.google.com/apps/internaltest/4699446330883803708)

## Screenshot

<img src="https://i.imgur.com/cZPAX4N.jpg" alt="drawing" width="400"/>
 
## What I have done

I have successfully used LiveData, RecyclerView, CardView and ViewModel to display my ToDo list createad and they still persist after I reopened/killed the application. Also, I created the same application layer architecture as shown in class/official website. I have looked up various YouTube tutorials but they were really different from what we are expecting. I basically have re-written this whole application for about 3 to 4 times and in the end, I kind of gave in and follow Adrienne's code.However, I did learn a lot form my  failures.

# What did not work at this point

The update part worked fine in the older version. In this version, I have been debugging for almost 2 days and looked up a tons of posts on StackOverflow but had no luck to solve this issue: I cannot retrieve the list even directly from the repository. The application seems loading the live data just fine but when I try to access the list, I always get null pointer which meaning it is not fetching the right list at all. I will consult to Adrienne or maybe look up more tutorials to see if I am able to resolve this issue.


# Update

This has been cleaned up and now it is functioning as it should be. I removed the part which I used ViewModel because I am using two different activities to show and create the todo. After long hours of research, I figured it is not the best practice to use ViewModel to share data between two different activities. If I want to use ViewModel, I shall be changing the adding todo part to be using fragment. I feel sharing data using ViewModel between two activities is an anti-pattern and has no difference between preserving data by using only the repository class. 

