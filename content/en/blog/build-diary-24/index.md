---
title: "💥Build Diary 24💥"
description: "In this issue - a behind the scenes look at the huge platform upgrade delivered in the last 6 weeks"
lead: "In this issue - a behind the scenes look at the huge platform upgrade delivered in the last 6 weeks"
date: 2023-04-19T13:12:51+13:00
lastmod: 2023-04-19T13:12:51+13:00
draft: false
weight: 50
images: ["hacker.png"]
contributors: ["harkl"]
---

## The Relaunched Boom GitHub Commit History Unveiled

<img src="hacker.png" alt="Hacker time" width="400"/>

Over the past few weeks, I've been hard at work to improve some of the core features and tooling of [Boom](https://boom.army). Today, I'm excited to share a behind-the-scenes look into the commit history of my both the back and front end GitHub repositories, which offer insight into the various enhancements and fixes I've implemented.

One of my primary focuses has been streamlining the deployment and building processes. Notable commits include updating the deployment process for production, adjusting the build process to deploy from Mac M! (arm64 arch) to AWS ECS (amd64 arch) architecture, and tweaking the Docker configurations to build correctly. I also migrated to Node 18 LTS and introduced development tooling for DevOps, ensuring a smoother and more efficient workflow. This means I can now deliver faster!

I put considerable effort into setting up and refining the TypeScript (ts) environment. With multiple commits centered on configuring TypeScript, I managed to establish an up to date best in class build process which should mean less bugs and better stability in future.

In terms of application features, I enhanced the platform's user interface and experience by adding a dashboard with new components like home panels, a tag cloud, and the top meepers list. I made significant updates to the meep schema, allowing for better management of master meeps and child meeps which you'll see reflected in the new threeading. Additionally, I implemented nested comments in the meep view and improved the display and search functionalities for tags.

Security and performance were not overlooked. I made critical updates to CORS settings, authentication, and error logging. Moreover, I worked on optimizing queries, implementing several new fetch limits, and introducing a more advanced date range functionality for returning date specific content.

Lastly, I dedicated time to refining the visual aspects of the platform. I styled titles, made adjustments to the user channels namespace, and even hid non-awarded badges for a cleaner look.

# Why did I do this?

The main reason for the upgrade was migrating the backend from Apollo Server v3 to v4 which caused a daisy chain of events requiring extensive retooling. I've got mixed feelings about GraphQL, but for better or worse [Boom](https://boom.army) is stuck with it as a core part of the platform, and it's too extensively integrated to justify the effort to completely swap it out. Apollo seem to recently either have made some big comprimises, or otherwise hit some limits in their dev team, because the recommended way to implement an Apollo v4 server now is to basically use ExpressJS to do all the heavy lifiting.

Whatever the case the app is leaner and meaner than it's ever been and is now ready to deliver #WhatIsGorgon and the Market Place (finally). All the original plans stand, in one way, shape, or form. It's easy to forget that until [Boom](https://boom.army) gets funded I'm one dev pushing hard to implement the crazy CypherPunk dream of Decentralized Social native on [Solana](https://solana.com). It's especially challenging given so many people in the space seem much more concerned with a quick 10-100x rather than freedom focused crypto tools. That's not me, and I'm very grateful for the small passionate community we have. I also realize that I fall down in many areas, but I hope you'll see I'm never giving up on this project and will continue to buidl even if there continues to be only a few legends on [Boom](https://boom.army).

I love you all - [harkl](https://boom.army/harkl)