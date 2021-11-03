---
layout: post
title: "Adding notification"
date: 2021-11-02
---

# Adding notification
## link
[Github Link](https://github.com/dustinlo/NEUSEA-Chih-WeiLo/tree/c47c7a4ae531ed7d0827671f973e8e31b2bf3967/TodoApp)

[Android link (Updated on 2021/11/2. Not sure if it's published yet or not.)](https://play.google.com/apps/internaltest/4699446330883803708)

## Screenshot

<img src="https://i.imgur.com/5yuebPA.png" alt="drawing" width="400"/>

<img src="https://i.imgur.com/teyjjlT.png" alt="drawing" width="400"/>
 
## What I have done
I have completed the feature to add notifications. I have actaully been spending my time refining A4 the past few weeks. Adding notifications did not result hard-to-resolve bugs after watching a lot of youtube videos and reading stackoverflow posts. 
Here is my notification logic:
After the list is updated, notifications are created based on the remind date that I created. If the remind date has already passed, the notification will still show. One of the problems that I spent most time resolving was that the title of the notification is not changing after I change the todo title. Turned out it was related to the id that I set to the notification and it is now working correctly.

# What did not work at this point
Everything is working at this point.

