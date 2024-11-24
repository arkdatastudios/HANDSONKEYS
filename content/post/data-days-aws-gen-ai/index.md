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

I settled in and spent the rest of the hour provisioning my AWS Workshop Studio account while getting to know my first desk mate.

There were light refreshments available for breakfast, but on this day I passed.

I'm watching my figure.


## 10:00 AM

After a quick round of introductions, the AWS team gave attendees an overview to what the workshop would be covering during the day.

We were given a business case (*There are two companies going thru a merger. They are in the process of combining their databases with each other*) and a high level walkthru of the solution architecture we would be implementing using various Amazon services (*Amazon QuickSight, Amazon Bedrock, and Amazon Q were the my stars for the day*).

Amazon Quicksight was the first service we became familiar with. We used it to explore the data we would be working with. During the time, I felt that Quicksight was standard fair in terms of a BI experience, but my feelings changed during a future lab. More on this later. 

As the top of the hour approached, a question was rasied about if a "low code" or "pro code" experience was preffered by AWS.
 
From the teams answer, I was happy to learn about AWS's mission is to provide developers ***choice***. AWS prides itself on having both options of "no code" and "pro code" development at a user's disposal.

However, this event definetley leaned in the "no-code" direction, which was appropiate for a workshop setting. 

*Keyboard bangers rejoice. No debugging will be needed during these sessions.*

## 11:30 AM

After getting familiar with our use case and associated data, it was time to get building.

A foundational aspect to any Generative AI application is its knowledge base. A knowledge base is the library of information an application will refer to while it generates its content. It could be filled with images, videos, tables, pdfs, etc. 

For the workshop, our knowledge base would be comprised of .TXT and .JSON files.

Amazon Bedrock Knowledge Bases made this task a breeze. To configure, we used the Bedrock UI to point the location of our source data, select an embedding model, and configure an vector store. 

Once the knowledge base was set-up, we had a pretty cool RAG application up and running. We asked questions (i.e. *"What product has caused the most customer support tickets over the past year?*) and extracted insights from the model. At the end of this block, I took a look around the room to see how folks were doing. I could see their wheels turning as this was the first time a lot of them had put their hands on any AI that was not Chat-GPT. 

No matter your thoughts on if AI is good, bad or in the middle. One thing is for sure, people *want it*.

This workshop was proof.

## 12:30 PM

Lunch.

I had one and a half sandwhices. No sides though. I'll say I had one eye on my figure, the other on the plate.

More importantly, by this time, our duo had become a trio. We had a third join our table and we had a grand time. While these events are great for learning tech, my biggest takeaways come from the networking opportuninites.

This day was no diffentnt, and I can confidently say, what happens at Gen AI events, stay there...

Shoutout my deskmates...

# 1 PM

After lunch, it was time to set up our Agent.

No, we were not finding a date for [Scott Boras](https://en.wikipedia.org/wiki/Scott_Boras), but actually using **Amazon Bedrock Agents** to retrive customer data from our knowledge base.

[AI Agents](https://aws.amazon.com/what-is/ai-agents/) are AI programs that can interact with other AI systems, collect data, and make its own decisions.

The Bedrock Agent Console made this setup surprisingly efficient, as I was able to start utilizing my AI agent after 15-20 minutes of setup. A click here, a scroll there, and before I knew it, I was able to give my agent a customer ID and have the associated order history, support history, and other details reported back to me. 

One of my table mates, an experienced BI and Data executive, was blown away. Apparently this is a task he has done many times in his day to day, and the ability to have a simple query return curated information blew him away.

# 2 PM

Now that the AI system was built, we had to make it safe.

By implementing Guardrails, we ensured that our applications would not return any hateful, inflammatory, or otherwise dangerous information.

See [this episode](https://www.youtube.com/watch?v=R0Uqx9J9pR4&list=PLhr1KZpdzukd23aGzGWMa03afLZr3aJS7&index=5) of AWS's Data Strategy Unraveled to learn more about the world of Responsible AI.

# 2:30 PM

In our final session, titled Generative BI, we covered ways to generate data-driven stories and insights by using natural language with Amazon Q with QuickSight. It was here where my feelings on QuickSight went from "ehhh I've seen this before" to "I havent seen anyhting like this yet".

Specifically, the ability to create a few graphs and generate a report is what did it for me. Being able to bridge the gap between technical and non-technical stakeholders is an age old struggle, but after seeing a report generated in seconds that was filled with graphs and insights, I was left thinking about the art of the possible in terms of what this technology could do for my teams, past projects, and future engagements. 


To close the sessiong, we had an interactive quiz covering the topics we learned throughout the day. The curious ones that completed their labs early and filled out the accompanying worksheet found themselves very prepared for the quiz, and a special prize was given to the winner.

Even though I didn't win the prize, being able to experience the day had me feeling like a winner.


# 4 PM CST (EOD)

What happens when a 30+ technologists walk into a bar? More networking!

During this time, I spoke with the other attendees and AWS staff to discuss the day over drinks and appetizers.

I passed on the apps, but did discover a love for Margherita Pizzas and Blueberry Moscow Mules. 

By this time in the day, my figure was no where in my sights.

There was too much great company around to look at anything else.

-- KEYS --

# Special Thanks

Special thanks to AWS's Khendr'a Reid, Manish Vazirani, Benson Tanner, and Travis Price for leading a great workshop!

And thanks to their partners BJSS for collaborating!


# Generative AI on AWS

Here are some good resources to learn more about Generative AI on AWS: 


### Data Strategy Unravelled: Creating Business Value with GenAI - Part 1 | Amazon Web Services

{{< youtube "8VtNW-bIIHA" >}}

### Building Terraform Projects with Amazon Q Developer

{{< youtube "JSjOUX3zVg8" >}}

### AWS PartyRock

Create your own AI apps!

[PartyRock](https://partyrock.aws/) is AWS's Gen AI Playground.

It's free, and all you need is am email.








