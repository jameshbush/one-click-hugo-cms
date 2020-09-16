---
title: Netlify Talk
date: 2020-09-16T19:22:10.976Z
description: Search keyword trends -- CloudFlare in red, Netlify in green. Both
  increasing in popularity.
image: img/screen-shot-2020-09-16-at-6.33.52-pm.png
---
**What it is**

* GitHub Pages + AWS Lambda + Cloudflare CMS/DNS + with additional integrations and features
* $100+ mil funding
* Founded 2017
* Invented the JamStack (JavaScript, APIs, Markup)

<br><br> 

**It's a good fit for**

* Your personal projects
* A consulting client that's not a technology company
* A project with just a few developers or short horizon
* You want a simple serverless backend and a static front end
* You want a SPA/Serverless monorepo
* You don't want to config/manage a complicated AWS system - but you want to use FaaS
* You don't want to manage a Kubernetes cluster

<br><br>

**Key features**

* Static Content
* Serverless Functions
* DNS configuration
* Git-based workflow by default
* Github build integration by default
* "Sane defaults"

<br><br>

**Price**

* Simple and straightforward, pay for what you use
* More expensive than AWS and other IaaS providers
* Cloudflare workers: 100k daily free; $5/mo + $0.50/million requests
* Netlify functions 125k monthly free; 2 million/mo $25

<br><br>

 **Cons**

* Quickstart examples (documentation) broken — because they are iterating their stack & JS ecosystem moves fast
* Ran into “works on my machine but not in the cloud” and “Works in the cloud but not on my machine” with both React+Lambda and TS React+Lambda starters
* Because it does so many things, I don’t think it does anything particularly well. And it’s harder to find good learning resources and documentation because it’s a less popular platform and it does so many things
* The button that says “Gatsby Site Starter — deploy with Netlify” failed to download Nodejs on deploy

**Pros**

* It includes a lot of things under one roof. So, spend less time thinking about how to set up and connect different basic services
* It wraps AWS functions, coordinates them with front end in monorepo, and gives a useful CLI
* Build automation setup on init