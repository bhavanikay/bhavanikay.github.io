---
layout: project
type: project
image: images/bankingdb.png
title: Bank Database
permalink: projects/bankingdb
# All dates must be YYYY-MM-DD format!
date: 2021-3-15
labels:
  - C
  - Banking
summary: A banking database I created for my ICS 212 class.
---



This banking database allows users to create a new bank record, view  and edit existing records, and delete records if they wish. This database is written in C and uses the following struct for information:


```
struct record
{
    int                accountno;
    char               name[25];
    char               address[80];
    struct record*     next;
};
    
```

Although it is on the simpler side, it is simple to add more functionalities to this database. Banking has never looked so easy before!




