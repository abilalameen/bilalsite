---
title: Document Automation – Manually review vs Auto validation- AI
date: 2023-01-10 12:39
tags:
  - AI Builder
  - PowerAutomate
  - technical
social_image: /media/image-3-768x284.png
description: I recently discovered that when Document Automation is used out of
  the box, the documents are auto-validated*. I will briefly in this note
  explain where you can change that.
---
<!--StartFragment-->

**Document Automation is a solution that is built using PowerAutomate, AI builder and Powerapps. So you need to think and view it like any other solution you install in your environment.**

**Step-by-step**

Once the solution is installed, you will get the following view.

<!--EndFragment-->

![](/media/image-1-768x263.png)

<!--StartFragment-->

Click **“View Solution”**

This will lead you to the following screen:

<!--EndFragment-->

![](/media/image-4-768x273.png)

<!--StartFragment-->

Open “**Document automation base kit**” and filter “**Cloud Flows**” here you will find “**Document Automation Validator**” flow,

**Open and edit the “Document Automation Validator” flow**:

<!--EndFragment-->

![](/media/image-5-768x456.png)

<!--StartFragment-->

If you want all the documents to be manually reviewed, change the following step in the flow to **false**.

<!--EndFragment-->

![](/media/image-6.png)

<!--StartFragment-->

**Now all the documents will have to go through manual review:**

<!--EndFragment-->

![](/media/image-10-768x310.png)

![](/media/image-8-768x413.png)

<!--StartFragment-->

For more advanced changes to the flow, you will have to understand PowerAutomate. To start learning PowerAutomate please check: <https://docs.microsoft.com/en-us/learn/modules/get-started-flows/>

\*They are not really auto-validated, there is more logic to it, but I kept this post simple for the beginners

<!--EndFragment-->