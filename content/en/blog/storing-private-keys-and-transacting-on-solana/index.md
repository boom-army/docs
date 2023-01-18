---
title: "A Secure Approach to Storing Private Keys and Transacting in Solana"
description: "Listen up, freaks. When it comes to cryptocurrency, security is of the utmost importance. Not only is your financial well-being at stake, but also the security of the entire network."
lead: "Listen up, freaks. When it comes to cryptocurrency, security is of the utmost importance. Not only is your financial well-being at stake, but also the security of the entire network."
date: 2023-01-18T14:12:51+13:00
lastmod: 2023-01-18T14:12:51+13:00
draft: false
weight: 50
images: ["tree-key.png"]
contributors: ["harkl"]
---

And let me tell you, the crypto game is not for the faint of heart. In this blog post, we will explore a few different ways to ensure that your Solana transactions and storage are as secure as possible, because in this wild west of digital assets, you can't be too careful.

## Why Security is important

Let's get one thing straight, cryptocurrency is vulnerable to hacking and other forms of cybercrime. And let me tell you, there are some real lowlifes out there just waiting to steal your hard-earned crypto. In order to protect your assets and the network as a whole, it is essential to take the necessary precautions to ensure that your transactions and storage are secure. This includes using a safe and secure operating system, creating an air-gapped wallet you only load in a secure environment, and properly backing up your seed phrase. Because trust me, you don't want to be left out in the cold with nothing but a string of meaningless words.

## 1) Using Tails bootable Linux USB

One of the best ways to ensure that your transactions and storage are secure is by using a secure operating system environment. And let me tell you, [Tails](https://tails.boum.org) is one hell of an operating system. [Tails](https://tails.boum.org) is a bootable Linux USB that is specifically designed for anonymity and privacy. It's a portable secure OS that is designed with privacy and security in mind first.  It's like a psychedelic cloak of invisibility for your digital assets.

### 1.1) Why use Tails

[Tails](https://tails.boum.org) is a live operating system that can be booted from a USB drive or DVD. It is based on the Debian Linux distribution and is built to provide anonymity and privacy. And if you don't already know it, in this crypto game, anonymity is key. [Tails](https://tails.boum.org) is also built to be resistant to malware and tracking, so you can sleep easy knowing when you boot it up your assets are derisked from prying eyes.

### 1.2) How to make a Tails Bootable USB

In order to create a [Tails](https://tails.boum.org) bootable USB, you will need a USB drive with at least 8 GB of storage and a computer with an internet connection.

- Download the [Tails](https://tails.boum.org) ISO file from the [Tails website](https://tails.boum.org).
- Use a USB image writer software like ["Etcher"](https://www.balena.io/etcher/) to write the ISO file to the USB drive.
- Restart your computer and set the USB drive as the first boot device.

### 1.3) Apple Silicon alternative for ARM arch

Apple Silicon devices like Macbook Air and Macbook Pro are now equipped with ARM architecture processors, which can present a challenge when it comes to finding a secure operating system that is compatible with the architecture. One alternative solution is to use [UTM (Untangle Network Security Framework)](https://mac.getutm.app) and Ubuntu ARM64 server with ubuntu-desktop as a virtual machine.

Here's how you can set it up:

- Install and configure [UTM](https://mac.getutm.app) on your Apple Silicon device to create a virtual machine.
- Download and install the [Ubuntu ARM64](https://ubuntu.com/download/server/arm) server image with the ubuntu-desktop package added.
- Once setup, you can use the virtual machine as a fresh environment for your Solana transactions and storage, ensuring that your activities are somewhat isolated from the host system.

Although this is less secure than using Tails because of disk writes and potential keyloggers, by using UTM and Ubuntu ARM64 server with ubuntu-desktop as a virtual machine, you can ensure that your Solana transactions and storage are as secure as possible, even on Apple Silicon devices with ARM architecture processors.

## 2) Creating an Air Gapped Solana Wallet

Another important step in ensuring the security of your Solana transactions and storage is creating an air-gapped wallet. An air-gapped wallet is a generated wallet that you ONLY connect to the internet through your [Tails](https://tails.boum.org) bootable USB. You want to keep your treasury assets on that wallet, and then only move assets you need to your hot wallets as you need them. An air-gapped wallet with [Tails](https://tails.boum.org) is like having your own Fort Knox for your assets, where they can be safe from the digital bandits roaming the internet.

### 2.1) Using the command line

The safest way to create an air-gapped Solana wallet is by using the command line. This involves using the Solana CLI to create a new wallet and then transferring the private keys to an offline computer or device. It's like a digital safe deposit box, where your assets can be locked away and protected.

### 2.2) Using Glow wallet

If you're going to create an air-gapped Solana wallet using a brwoser plugin you really can't go past Glow wallet. Glow wallet is a browser wallet plugin and mobile wallet that allows you to create a new wallet and then transfer the private keys to an offline storage solution. With Glow, you have the advantage of an easy to use interface if you're not comforatble using the command line. And Glow has added security for every transaction, displaying exactly what you're signing in the TX method so you can avoid wallet drains via extended wallet permissions.

## 3) Seedphrase backup using steel

In addition to using a secure operating system and creating an air-gapped wallet, it is also important to properly backup your seed phrase. A seed phrase is a series of words that are used to restore your wallet if it is lost or stolen. Losing your seed phrase is like losing the key to your digital safe deposit box. So it's important to have a backup plan. One way to ensure that your seed phrase is properly backed up is by using a seed phrase backup tool. Using physical steel allows you to engrave your seed phrase onto a permanent durable object, providing a secure and storable backup. 

## Conclusion

By following these steps and using the recommended tools, you can ensure that your Solana transactions and storage are as secure as possible. Remember to always keep your private keys and seed phrase in a safe place and to always use a secure operating system when transacting in Solana. Because in this crypto game, you can never be too paranoid.
