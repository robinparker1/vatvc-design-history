---
title: Accounting view
description: This example was generated using a script and shows how to automatically include a list of screenshots at the end of your post.
date: 2022-06-13
screenshots:
  items:
    - text: Design history index
      src: 01-design-history-index.png
      caption: |
        You can include captions with each image, and each caption can include markdown. This is a screenshot of the [index page](/).
    - text: Search results
      src: 02-search-results.png
    - text: A design history post
      src: 03-a-design-history-post.png
---



Accounting View was a piece of work that started through user feedback that we saw through DeskPro comments and exit surveys. Users wanted a more ‘accounting type view’, and consequently the UX team had to research to uncover what that definition meant, and how we could change our existing Payment History page to reflect that user need. We uncovered that the current view on Payment History wasn’t clear in communicating charges that had been paid to a user from HMRC versus charges that a user had paid to HMRC.

We designed a view that used the accordion component to separate payments in relation to the VAT period that they paid for, however technically this was not possible as an API call would duplicate information, complicating the screens that users would see, negatively impacting the user experience. We stripped back the screen, therefore, to respond to the core user need of having a clearer view of charges to HMRC vs from HMRC. This resulted in a simple UI change, creating dedicated columns for these elements.



![alt text](/payment-history-4-0.png "Before")

![alt text](/payment-history-4-5.png "After")
