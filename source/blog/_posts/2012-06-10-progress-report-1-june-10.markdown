---
layout: post
title: "Progress Report 1 - June 10"
date: 2012-06-10 17:23
comments: true
categories: progress
author: David Pratt
---

This is first public post on progress. With the blessing of Boydlee, I have assumed the Project Lead position. You will find me at https://github.com/fairwinds. After some delay, TideSDK is moving forward in a positive way with the code and also with the full support of the initiative from Appcelerator through Kevin Whinnery.

I have sought commitments from Appcelerator for their support including specific legal, financial and technical assistance (when needed). I was happy this past week to have received this. I have been advised that Nina, Appcelerator's dedicated legal support is working actively to immediately resolve the issue posed by the TiStudio (that impacted the TiDesktop and Kroll projects that we are inheriting). This has been a barrier to moving forward and a high priority request that I expect to see fulfilled shortly.

The short term plan is below. We are focusing here.

* Verify existing builds and build instructions on supported platforms. Tool chains need to be updated. Seek additional developer support once we have verified build processes to get people started easily.
* Establish our CI capacity and automation.
* Rename the core project in the code retaining the Ti namespace.
  Ti === Titanium === TideSDK
* Test and release a candidate at 1.2.1.RC1 that will be beginning of TideSDK line from Titanium Desktop inheritance
* Update libraries incrementally that TideSDK relies upon (release frequently)
* Create a branch for OSX sandboxing initiatives. (high priority)
* Cherry pick priority bugs from JIRA and begin issue tracking process through Github which has a low barrier to use and where our project lives. JIRA will be used as resource only for historical context.

First, welcome https://github.com/nazcasistemas to the development team who has already shown himself to be a dedicated team developer. We have dedicated long hours to ensure we are able to successfully build on all platforms (MacOSX, Windows and Linux). This is an important first milestone that we achieved recently and in a relatively short period of time between us. We have documented progress on a wiki at https://github.com/TideSDK/TideSDK/wiki. Josh has also been with us the past days giving us further insight into the code. Josh has also recently been successful on MacOSX Lion which is another important milestone and has been exploring Embedded Chromium for the project.

At this point, we are working through Drillbit tests to establish the quality of the builds and what may need some immediate attention.
Initially, we have a small developer group and we want to expand this shortly. As soon as we have verified, tested, and have documented our build instructions and laid the groundwork, we will begin soliciting more help from the community. We do not want a circumstance where help arrives and we are not prepared to get people going or fully understand our needs.

I have asked Appcelerator to transfer the TiDesktop and Kroll repos to us directly. This will retain all followers, forks, pull requests and such. I am hoping to have this happen immediately as we will be going through a process of renaming code components to rebrand. Rest assured the namespace will not change. That is Ti === Titanium === TideSDK so your projects should be unimpaired by what we are doing.

Sharry at https://github.com/molinto has pledged ongoing support on the communications and marketing side and we have in a short time identified priorities and taken stock of what we have. https://github.com/TideSDK/TideSDK/wiki/Communications-Strategy

The code base is very large and complex and requires a depth of understanding. For folks anxious to dig in the first step is a proper study of the code which is hosted at https://github.com/TideSDK. I am confident we will be able to extend our small team to meet the challenge.

In addition, we are working to determine builds on updated toolchains. There is currently a bug with scons that makes building on MSVC10 Express a problem. I am working on a bug fix to send on to the scons project when complete. Once this is fixed, we will be able to build using the current defacto compiler for Windows. That said, we already building on the older tools for Windows.

Next, we will be setting up automated build processes on a Continuous Integration (CI) system. I will be making my request to Kevin on server instances for various platforms to support the system. This is a critical need for the project as we must support 32 and 64 bit platforms and multiple operating systems. We must know what is happening at all times with the builds when there are changes to the code base.

This message is long and much more to say but out of time. Please follow our developments and we will keep appraised. Our objective is to release quickly and often. If our build processes and testing check out well and renaming exercise goes as expected, an early release should be available in the next week. Please stay tuned.

Regards,
David