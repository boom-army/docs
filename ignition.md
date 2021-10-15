## Inspiration

Web2 spawned the Social Media craze. Large centralized organizations have grown out of these social media platforms, where users share their data for free. That data is monetized by these companies, and they've made a boatload of money in the process. The problem for users is that they don't typically see any profit from their valuable data. This is the environment sosol has an opportunity to disrupt.

[Solana](https://solana.com) allows **sosol** to shift the landscape of Social Media from a Consumer-to-business (C2B) model, towards a Consumer-to-consumer (C2C) driven model. By signing content with public/private keys, Content Creators are able to post and upload content with provable ownership. This way Content Consumers can engage content for a small fee, and a Solana Program sits in between the two parties to facilitate the terms and fees associated with that engagement.

It was [Melvin E. Conway](https://en.wikipedia.org/wiki/Conway%27s_law) who stated that "Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure." By shifting the social media landscape from C2B to C2C and removing third parties from engagement, there is an opportunity to align social media toward a more human centric organizational model. Mirroring real world interaction where peers communicate directly with one another and transact value accordingly is the primary driver of **sosol** and it's delivery road-map.

## What it does

**Sosol** alpha is a twitter clone, that aims to prove the concept of micro-transactional engagement on Social Media. It is integrated with a Solana token and token program, to enable micro-transactions with sub-second finality delivering a Web2 experience on Web3 infrastructure. This specific social format was chosen, because the base functionality of Twitter is succinct and easily understood as a concept for Content Consumers and Creators to learn how micro payments can augment and improve the social experience.

### Tokenomics

The core program transaction method between Consumers and Creators is described in the attached image:

![Content Creator to Content Consumer flow diagram](https://github.com/sosol-gmi/docs/raw/main/assets/img/creator-to-consumer.png)

## How we built it

**Sosol** was built over 4 months by a single developer. It all started with a conversation in Telegram with a close friend in July 2021:

"The first blockchain network that can build a viable twitter competitor will go 1000x. At the moment I think that it's probably only possible on $sol, $tron and maybe $dot."

This idea led to the realization that @harkl_ could build an alpha alone, which started the build process encompassing delivery of an alpha prototype with the following stack:

- [React JS client](https://github.com/sosol-gmi/sosol-client)
- [Serum Anchor Contract](https://github.com/sosol-gmi/sosol-program)
- [Dockerized GraphQL API](https://github.com/sosol-gmi/sosol-graphql-api)
- [Terraformed AWS server](https://github.com/sosol-gmi/sosol-graphql-api/tree/main/terraform)
- [Solana token on testnet](https://explorer.solana.com/address/soso1vCmdxwEZqU47M4NZ4MxZH19ppgqF1auG7dP3wz?cluster=testnet)

## Challenges we ran into

The technical challenges for the initial delivery of alpha were relatively minor. Learning Rust, and becoming familiar with the Solana program structure were somewhat of a challenge, as the dev community is relatively small. But the passion of the community makes up for the size, and there was excellent support from likes of [Chase Barker](https://twitter.com/therealchaseeb), [Armani Ferrante](https://twitter.com/armaniferrante), and [Seb Montgomery](https://twitter.com/SebMontgomery). Also, Rust is a language with some of the best documentation and tooling that exists. It's an excellent choice for building something like Solana on top of.

The future challenges are likely to grow with each delivery phase. By far the largest challenge on the horizon is decentralizing the database. But there are some promising candidates for this that can be either built on top of or forked and reworked to be fit for purpose. Overall the outlook for decentralized monetized social media is blindingly bright.

## Accomplishments that we're proud of

- Build time: from zero code to full product delivery in just four months with a single developer.
- Community engagement: As of today there are 1,290 alpha testers keen to jump in and try **sosol's** offering of monetized social media.
- Open Source: All the sosol code is open source and hosted at [github.com/sosol-gmi](https://github.com/sosol-gmi).

## What we learned

Solana specifically provides the ability for a rich online experience with high throughput (65k+ TPS), long term scalability, micro-transactional appropriate fees (< $0.001 USD) and near immediate transaction finality (400 ms). Following Conway's law, development on blockchain lends itself to decentralized patterns, making user account management much more streamlined when handled by a public/private keypair rather than a centralized email system. In an increasingly centralized online world, blockchain is essential for open democratic engagement and monetized social is a key ingress for this paradigm.

## What's next for Sosol

- Setting up the company structure (in progress).
- Launching the token on mainnet.
- Building out the development team.
- Taking all code-bases to 80% test coverage.
- Moving the AWS GraphQL API to a decentralized candidate such as IPFS/OrbitDB.
