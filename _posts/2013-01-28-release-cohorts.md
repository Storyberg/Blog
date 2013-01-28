---
layout: post
title: "Release Cohorts"
description: ""
category: 
tags: []
author: "Michael Dijkstra"
handle: "micdijkstra"
---

Cohorts are nothing new. Fred Wilson blogged that the cohort analysis is one of his firms favourite measurements back in October 2009.

> “I’d encourage everyone doing a web startup to adopt the startup metrics methodology and within that methodology, make sure you are looking at cohorts of users, not just all of your users in the aggregate.” <sup>1</sup>

The great benefit of cohorts is that they make it clear if user engagement is actually improving over time.

In most analytics tools cohorts are automatically created by week or month for the duration that metrics are recorded. This sounds great in theory because it's easy to do from a programming perspective, but it rarely works in practice.

Given that a cohort is a group of people who share a common experience, they should be created when the experience for the user of an application changes, or in other words, when feature releases occur.

The benefit of release cohorts over generic weeks or months is that you can see if the product changes you are making are positively or negatively impacting user engagement over time.

## Release cohorts in action

For example, say your previous release cohort shows that users are not activating, so you create a new welcome flow for your application. This is a significant release so you create a new cohort. Users start signing up to the app and activation has improved significantly. You pat yourselves on the back and mark that release off as "Validated".

As time goes by, you continue to monitor and compare the two cohorts. While initial activation might be significantly better with the new welcome flow, the data shows retention is much worse, as is paying customers. 

<div class="figure"><img src="/assets/images/2013-01-28-introducing-release-cohorts-1.png" alt="Release Cohort Example"></div>  

  

Therefore this welcome flow is not the golden feature you first thought it was and you now need to talk to users who signed up after you released it. Good thing they're grouped together in a cohort.

Release cohorts are a new feature we implemented into Storyberg. Do you think they can help you validate you're building something people want?  Let us know on [Twitter](http://twitter.com/storyberg)

* * *

1. Fed Wilson, *AVC - musings of a VC in NYC* (http://www.avc.com/a_vc/2009/10/the-cohort-analysis.html)
