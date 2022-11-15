---
layout: post
title: Being Your Own Bank
subtitle: Welcome to the Lightning Network
cover-img: /assets/img/2022-10-29/byob_title.png
thumbnail-img: /assets/img/2022-10-29/byob_thumb.png
share-img: /assets/img/2022-10-29/byob_thumb.png
tags: [lighting, nodes, techinical]
author: Ian
---

One of the fundamental principles underpinning the Bitcoin revolution is the change in ownership and custodial responsibility of personal finances. The goal being to move people away from entities that can be considered opaque, overreaching and self-serving, in favor of a model where each individual is empowered to take responsible for managing their finances. Whether you are a full-on BTC maxi (psychopath 😉) or just starting out down the rabbit hole I think we can all agree that the traditional financial status-quo [read satan's-quo] is being tested and a new paradigm is forming that puts the control back in the hands of the customer.

In a way the curators of the current state are, themselves, partly to blame for their own downfall. Indeed, the willful arrogance with which the industry has failed to development/evolve over time has resulted in change being driven from the base upward and (as it seem to be) the one main outcome is likely to be a shift in the power balance. If you've not yet reviewed the content from the 2022 BTC conference I urge you to watch this talk by Jack Mallers (~30mins). He quite succinctly discusses the overall flaws within the current payment system of day-to-day consumer/merchant payments. Jack then after pulling back the proverbial curtain offers up what is inarguably a better system based on the solid monetary foundation of the BTC network.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=dD2-T7TX2rk" target="_blank"><img src="http://img.youtube.com/vi/dD2-T7TX2rk/0.jpg" 
alt="Mallers @ Bitcoin 2022" width="480" height="360" border="10" /></a>

In case you don't have time to watch the full video here are the **TLDR** notes:

- The current payment system is outdated, involving more parties than are needed to carry out transactions (banks talking to banks, talking to merchants)
- Lack of innovation (especially for merchants) has seen a continuous ~3% slice being taken from their pockets
- Cash finality and verifiability can be achieved and secured using the the BTC and Lightning networks at a fraction of the current cost and maintain near instant speed.

Over recent months I've personally renewed my efforts to understand, participate and contribute to the BTC ecosystem. This in turn naturally lead me to a keen interested in the Lightning Network (as the current forefront of this space) and, setting up and running my very own Lightning Node. I'll be honest I knew it was going to be a reasonably involved technical job (with my trusty Raspberry Pi) and I put it off over a year now. However, rather than sitting on my hands any longer I decided (with the boost from Jack's recent presentation) it was time to take the plunge. After all, if we can have self-sovereignty for the price of a couple of beers, or maybe a takeaway, (thanks inflation) then why shouldn't we?

This article covers a few of the different ways to get yourself up and running with you very own personal node. With this you can validate your own blocks, perform your own on-chain analysis and block exploration (**Don't Trust, Verify**) as well as set up your own secure censorship resistant payment system. You may be amazed, it turns out it is really quite easy to be your own Bank.

---

# The Tech-Involved Option

First up I'll start with the option I've selected, [RaspiBolt](https://raspibolt.org/){:target="_blank"}. This defiantly isn't for the anyone who doesn't have time to dedicate to the task or the patience. I opted for this method because I like the idea of building up the elements one at a time to see how all the pieces fit together.

![RaspiBolt](/assets/img/2022-10-29/raspibolt.jpg "Raspibolt Logo.")

This process assumes you've gone out and got your required setup equipment and are reasonably comfortable in executing commands via a terminal. It is very much a scratch build project where you layer up all of required functionality to build your secure node from all its constituent parts (Bitcoin core, security features, Electrum server, your own block explorer, Lightning client, remote connections etc.). If you have time and want to start a home project (perhaps with a son or daughter who is particularly interested in computers) then this could be a good place to start. Just remember though take your time and be methodical, I found trying to run before you can walk with just have you re-starting!

---

# The Polished UI (Point and Click)

Next up we have an alternative option that is extremely popular ([Umbrel](https://getumbrel.com/){:target="_blank"}). This is a great middle ground for someone who wants all the functionality of running their own node but then wants both a clean UI and access to a bunch of other Apps. It is a more straight forward project and is quite polished, it also opens up using your personal secure server for other items like secure photo sharing etc.

![Unbrel](/assets/img/2022-10-29/umbrel.jpg "Umbrel app store.")

Looking at the user guide it has just 10 Steps! Again it assumes you've gone and got your hardware but they also offer a recommend specification if you're starting from scratch. While I've not used Umbrel (yet) myself I know from others that this is a great platform to setup both for yourself and others. A friend of mine also successfully used it to orange pill older relatives and other family members.

---

# TLDR Version

Finally, another very popular option is [myNode](https://mynodebtc.com/){:target="_blank"}. Much like Umbrel this option offers a more out-of-the box solution with minimal setup or technical expertise required. They also go further in offering a one-stop-shop (if you're wishing to pay a little more but get it done all in one go) with their premium package. This package includes all the hardware and the premium version software to get you on your way in just 4 steps!

![myNode](/assets/img/2022-10-29/mynode.png "myNode app store.")

Definitely can see this as solid alternative to Umbrel as it offers access to a bunch of handy Apps making for a better user experience. There is also the option of paying for Premium Support and one-click updates which can be a bonus if you don't like the idea of spending a lot of time on maintenance or asking for help on discussion boards.

---

# Final Thoughts

I cannot stress enough just how enjoyable the process has been of learning (through trial and fair bit of user error) in building my own Lighting Node from scratch. That said I know it isn't for everyone. Thankfully, Umbrel and myNode (among others) have really knocked it out of the park in making it so easy to onboard folks to the network. This process of breaking down barriers and inclusivity I think is critical to the long term success of this new financial system being shaped as we speak. Not everyone will want to do the leg work of building everything from scratch, but it is in the interest of the whole network for as many people to go non-custodial as possible. The more nodes onboarded the better and easier the lighting network adoption will be.

The future is happening right now and it is up to us to choose to be part of it, or stand back and watch it pass us by.