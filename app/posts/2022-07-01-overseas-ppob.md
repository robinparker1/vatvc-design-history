---
title: Overseas Principle place of business
description: Changing an overseas principle place of business
date: 2022-07-01
---


Previously in the service, if a user wanted to set their principal place of business (PPOB) as an overseas location, then they would have to call HMRC. On the service, their address would show as HMRC’s Aberdeen office. Our design change was to allow users to set their principal place of business as anywhere in the world, which we achieved by altering the content that read “The address does not have a post code” to “The address does not have a postcode or is outside the UK” and from that page, allowing a user to enter any country, rather than it defaulting to the United Kingdom.

![alt text](/overseas-ppob/overseas-ppob-4-0-02.png 'Initial UK-only journey')

![alt text](/overseas-ppob/overseas-ppob-4-0-03.png 'Initial UK-only journey, continued')


One design that we played with was asking users up front whether their PPOB is inside or outside of the UK, however it added a lot of complexity to the journey for a user group that would make up a small minority of the people using the journey. We were able to remove a technical blocker meaning that we could override the United Kingdom preset to the address field, meaning that we could embed the journey to create an overseas PPOB into the existing journey.


![alt text](/overseas-ppob/overseas-ppob-4-3-01.png 'Experimental journey with Yes/No routes')

---

![alt text](/overseas-ppob/overseas-ppob-4-4-01.png 'Updated journey with embedded capability for overseas addresses')

![alt text](/overseas-ppob/overseas-ppob-4-4-02.png 'Updated journey with embedded capability for overseas addresses, continued')

![alt text](/overseas-ppob/overseas-ppob-4-4-03.png 'Updated journey with embedded capability for overseas addresses, continued')
