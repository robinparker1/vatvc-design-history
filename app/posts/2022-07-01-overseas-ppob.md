---
title: Overseas Principle place of business
description: Changing an overseas principle place of business
date: 2022-07-01
---


Previously in the service, if a user wanted to set their principal place of business (PPOB) as an overseas location, then they would have to call HMRC. On the service, their address would show as HMRC’s Aberdeen office. Our design change was to allow users to set their principal place of business as anywhere in the world, which we achieved by altering the content that read “The address does not have a post code” to “The address does not have a postcode or is outside the UK” and from that page, allowing a user to enter any country, rather than it defaulting to the United Kingdom.

One design that we played with was asking users up front whether their PPOB is inside or outside of the UK, however it added a lot of complexity to the journey for a user group that would make up a small minority of the people using the journey. We were able to remove a technical blocker meaning that we could override the United Kingdom preset to the address field, meaning that we could embed the journey to create an overseas PPOB into the existing journey.


<!-- **Change trading name - before design changes**

![alt text](/trading-name/a1-trading-name.png)

![alt text](/trading-name/a2-trading-name.png)

![alt text](/trading-name/a3-trading-name.png)
 -->
