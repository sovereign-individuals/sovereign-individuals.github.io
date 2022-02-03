---
layout: post
title:  "Project Idea: AutoBisq"
date:   2021-02-01
categories: bitcoin
---

I believe that the best use case for Bitcoin at the current stage of adoption is as storage of value, that is for saving. In the past 12 years Bitcoin served this purpose better than anything else.

One of the best ways to save is to set up automatic contributions. This has been the recommended strategy for various types of saving, and I had very good experience with it myself. Rather than checking the price many times a day and burning energy on deciding when to buy and how much, you just decide how much you can invest, set it up once, and forget it. You can do this with SwanBitcoin or Coinbase, but you are putting yourself on government's list, and you don't really own your bitcoins (unless you immediately move it to your own wallet, which is a manual step). You can [trust Coinbase to do what makes money for them](https://www.econoalchemist.com/post/coinbase-things-aren-t-as-they-seem). Yes, they will lock you out whenever it brings profit for them just like RobinHood recently did. *Wouldn't it be great if you could buy Bitcoin automatically with Bisq?* Bisq is a decentralized peer-to-peer exchange, which means it's really hard to control it by any single entity, and only the person you trade with knows about you. You own the keys.

*So here is an idea for a product:* You configure how often you want to purchase and how much, and this script does it for you, using Bisq and Zelle.

Bisq is adding [API](https://github.com/bisq-network/projects/issues/46), which means you can control Bisq through programming interface, ie. python. If you have Bank of America account, it supports Zelle through their website, which means you can control it with something like [Selenium](https://www.selenium.dev/documentation/en/webdriver/), again [possible through python](https://duo.com/decipher/driving-headless-chrome-with-python). Similarly, you could purchase Amazon eGift cards. You will also need to receive and read SMS for 2FA, which can be also done in a browser when using Google Voice number. If you want to send notifications through Signal, there is [commandline interface](https://github.com/AsamK/signal-cli). I believe those are all the components we need.

This would be a very limited prototype, but I think it could be super useful at least for technical people at first, and then we can build it up from there.

If you are interested in building this with me, let me know.
