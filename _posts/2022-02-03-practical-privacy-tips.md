---
layout: post
title:  "Practical tips for privacy"
date:   2022-02-03
categories: privacy
---

Privacy means you decide what you share with whom. This is important, because when someone knows something about you, they can use it against you. For instance, to convince you to buy something through targeted ads, or something much worse.

Even if you live in a safe and stable country and you think you have nothing to hide, it's better to think about privacy, because what's accepted now might become dangerous opinion in the future, and the good government or corporation of today might easily turn bad tomorrow. And there is no delete on the internet.


### Define your threat model

It's impossible to get 100% privacy by using some fancy operating system or downloading an app. It's always a matter of how much someone wants to get you, and how much it costs to do so. Thus it's important to define the main threat models: what are you hiding from whom?

Who are you hiding information from? Common examples to consider: random person on the internet, your employer (ie. if you wanna work on a side project), your government (ie. if you are a journalist writing articles exposing something they don't want the world to know about), or specific person (ie. your ex-spouse, or high school lover who turned psycho).

What information do you wanna protect? Common examples to consider: physical location, ownership of some asset, opinions and interests.

And remember that your threat model might change as you grow older, and so it's good idea to revisit this every once in a while. Maybe once a year.

Most importantly, keep it simple.


### Separate your identities

Once you have your threat model defined, you can simplify it by deciding basic identities that you need to keep separate.

The most important one to guard is your _physical identity_: your DNA, your fingerprints, where you live, where you work, etc. This one is really hard to discard.

The other one could be your _public identity_: all the stuff you follow and post on Twitter, Reddit, Instagram, or write on a blog.

Then, you need separation of those identities. For each identity you need to decide who are you guarding against? Who should not be able to link the identity to your other identities, especially to your _physical identity_?

Let's say you just wanna make sure that random people on the internet can't link your _public identity_ with your _physical identity_, and thus can't come burn down your house just because of your opinions on Twitter. That means it's ok if the government, your ISP, or the companies whose apps you use, they all know that this _public identity_ is you. Then, you just need to use pseudonyms instead of your real identifiers (name, address, etc).

If you have an identity that's more likely to become a target, and you suspect that someone might do the work to hack one of those companies to be able to link your identities and find you, then you probably wanna separate that identity against your ISP, as well as the large corporations. You can accomplish that by using VPN and avoiding mobile phones for your _public identity_. That makes your VPN provider the bottleneck, so you wanna do your research and find a VPN provider you trust, and give them minimal information about you. And don't use the same VPN for your _physical identity_.

Qubes OS is good for maintaining multiple separate identities. I highly recommend [Insurgo](https://insurgo.ca/).

Using mobile phone for identities that you wanna keep unlinkable by governments or your carrier is pretty much no go. Might be possible, but really hard.

If there are locations you don't wanna link to your _physical identity_, don't bring your phone there.


### Look normal

Your _physical identity_ is the most important one, and there is bunch of public information about you already like where you own properties, receive mail, etc. If you wanna go crazy, there are tools to break those links, but I think the most practical solution is to be as normal as possible. Yes, eat at local restaurants, drive kids to school, buy stuff on Amazon, watch Netflix, and all that stuff. I think this is better than using VPN/Tor for everything, or not having any trace. You want a trace that looks very boring, normal, compliant.

Of course, you are interesting. You have opinions. You own bitcoin. But it's not linked to your _physical identity_. You talk to your friends in person or over Signal so only they know. You have _public identity_ to express ideas online and get feedback from people around the world. Maybe a _bitcoin identity_ to make it extra hard for anyone to know that you own some.

I personally lost all my bitcoins in a boat accident.


### Stay sane

Once you start going down this rabbit hole, learning about what the possible threats are, and all the tools out there that only works for something, it's gonna get very overwhelming. Don't panic. 

You need to find the right balance for you. You don't worry about getting run by a car every morning, do you? You can do a privacy review, maybe once a year. You define your threat model, prioritize the main threats, decide how to minimize them, considering the value and cost (how much energy will it cost to implement) and then just follow it and don't worry.

Keep it simple, and be consistent.

[Stacker.news discussion](https://stacker.news/items/10069)
