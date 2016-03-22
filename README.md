# Database Optimizations

## Description

Given an existing application which generates a report from a large data set, improve the efficiency of the report using database optimization methods.

## Objectives

After completing this assignment, you should...

* Understand the downsides of loops within loops in Rails.
* Understand the benefits and appropriate use of indices on database tables.
* Understand the downside of indices.
* Be able to measure the runtime of various webapp functions.
* Be able to query the database more efficiently.
* Be able to implement database indices.

## stats

* Time to seed the database 30.78 minutes (1847 seconds)
* Time to perform the first record search 27.93 minutes (1676 seconds)  I ended up
performing this search twice and while google timeline was compiling stats it just
shut down.
* After adding indices to hits/sequences/genes the same search took 11.43 seconds.
idle time was 1.83 seconds.  Rails time 7.21 seconds and 8.48 seconds recorded from
the bottom of the page.  Running the migration took very little time as well.
* Percent improvement in run time was 99.94%

## Time Estimate For assignment

I thought that this assignment was going to take 6 to 8 hours because some of the
skills we had not touched on before.  I thought that it would take a lot of research.
This turned out to be the case as I spent a good amount of time trying to figure out
how to join tables to optimize search times.  In the end I spent about 6 hours on the
assignment and did not complete it.
