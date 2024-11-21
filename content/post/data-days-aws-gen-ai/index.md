---
title: Data Days - Gen AI with AWS
description: Experience the power of generative AI with AWS
date: 2024-11-20 00:00:00+0000
tags: 
    - AWS
    - Generative AI
    - Data Management
    - Data Days
categories:
    - Data Days
    - Generative AI
    - AI
    - AWS
image: cloudflare_post.png
---

I was recently able to attend AWS's [Generative AI Innovation Day](https://aws-experience.com/amer/smb/e/2fe30/dallas-genai-innovation-workshop) in Dallas.

Here's how it went:



-----

## 9:00 AM CST

Upon entering the AWS office, I was promptly greeted by staff members that helped me get checked into the event.

With badge in hand, I headed down the hall, and into the conference room to find my seat.

I got settled in and spent the rest of the hour provisioning my AWS Workshop Studio account while getting to know my first desk mate.

There were light refreshments available for breakfast, but on this day I passed.

I'm watching my figure.


## 10:00 AM CST

After a quick round of introductions, the AWS team gave attendees an overview to what the workshop would be covering during the day.

We were given a business case (There are two companies going thru a merger. They are in the process of combining their databases with each other) and a high level walkthru of the solution architecture we would be implementing using various Amazon services (Amazon QuickSight, Amazon Bedrock, and Amazon Q were the my stars for the day).

Then HANDS ON KEYS time began...

Amazon Quicksight was the first service we became familiar with. We used it to explore the data we would be working with, and I found this experience to be the standard BI experience. More on this later. 

As the top of the hour approached, a question was rasied about if a "low code" or "pro code" experience was preffered by AWS.
 
From the teams answer, I was happy to learn about AWS's mission is to provide developers *choice*. AWS prides itself on having both options of no code and pro code development at developers disposal.

However, this event was definetley leaning in the "no-code" direction, as it is definetely the most appropiate form of development when there is a agenda to keep!

Keyboard bangers beware.

## 11:30 AM CST

Now that we were familiar with our use case and associated data, it was time to get building.

A foundational aspect to any generative AI application is its knowledge base. A knowledge base is basically the library of information an application will refer to while it generates its content. It could be filled with images, videos, tables, pdfs, etc. 

For the workshop, our source data would be comprised of .TXT and .JSON files.

Amazon Bedrock Knowledge Bases made this task a breeze. To configure, we used the Bedrock UI to point the location of our source data, select an embedding model, and configure an vector store. 

Once complete, we had a pretty cool RAG application at our disposal that we could ask questions and extract insights. By the end of this part of the workshop, I could see the wheels turning in the minds of all attendees, including myself.

Even though the use case was "simple", I could only imagine what the true power/ possibility of Gen AI could be **when done correctly**.



## Save and Deploy

Once you have set up your build configuration, click **Save and Deploy**. 

When the deployment is complete, Cloudflare will provide an unique URL for your to view your site!



# Learning Resources

Here are some good resources to check out to continue your web development journey: 


### Deploy your website for free with Cloudflare Pages and GitHub!

{{< youtube "MTc2CTYoszY" >}}

### Set Up a Portfolio Website with Hugo

{{< youtube "6MKW4gzLItU" >}}

### Clouflare Pages Docs
The best tech advice you will ever get?

[Read the docs.](https://developers.cloudflare.com/pages)






