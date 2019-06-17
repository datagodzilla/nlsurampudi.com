---
layout: post
comments: true
title: 'SQL for Data Science'
excerpt: 'Stages of data analytics project'
date: 2019-05-05 04:00:00
mathjax: false
published: true
permalink: /sql/
summary: "Concepts of SQL in Data Science"
tags: [news, machine_learning, be
tags: [news, machine_learning, becoming_a_machine_learning_engineer]
---

# Introduction

## Database Normalization
When creating a database, it is really important to think about how data will be stored. This is known as normalization, and it is a huge part of most SQL classes. If you are in charge of setting up a new database, it is important to have a thorough understanding of database normalization.

There are essentially three ideas that are aimed at database normalization:

Are the tables storing logical groupings of the data?
Can I make changes in a single location, rather than in many tables for the same information?
Can I access and manipulate data quickly and efficiently?
This is discussed in detail here[http://sqlmag.com/database-performance-tuning/sql-design-why-you-need-database-normalization].

However, most analysts are working with a database that was already set up with the necessary properties in place. As analysts of data, you don't really need to think too much about data normalization. You just need to be able to pull the data from the database, so you can start making insights. This will be our focus in this lesson.