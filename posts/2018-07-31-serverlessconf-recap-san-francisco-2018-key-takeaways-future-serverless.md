---
title: "ServerlessConf 2018 San Francisco: key takeaways for the future of serverless"
description: "Missed ServerlessConf in San Francisco this week? No worries, we got you. Here are the key takeaways you'll want to know about."
date: 2018-07-31
layout: Post
thumbnail: "https://s3-us-west-2.amazonaws.com/assets.blog.serverless.com/slsconf_nyc.jpg"
authors:
  - AndreaPasswater
---

It's been amazing to see the lightning fast transformation happening in the serverless space. ServerlessConf 2016 was the conference of serverless projects. By the 2017 conference in NYC, the community had already been building a lot of projects. The new problem was tooling, and [tooling discussions dominated the stage last year](https://serverless.com/blog/serverless-conf-2017-nyc-recap/). 

So what about ServerlessConf 2018 in SF? It's been the conference of two things: (1) big@$$ companies talking about their large-scale, production serverless architectures; and (2) (from a drastically different perspective) non-engineers talking about how serverless technologies empowered them to begin developing their own apps, without a coding background.

## Serverless adoption and architecture in large-scale organizations

The talks in this category had three main types: 

### 1. Serverless as the basis for rapid development

Developers looking to minimize time to value will automatically gravitate toward serverless. 

Leslie Pajuelo from Walmart just ran a POC in which she rebuilt their high performance orchestration layer. It's a use case we hear about all the time—a developer goes, "we want to try this serverless thing," and they build it out with a 1 or 2 person team. It does so well that the organization then moves to expand usage.

### 2. Testing, debugging and monitoring of production serverless apps

This has been an undercurrent of serverless adoption discussions for a long time, and it's been dominating the table discussions here. Every presentation starts to touch on the ways teams at Verizon, CapitalOne and Nordstrom are handling all of their operations with a smattering of tool sets.

We'd be remiss if we didn't mention that this is something we've been passionate about here at Serverless, Inc, and as such we [just launched a new Serverless Platform Beta](https://serverless.com/blog/serverless-platform-beta-helps-teams-operationalize-development/) to help teams operationalize serverless across their entire organization.

### 3. Structured models and practices to design and analyze Serverless architecture

Rob Gruhl from Nordstrom talked about the best ways to scale serverless:

1. Partition for horizontal scalability
2. Embrace eventual consistency
3. Idempotency throughput
4. Stateless(ish) compute
5. Understand your bottlenecks

<img src="https://s3-us-west-2.amazonaws.com/assets.blog.serverless.com/2018-serverlessconf-sf/nordstrom-serverless-all-things.jpg">

And it's easy to see why this matters. Verizon is here at ServerlessConf talking about serverless in the enterprise. There was a case study from Box. Capital One is presenting on their own architecture tomorrow. Fender Digital (yeah, the guitar company) is all-in on serverless right now. And? They're transitioning everyting to Go. 

And speaking of which—

#### Wow, Go was everywhere

Our [community survey](https://serverless.com/blog/2018-serverless-community-survey-huge-growth-usage/) showed that Go usage was increasing, and had already edged past Java. But even the ServerlessConf stage had several mentions of companies who were using Go, and cloud providers who were moving to adopt it.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/AzureFunctions?ref_src=twsrc%5Etfw">@AzureFunctions</a> moving to support <a href="https://twitter.com/hashtag/Golang?src=hash&amp;ref_src=twsrc%5Etfw">#Golang</a>? <a href="https://twitter.com/hashtag/ServerlessConf?src=hash&amp;ref_src=twsrc%5Etfw">#ServerlessConf</a> <a href="https://t.co/KT8mnlldJZ">pic.twitter.com/KT8mnlldJZ</a></p>&mdash; Serverless (@goserverless) <a href="https://twitter.com/goserverless/status/1024419241766707200?ref_src=twsrc%5Etfw">July 31, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### People are really thinking about security

One thing we noticed in every "here's how we're using serverless" presentation this year, which was largely missing in previous years, was the security component. How are serverless organizations handling security, what are their best practices?

<img src="https://s3-us-west-2.amazonaws.com/assets.blog.serverless.com/2018-serverlessconf-sf/fender-digital-serverless-security.jpg">

Mark Nunnikhoven insisted—you're better off out of the gate with serverless security. And ultimately, security is about the _people_. It isn't about just securing the functions, you need to have a robust system that does what it's intended to do, and only what it's intended to do.

## Bringing software development to the non-developer developers

What does that even mean? It appears there is a trend among people with non-engineering backgrounds using serverless. With a lot of the tricky administration cut out of the mix, a vast ecosystem of beginner-oriented tutorials, and pre-existing code repositories like NPM, it's never been easier for inexperienced newbies to get started with their own coding projects.

Our own Andrea Passwater does Growth at Serverless, Inc, and has started to deploy her own marketing-based automation tooling. In her own words: "Serverless significantly lowers the barrier to entry for anyone who wants to automate parts of their workflow. And if I could automate away the boring things in my life, then why wouldn’t I?!"

Her first serverless app was [Serverless Ipsum](https://medium.freecodecamp.org/i-just-deployed-a-serverless-app-and-i-cant-code-here-s-how-i-did-it-94983d7b43bd), but she has since moved on to other things, like a Slack bot that pings her coworkers about their blog post deadlines. 

And she's not the only person preaching about the newfound accessbility of coding. Keith Horwood is speaking on Stdlib, an API platform that could make developing APIs more like using Zapier. There are more engineers having open discussions about how to make coding more accessible to everyone, and more people at ServerlessConf from non-engineering backgrounds who are here to learn.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/goserverless?ref_src=twsrc%5Etfw">@goserverless</a> <a href="https://twitter.com/sogrady?ref_src=twsrc%5Etfw">@sogrady</a> <a href="https://twitter.com/monkchips?ref_src=twsrc%5Etfw">@monkchips</a> theme from <a href="https://twitter.com/Serverlessconf?ref_src=twsrc%5Etfw">@Serverlessconf</a> seems to be &quot;Knowledge workers and other non-developers are the newest Kingmakers&quot; 😉 <a href="https://twitter.com/hashtag/serverless?src=hash&amp;ref_src=twsrc%5Etfw">#serverless</a></p>&mdash; Val Bercovici 🇻 (@valb00) <a href="https://twitter.com/valb00/status/1024364019241472000?ref_src=twsrc%5Etfw">July 31, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Stay tuned

This is only day 1. More talks to be had tomorrow! Stay tuned for all the updates, straight from us.
