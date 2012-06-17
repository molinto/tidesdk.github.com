---
layout: post
title: "What's Happening? - 10th April"
date: 2012-04-10 16:49
comments: true
categories: update
author: Boydlee Pollentine
---

Hi Everyone,

I know that many of you have been asking on the Google Transition group as to what is happening currently on the TideSDK (nee Titanium Desktop) front. Apologies for not being able to clearly state where we are at before, but I'm sure you can appreciate that there is a lot of things to take over from Appcelerator, and many decisions to be made regarding TideSDK moving forward.

Here's the major points we are currently working on:

We've requested Jira Access and all the Q&A data relating to Titanium Desktop from Appcelerator. Once we have this access/data, we will start filtering all the bug list in order of priority and we will be asking you, the community, to step forward and help us fix these issues.

The current branch of Titanium Desktop is available here https://github.com/TideSDK/titanium_desktop. Please feel free to fork this repo, and make bug fixes now in preparation for when we have the Jira data. We'll be trying to keep the process of merging your changes as seamless as possible - that means simply you fork the code, make the change in your own repo, and create a pull request for us listing the Jira Bug ID and what you did to fix it. We don't have the manpower to bug-test every single pull request, so we'll be relying on the community to do that thoroughly during any release cycle.

About half of the team are currently investigating how to get the WebKit upgraded (particularly on Windows) as a matter of priority. If you want to help with this, please comment on this post and I'll get you in touch with Burak and a couple of the guys who are leading that.

The rest of us are currently looking into building a prototype of how we see TideSDK evolving into a new product in the future. Basically, after looking through many, many options, this is revolving around the use of Chromeless, coupled with NodeJS. This is going well for a prototype investigation stage and we already have a sample application (just hanging off Webian, a sample Chromeless app), that: 

* Runs the standard Chromeless CommonJS libraries
* Runs a custom set of "Tide" CommonJS libraries
* Runs a compiled version of node.js and executes a sample node.js script (called node.js which launches a HTTP server instance on port 8000 and returns some HTML)
* Bundles a basic OSX package, whereby NodeJs and the application itself are executed by a bash script that I packaged up into an application file using another bash script - basically when we would build a 'package' or 'msi' for a user, we're just running some scripts that bundle up our code, Xulrunner and a few other launch scripts together.

We will, as a leadership group, be discussing this approach over the next couple of days with the intention of setting out a series of 0.1 release goals. These will be the features that will be available in our very first release, wich is going to be a very early alpha with a limited feature set, but it will be enough to provide a prototype. I will post those 0.1 release goals publicly once we have group agreement and push the code into a new GIT repo and ask the community to start providing feedback.

Looking forward to your comments over the coming days,

Boydlee