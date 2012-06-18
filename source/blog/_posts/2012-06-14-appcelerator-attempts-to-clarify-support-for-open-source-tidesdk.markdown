---
layout: post
title: "Appcelerator Attempts to Clarify Support for Open Source TideSDK"
date: 2012-06-14 20:49
comments: true
categories: appcelerator
author: David Pratt
published: false
---

### The Bad News

The TideSDK project received disappointing news today as Appcelerator attempted to clarify a position that left little in the way of support to enable the transition of the Titanium Desktop project to a community open source effort.

### The Original Pledge

Appclerator originally pleged its support to this transition in its official blog

[Official Appcelerator Blog - The Future of Titanium Desktop](http://developer.appcelerator.com/blog/2012/01/the-future-of-titanium-desktop.html)

### Appcelerator's Official Statement Received June 14

From the Titanium Desktop Transition Mailing List

"Hi everybody,

Recently there has been some confusion around the legal status of the desktop codebase, and the official position of Appcelerator as it pertains to supporting the Tide SDK project.  I wanted to clarify both of those items, so that everyone knows where Appcelerator stands.

The source code located at https://github.com/appcelerator/titanium_desktop is open source under the terms of the Apache 2.0 license.  As such, it can be forked, modified and redistributed under the terms of the Apache 2.0 license, and is not covered or impacted by the licenses applied to other Appcelerator products, such as Titanium Studio.  However, "Appcelerator Titanium" and the Titanium Ribbon logo are registered trademarks of Appcelerator, Inc., and may not be used by Tide SDK or in any derivative works.

Appcelerator is focused on building our mobile platform, and our entire organization must be dedicated to that goal.  Thus, we cannot commit to any ongoing financial, administrative, or development support relationships. With that said, we do want to remain open to supporting this community on a case-by-case basis.  If there are specific requests that can be accommodated, we want to assist in those instances.  We would ask for those requests to be made of our developer relations team, which can be contacted via e-mail at community at appcelerator dot com.

Hopefully this helps clarify our original position.  Please direct any questions or concerns to community at appcelerator dot com.

Thanks,

-Kevin

-- 
Kevin Whinnery
Director of Developer Relations
Appcelerator, Inc."

Needless to say this was discouraging news after we felt that we had shored the necessary legal, finanical support and technical consultation we had received earlier from Kevin. You can follow this thread at:

[Tiantium Desktop Transition List - Clarification on Appcelerator relationship](https://groups.google.com/forum/?fromgroups#!topic/titanium-desktop-transition/IUe7S8lYNs0)

### Statment from Jeff Haynie, Appcelerator's CEO

Jeff Haynie, Appcelerator's CEO intervened to advise the following:

"Hey guys

I'm not sure how much more clear we need to be around the license for desktop. The code in github is Apache 2. However Studio is not. Studio is not the issue here. It's not OSS and never has been. It is however free. But studio is not required for desktop and shouldn't need to be considered as part of the TideSDK and likely would never be part of Studio anyway.

On the issue of packaging, our build server simply invoked the package scripts that are already available as part of the source and are open source. The wrapper code simply did work to add the build to our DB and some other Appcelerator cloud type stuff. It's is little less than 500 lines of code and wouldn't be useful if we did OSS it.

You have our moral and some limited financial support. I think that is reasonable."

### TideSDK Requests From Appcelerator

Our requests for support were outlined in this document. Pledges of support from Appclerator's Kevin Whinnery came to us in an irc conversation on #tidesdk that was logged. The log is included.

[Appcelerator Requests](https://github.com/TideSDK/TideSDK/wiki/Appcelerator-requests)

In total, our requests consisted of the modification a license clause in TiStudio, startup costs totalling $2104.00 and an ongoing monthly cost of $797.00. We requested assistance for some technical consultation for our developers for a limited time until our developers become more familiar with the code base. Our budget is attached in the request document above for clarity and breakdown of the numbers. Mostly this is to provide for our Continuous Integration (ci) system and to use those same servers in a role for user network packaging.

We had also asked that Appcelerator set aside funds that we could request on a case by case basis to offer bounties to accelerate important bug fixes and to encourage new developers into the code base.

Having felt we had received the commitments of support verbally, we were surprised the budget was rejected. We were advised to wait for Kevin's official statement on support. The official correspondence suggests no tangible support or cooperation. As the Project Lead, I requested a face-to-face skype with Sandeep Johri to resolve this issue prior to Kevin making an official public statement on the mailing list. I was forced respond on the mailing list to clarify for all, the figures and pledges made by Appcelerator in contrast to their actions.

We are currently awaiting clarification from Jeff Haynie to understand the meaning of "minimal financial support". We delivered a budget with that meaning in mind. For TideSDK to be developed, we must maintain a ci system to ensure we understand the impact of code changes on our builds and unit tests. We currently receive no funding from Appcelerator that I am aware of.

### A Lack of Support that is Difficult to Reconcile

Appcelerator is currently ranked #2 by on momentumindex.com with 50.2 million in venture capital. 

[http://momentumindex.com/100-open-source-companies-ranked-by-momentum-index](http://momentumindex.com/100-open-source-companies-ranked-by-momentum-index)

This is a fact that is hard to reconcile with the rejection of our minimal request for legal, financial and technical consultation. Appcelerator dicontinued TiDesktop with a pledge to the community for a transition and continuation under an open community effort.

Excerpt from the original pledge:

"The new Desktop project, which will undergo a name change from Titanium Desktop, will be governed and developed by the Desktop community, with material, administrative and logistical support from Appcelerator, but limited development resources. From the Appcelerator side, I will be acting as the liaison for this community to Appcelerator, and facilitate any action or assistance that needs to be rendered from our end."

### Summary

Depite the current circumstances, a transition is occuring. It is not the transition envisioned nor supported by Appcelerator in the manner pledged. Despite this, there is dedicated and growing support for TideSDK. It is our desire for the TideSDK project to work together with Appcelerator on a collaborative and cooperative basis. We have requested a meeting to properly resolve this since there is stark contrast between words and actions to supply our team with the needed resources. 

It is desirable for this to end with the support we need together with a announcement of support from Appcelerator and a joint commitment towards the goals of a successful transition. I will continue to press Jeff for a time to resolve this so that we may rest assured these commitments are met and our efforts are not compromised.









