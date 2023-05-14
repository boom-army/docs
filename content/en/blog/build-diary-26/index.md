---
title: "💥Build Diary 26💥"
description: "In this issue - DAO Promo Page, Interface Improvements, App Navigation, and More"
lead: "In this issue - DAO Promo Page, Interface Improvements, App Navigation, and More"
date: 2023-05-15T08:12:51+13:00
lastmod: 2023-05-15T08:12:51+13:00
draft: false
weight: 50
images: ["cypher.png"]
contributors: ["harkl"]
---

![DAO cyber](cypher.png)

Hello everyone! Here's a quick update of the last weeks dev to give you an idea of how the new DAO direction of [Boom](https://boom.army) is progressing.

Listen to the Twitter spaces for a full breakdown on DAO delivery:

{{< tweet user="harkl_" id="1656750151179042816" >}}

## Creating a DAO Promo Page

First off, I've created a new DAO promo page, serving as a platform to advertise the new DAO functionality. This will be a great way for users to understand and engage with the DAO capabilities of our platform. But more importantly, it will act as place where NFT projects can pre-register their interest to be notified when WL invites are ready.

## Interface Improvements

I'm currently making huge changes to the UX and the general structure of the site user interface. This last week of dev has involved prepping the header container for these sweeping changes including:

- **Head Logo and Link Alignment:** The image inside the link for the head logo has been aligned, and it now correctly links to the home page.
- **Navbar Icon Update:** The icons on the floating navbar have been updated for a more intuitive user experience.
- **Appheader Container Adjustment:** The appheader container has been temporarily clipped to a large width to better accommodate various screen sizes.
- **Wallet Connect Button Positioning:** The wallet connect button has been shifted to the right for better visibility and accessibility.
- **Header Positions Adjustment:** We have shifted header positions in preparation for user icon placement.

## App Navigation Improvements

The structure of links is changing to accommodate the new DAO functionality. All DAOs will be available behind a `/d/` link. I hope the reference isn't lost here on some of you ;). Here are the updates that have been made last week in preparation for this:

- **Route Updates in React-DOM-Router:** All routes in react-dom-router have been updated for enum paths. This standardizes link paths and creates a smoother, more predictable navigation experience.
- **Link Updates:** I have updated links across the app to align with the new TypeScript enum file.
- **Side Menu and Universal ToggleDrawer Menu:** I've implemented a side menu with a universal toggleDrawer menu for more flexible navigation options.
- **Menu Button:** I've added a menu button to the top left for easier access to the side menu.
- **Floating Nav Addition:** We have added a floating nav to improve the user experience.

## Mobile View Enhancements

Several enhancements have been made for the mobile view of the app:

- **Scroll Trigger for Show/Hide Header:** I've set a scroll trigger for the show/hide header in the main routes panel. This helps optimize screen real estate on mobile devices.
- **Header Hide for Mobile View:** I've made it so the header only hides for the mobile view when scrolling.

Other than that, I fixed a bug regarding the date display on the hero feed. As always, your feedback is invaluable, and we appreciate your continued support as we make improvements.

Until we meet IRL - [harkl](https://boom.army/harkl)
