---
layout: post
title: "5th March 2012 Minutes"
date: 2012-03-05 14:44
comments: true
categories: minutes
author: Sharry Stowell
---

## Tide SDK Leadership Group Meeting - Agenda

### Project Name

* Discussions were made around the name of the project, and the group. "Tide" was the clear winner from the survey of names suggested by the community. After some deliberation and decisions revolving around other similar project names on the web and how we could differentiate ourselves - plus a check on domain availability - it was decided and agreed by majority that the new name of the product and group would be called "Tide SDK".
* As agreed by the group, all correspondence and documentation will refer to the product by its full name of "Tide SDK". In speech, conversation etc, this can also referred to as "Tide".
* Sharry Stowell purchased and is holding for the group the domains "tidesdk.org" and "tidesdk.com". Our main domain will be the .ORG. The .COM will be redirected to the .ORG.
* Our group logo will be created as part of our initial interaction with the community. We will open a competition for the best logo. Details TBC.

### Website Development & Community Co-ordinator

* Sharry Stowell nominated. All seconded

### Project Management Requirements

* All code to be stored in a GitHub Open Source account. Sharry will organize this account.
* Group decided on Atlassian, which includes project management plus Jira, etc. Used by a lot of open source groups. Sharry to organize - we will try to get a free account as we are an open source group.
* OSQA decided upon as the open source Q&A system, which is similar to Appcelerator's and will hopefully ease the transition of existing Q&A from that site to ours.

### Server side languages & Project Architecture 

* Group is divided on the continued inclusion or removal of SS languages.
* The biggest bone of contention for not including them is that some developers rely on them for their current projects. According to Kevin, based on off-the-cuff knowledge, the amount of users actually using these packages is fairly small.
* Alternatively, as a group most feel we do not have the capacity to support 4x languages - JavaScript, Python, PHP & Ruby.
* A suggested middle ground was keeping Python support only.
* Another suggestion was that external language support (re: Python)
should be made as an extension and kept out of the product core.
* Suggestions were made about the implementation of Node.JS as a core piece of the project. Node.JS would allow us to have a built-in framework for native extensions in C/C++, plus has a large community and a bunch of existing extensions we can leverage. It has a large set of built in API's we wouldn't have to rewrite (e.g. file system). It has a built
in package manager. Most of the group seems in favour of Node.JS with a bit of exploring.

### Moving To Chromium (Chrome Embedded) or Keeping Webkit

* Generally considered a good idea from an administration standpoint. The more bits we can "black box" then the more time we have to focus on core code.
* As Kevin pointed out, one of Appcelerator's biggest headaches wascontinually needing to upgrade and package the custom WebKit build with Titanium Desktop.
* In saying, we need to first test Chrome Embed

### Architecture Submissions

* The group is divided along some lines of architecture, and the system as a whole needs to have some serious thought.
* On that note, it was decided and agreed that everyone in the group who has firm ideas about architecture should document, with diagrams wherever possible, their ideas of how to architect the whole solution.
* These submissions are to be made to the group and we will make further decisions based on them when we meet next.

### Licencing

* There is some licencing section of the Ti Studio licence that may interfere with the Apache licences that govern the rest of the existing Ti Desktop et al codebase.
* David is to email the highlighted sections of the licence agreements in question to Boydlee and I will interface with Appcelerator directly to get them amended or get us an exception.

### Date of the Next Meeting

* Monday, 12th of March. 2012


[Download Minutes PDF (~70K)](http://tidesdk.github.com/downloads/TideSDK-Minutes-05032012.pdf)