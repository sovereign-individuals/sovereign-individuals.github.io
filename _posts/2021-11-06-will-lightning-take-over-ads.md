---
layout: post
title:  "Will Lightning take over Ads?"
date:   2021-11-06
categories: bitcoin lightning product-idea
---

If you think about it, Ads serve as a middleman. It enables people to pay online, especially people without access to standard banking, and also across different countries and payment systems:

*Content Creator ← Ads Platform ← Advertiser ← Content Consumer*

Content Creator can be someone posting interesting tutorials on YouTube or a successful blogger. They create content and eventually get paid by Ads Platforms like Google or Facebook. Content Consumer is someone watching these videos, but they don't pay directly. These videos are “free”. However, Content Consumers see and sometimes click ads, and eventually buy stuff from Advertisers. These can be completely unrelated products, like shoes. The Advertiser pays for these ads to Ads Platform and that's how the money eventually gets to the Content Creator. Yes, you guessed it right: everyone takes a cut.

This complicated model actually provides value. It solved some issues such as cross-border or cross-system payments: someone in Africa could click ads, and maybe even purchase something, using their local currency, and indirectly pay someone in America who created interesting YouTube video and eventually gets paid in dollars.

It seems like Lightning could simplify this model a bit:

*Content Creator ← Content Consumer*

Someone also needs to pay the platform, but that again could be done explicitly and automatically through Lightning. Content Creator can put some videos behind LN-paywall and most of it goes directly to them, while some percentage goes to the platform provider.

[Stacker.news discussion](https://stacker.news/items/4604)
