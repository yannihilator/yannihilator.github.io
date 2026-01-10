---
title: "Suggestion Algorithms"
date: 2026-01-10T12:12:28-05:00
draft: false
toc: false
images:
tags: 
  - Technology
  - Lifestyle
---

Everyone is aware of "the algorithm" that pulls the strings behind the scenes to determine what content shows up on their feeds. In this post, I hope to go into a little bit more detail as to how this works, what the goals of the companies that program these algorithms are, and what can be done about it.

## The Feedback Loop
Every major platform nowadays has a feedback loop that is optimized to maximize user engagement (aka, keep you on their app as long as possible). Everything you do on X/Twitter, YouTube, is automatically tracked by your phone and sent to their servers to determine what content will keep you engaged on their platform.

At a **bare** minimum, this information includes:

* Content you consume
* Topics/tags the content is related to
* How long you engaged with that content before scrolling away from it

In real time, this information is fed into a machine learning algorithm, which takes these inputs as variables and calculates what content should be shown to you next to keep you engaged on their platform.

![Suggestion Algorithm No GenAI](/plantuml/suggestion_algorithms_no_genai.png)

Until recently, the content they can suggest to keep you engaged comes from a finite pool of what has been created by other people on the platform. Generative AI now allows for the **further** optimization of content to show you through these suggestion algorithms, but now this content comes from an **infinite** pool. In short, the effects that social media has had on the world will only be **intensified** with generative AI, unless people just leave the platforms altogether or don't fall victim to the suggestion algorithms.

![Suggestion Algorithm No GenAI](/plantuml/suggestion_algorithms_with_genai.png)

This feedback loop repeats endlessly until you make the decision to stop paying attention, something that will get harder as the content generation gets better.

## Their Incentive
Additionally, over a long period of time, the data that is collected **automatically** about what you consume gives these platforms the ability to build a profile about each user - what your interests, beliefs, associations are - **automatically**. They make money off of this information by selling this data to advertisers (in some cases, such as Google, they are the advertisers also) and other parties that are willing to pay for it, in addition to showing you ads that best suit your profile. These suggestion algorithms are so good at building a profile that they can seemingly predict things that you think or talk about.

## Do their Priorities Match Yours?
At this point, you should ask yourself - are the goals of these platforms in line with my own? Do I want to maximize my engagement with my phone/computer? Do they improve my relationships? Do I actually learn useful information? Do I mostly need to filter through slop to find something useful?

## Solutions
Thankfully, there are currently plenty of alternatives to getting the information you need, and ways to break the feedback loop described above. Here are the main areas to tackle on this:

* First, and most importantly, do not engage with the suggestion algorithms
    * This means deleting whatever platforms don't provide any benefit to your life, and/or turning off "suggested", "recommended", or "explore" feeds. Simply doing this means that even if you have to go on a platform to get some information, there is an intention behind it which decreases the likelihood of being sucked into a scroll
    * This does not mean to never consume any content. The best way to consume content without a suggestion algorithm is an [RSS feed](../../guides/rss/) that is curated to your goals and interests.
* Minimize the information that the platforms can collect on you. This breaks down into a couple of categories:
    * It is important to note, that if you are using a platform at all, the bare minimum amount of information is still being collected
    * Use [free software](https://en.wikipedia.org/wiki/Free_software) as much as possible. There is free software for basic functionalities you would expect from a computer/phone that are arguably better than the proprietary software that comes with your phone
* Take away the ability for platforms/advertisers to suggest content to you
    * Delete mobile apps and opt to use a web browser instead whenever possible. Apps get to collect far more information on your phone than anything else, and in addition, aren't vulnerable to blockers you may install
    * Install ad blockers on your web browser

I hope to create guides that will detail out specifics on all of these in the future.
