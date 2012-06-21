---
layout: post
title: "Unit Testing Progressing with Drillbit"
date: 2012-06-21 10:26
comments: true
categories: Drillbit
author: David Pratt
---

Our team has been working to get Drillbit running and sucessfully passing unit tests in anticipation of connecting to our Continuous Integration system late this week to executed the tests following commits from Git.

There are a total of 4619 assertions made in the tests. Currently 85 tests remain broken but this is already much better from originally and we continue to progress. The failing support continues to be primarily in the language and process modules.

The following is a screenshot of the unit testing and current status:

![June 21 Drillbit results](http://tidesdk.github.com/images/drillbit-06212112.png)