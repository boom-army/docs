---
title: "💥Build Diary 21💥"
description: "In this issue - Big server migration completed, BoomHeroes on sale, Steady lads deploying proper capital"
lead: "In this issue - Big server migration completed, BoomHeroes on sale, Steady lads deploying proper capital"
date: 2022-11-22T06:40:56+13:00
lastmod: 2022-11-22T06:40:56+13:00
draft: false
weight: 50
images: ["servers.jpeg"]
contributors: ["harkl"]
---

Are you still alive anon? Are you still here? I'm still here and I'm still building [Boom](https://boom.army). Nothing has changed for the long term thesis on Solana as far as I'm concerned. It's the fastest production Blockchain Layer 1 at scale, with the best community and developers in crypto period. Boom is committed to continuing delivery indefinitely and will always do so as long as Solana remains the best product in the biz.

So what have I been up to for the last couple of weeks?

## All your data is now anon

The last couple of weeks have been spent on a major migration. I've moved all of our backend services and data storage to an anonymously hosted VPS via [BitLaunch](https://bitlaunch.io) all paid in Bitcoin. This is important as part of the anti-fragility of [Boom](https://boom.army), and although it was a lot of work it's certainly worth it.

### Decreased costs

As a side benefit this decreased the cost of hosting significantly. Hosting an app that will handle proper scale in production is not cheap, but now the burn rate for [Boom's](https://boom.army) hosted services has gone from around 400 USD per month to around 90 USD. Ultimately this gives [Boom](https://boom.army) a new amount of unlimited runway, so we can consolidate with a lot less cost stress during the Bear market and get ready for the influx of onboarding during the Bull. This is a huge part of the reason building in a Bear market makes for strong companies.

### Faster data delivery

[Boom](https://boom.army) has moved to a self-hosted postgres instance which is a large part of the cost saving. RDS on Amazon is great because it's a turn-key solution and gives you scale and convenience but it comes at a hefty cost. The new server running the postgres instance is dynamic so [Boom](https://boom.army) can now scale the hardware and run a standard postgres installation that takes full advantage of dedicated resources without the cost overhead.

## BoomHeroes are having a fire sale at 1.30 USD

The BoomHeroes floor has never been lower. [It's currently sitting at 0.10 SOL](https://www.tensor.trade/trade/boomheroes)! Understandable given I do basically zero marketing and am uncensored in everything I say on social media which can turn quite a few of the crypto-bros and woketards off. As far as I'm concerned this is a feature not a bug. But in the future the BoomHeroes NFT will still be the Boom version of Twitter Verification and I'll be building premium features into the feed for holders. Do what you will with that information, but the whole Magic Eden collection could basically be swept for a few hundred dollars at the moment.

## RPC woes

If you've noticed that tipping is sporadic and profiles don't load NFT galleries you've noticed that Boom has switched back to the stock Solana Mainnet RPC. A lot of optimization needs to go into the RPC calls, and I'm aware that it's less than ideal. It's on the todo list.

## A focus on funding

In the short-term I'm focused on securing a steady line of funding so that I can hire some developers and stop working on everything myself. Unfortunately there's just not enough time in the day to do everything alone. Boom is a massive undertaking for one individual and even though I've been going solo on the project for over a year now and delivering successfully I'm acutely aware that I need to get serious and get funded so the whole project can take on the real contenders. If you're a VC looking to fund a serious builder project, then don't hesitate to reach out on [twitter in my DMs](https://twitter.com/harkl_). I'd love to chat.

Until we meet IRL - [harkl_](https://boom.army/harkl)
