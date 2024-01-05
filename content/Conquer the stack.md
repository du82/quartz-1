---
title: Conquer the stack
author: Du Cheng
date: 2023-12-29
tags:
  - Sovereignty
---
I've noticed in recent years a trend towards decentralized and open source technologies with an emphasis on increased liberties to post, share, and create what you want without having to please the site operators or their algorithms.

Out of this, I've noticed a shift in the power dynamic between users and platform operators, and users remain disadvantaged. To gain true freedom, I believe that users must "conquer the stack".

## How did we get here?

### The pre-internet networks
In the early days of what we know as the internet, particularly in 1978, services operated primarily by individuals, known as Bulletin Board Systems (BBSes) were started to organize and share information on the internet.

As these bulletin boards grew in user count, some of them became internet service providers (ISPs). These ISPs then allowed users to access other content on the internet, similar to what we have today.

### Internet Relay Chat
In 1988 a program called IRC (short for Internet Relay Chat) was invented to replace an older and less relevant chat protocol that exited on a BBS. Remember IRC, I'll come back to it later. The important thing you should know about IRC is that it's decentralized[^1].

### Web One: The world wide web
In 1990 Tim Berners-Lee created the first web browser, simply named "WorldWideWeb". This is the start of what is commonly known as "Web 1.0". This new functionality of the internet comes with webpages with limited user interaction and some graphical elements to a mostly text based internet.

Around this time, rudimentary advertising online was becoming commonplace, although the ads were usually unobtrusive banners that didn't track users and were there simply to generate revenue as there was no good way to charge users for access.

### Web Two: Where we are now
Fast forward to around the year 2000, and "Web 2.0" is coming into fruition. Google, YouTube, Facebook, and MySpace were some of the first truly interactive websites to be part of early Web2.

This is the current iteration of the web, controlled by gigantic capitalist organizations and world governments, with considerably less websites operated by individuals. This era of the web is marked by giant advertising agencies and a centralization of services.

### Web Three: The capitalist web
Around 2020[^2] (but started in 2014), the term "Web3" has been used to describe the next iteration of the World Wide Web. This iteration is commonly associated with cryptocurrencies, vague claims of decentralization, and increased microtransactions.

The premise of Web3 is that instead of trusting centralized entities, users will be able to verify code that runs on blockchains, and there will be increased transparency and accountability.

## Our corporate overlords
Remember how I told you that IRC would be relevant later? It failed because it couldn't keep up with the offerings from our corporate overlords, Facebook, Google, Apple, Amazon, and Microsoft.

These giant companies, and similar but smaller ones, set the standard for how modern software should work, which has pushed out much of the old internet. This is problematic since ideas and software binaries are perceived as bad because they don't fit the modern standard of what software should be.

A good example of this is [[The tragedy of Discord]], which was mass migration of users from IRC over to Discord. Despite being a predatory platform full of microtransactions and the platform having artificial limitations imposed on you unless you pay for their "Nitro" subscription, people love it. Simple software that does what it's supposed to and nothing more can no longer compete.

This transition proves that normal people are willing to give up freedoms and control for convenience, even if it means they end up paying for a product that lets employees spy on their Direct Messages.

## Where did we go wrong?
I believe that we went wrong when users decided that they'd rather have convenience instead of control. Its not entirely the fault of the users, since their expectations have been set by giant corporations with millions to spend on little features that aren't critical but nice to have (like stickers).

## What can we do to fix it?
There have been many solutions proposed to solve the madness that is the modern internet. I believe that the most notable attempt; Web3, has also failed. The reason is because Web3 puts the power in the hands of a few investors who are willing to stake inherently risky assets, instead of the real users. This puts the power in the hands of those with money, and we're back to the problems that plague the current internet.

What I think we need to do is to make setting up and maintaining your own infrastructure easier.

## A guide to conquering the stack
This is an idea that I've had for years, which revolves around the idea of the food chain on the internet, and changing your place in the chain. By becoming self-reliant, you can control your future, decrease costs, and increase sovereignty.

{{< hint danger >}}
**Keep in mind**  
Everyone has a different setup, so this is a general idea of what you should aim for, and won't go in depth on specific products due to product lifecycles being so short in tech.
{{< /hint >}}

### Hardware
This is the top of the food chain, and by far the most important part. Acquiring your own hardware is important since without controlling the hardware, you can be shut down at any moment by your service provider for any reason if they aren't happy with your content or users, which will affect your entire stack.

When starting out, I'd look into used desktops. This is the route that I took years ago, and am still satisfied wth. They're easy to transport and can be bought very cheaply from businesses that are selling their old supply as they upgrade.

### Networking
Networking and ISPs are the second most important part, since your network operator (usually your ISP) has total control over your services ability to be seen and reached by others. You can relocate hardware if you aren't able to get another ISP in your area due to monopolistic agreements that divide most cities into regions only served by one ISP.

The networking hardware that you choose is very important, especially if you choose to host at home. Do not choose a router that is owned by a big tech company, such as an Eero or Google Mesh wifi system. These devices phone home and provide your entire network topology to the tech giants. Yuck!

### Operating Systems
No Windows or MacOS allowed as your server operating system, period. Windows and MacOS both are known to track users deeply and without giving the user any meaningful way to opt-out.

Linux is the way to go. When starting out, I think you should choose Ubuntu Server, or another Debian based distribution for its ease of use and rock solid packaging as well as the amount of software that has precompiled binaries in the .deb format.

### Applications
Software is the hardest part of the process, since you need something that will be stable, secure, and not be abandoned by its developers months after you select it. Open source is the way to go. 



[^1]: Although IRC has become more centralized over the years, its still a decentralized protocol with no one server controlling everything.
[^2]: The term Web3 was coined in 2014, although didn't gain meaningful relevance until around 2020