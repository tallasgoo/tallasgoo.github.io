---
layout: project
type: project
published: true
image: images/database.jpg
title: Account Manager
permalink: projects/account-manager
date: 2017
labels:
  - C
  - Unix
  - GitHub
summary: A terminal window program that creates and stores generic account records.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/database-menu.png">
  <img class="ui image" src="../images/database-new.png">
  <img class="ui image" src="../images/database-records.png">
</div>

This program allows the user to create, edit, view, and delete account records from a database using a terminal menu-interface. On exit all entered records are stored in a savefile to preserve the database for later use. Account records contain account numbers, names, and addresses.

The entire program was written in C using a Unix text editor. This project required a solid knowledge of pointer values and linked lists of data structures, as well as how to reserve and free up memory on the heap.

Since this project was not written using an IDE, the task of debugging was tremendously more tedious. This project also contained the most number of individual files that I have worked with thus far, requiring me to use a Source Code Control System (SCCS) and Makefile extensively.
 
Source code available on GitHub: <a href="https://github.com/tallasgoo/account-manager"><i class="large github icon"></i>tallasgoo/account-manager</a>
