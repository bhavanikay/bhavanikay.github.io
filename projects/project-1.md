---
layout: project
type: project
image: images/bdpic.png
title: Bank Database
permalink: projects/BankDatabase
# All dates must be YYYY-MM-DD format!
date: 2021-09-27
labels:
  - C
summary: A bank database I created for ICS 212.
---

<img class="ui image" src="{{ site.baseurl }}/images/bankingdb.png">

I created this bank database for my ICS 212 class. It allows users to create a new bank record, view and edit existing records, and delete records if they wish. This database is written in C and uses the following struct:


```
struct record
{
    int                accountno;
    char               name[25];
    char               address[80];
    struct record*     next;
};
    
```
Throughout the course of this project, I learned about what a “struct” is and how to incorporate it into my program. I also became much more familiar with terminal commands as well as different functionalities of using the UH Unix to write my program. The main issue I ran into during this project is I felt overwhelmed by the end goal: to create a banking database. However, by splitting up the tasks into sections and learning how everything was connected, I found this project to be much easier. I made a tree diagram in order to see the start-to-end process that someone would go through when using this application.
Although it is on the simpler side, it is simple to add more functionalities to this database. Banking has never looked so easy before!

Source: <a href="https://github.com/bhavanikay/BankDatabase"><i class="large github icon"></i>bhavanikay/BankDatabase</a>
