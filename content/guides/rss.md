---
title: "RSS - A Non-Endless Content Feed"
date: "2026-01-10T12:07:01-05:00"
draft: false
toc: false
images: 
  - /images/rss.png
tags: 
  - Technology
  - Lifestyle
---

## Why

The main purpose of having an RSS feed is to get content from various sources without a suggestion algorithm. If you haven't already, see my [post on suggestion algorithms](posts/suggestion_algorithms.md) for a more detailed breakdown of the effects of suggestion algorithms.

Although we want to escape suggestion algorithms, we still want to see content from sources that help us in some way. RSS is the long-forgotten protocol of how the internet was originally supposed to work, in a decentralized manner; we don't need to depend on huge platforms that have a financial interest in keeping your attention to see a video/article/post from someone we want to follow.

For example, YouTube has a plethora of useful content; I have learned many new skills from the content on YouTube that have helped me in my career and improved my day-to-day life. What I have *not* benefited from, however, is the countless hours I have spent scrolling through my recommended feed on YouTube's homepage, or the rabbit holes that show me content that will likely never be useful in my life. 

The difference between using YouTube as a tool and getting used by YouTube is intentionality. If I know what channels produce quality content that I want to subscribe to, I can subscribe anonymously* via RSS. If I need to discover channels for a new area of interest, I just search. In YouTube's case, all I need to do is turn off watch history and the recommended feed does not show up.

RSS is like a universal feed, where all you get is posts from sources you are subscribed to - YouTube channels, blogs, Odysee channels, news websites, podcasts, and much more. With some discipline, you can build a feed to match:

* Your goals and areas of interest
* The amount of time you have to spend consuming content

Most importantly, you will not have a suggestion algorithm that is fighting to keep your attention. 

## How to Set Up RSS on Mobile

{{< admonition type=note title="Note">}}
I am only going to cover mobile here (as opposed to desktop) because it is the easiest thing to transition to from social media platforms like X/Twitter, YouTube, Facebook, etc.
{{< /admonition >}}

Download an RSS feeder. There are various applications for your phone, computer, and tablet. Here are some:

* Android
    * Feeder ([GitHub](https://github.com/spacecowboy/Feeder), [Google Play](https://play.google.com/store/apps/details?id=com.nononsenseapps.feeder.play))
* iOS
    * NetNewsWire ([Website](https://netnewswire.com/), [App Store](https://apps.apple.com/us/app/netnewswire-rss-reader/id1480640210))

### YouTube Channels
Use [this website](https://newskeeper.io/tools/youtube-rss) to create an RSS feed from a YouTube channel. All you have to do is paste the link to the channel and it will give you options for what you want the feed to contain (all, vidoes, livestreams, shorts)

### Websites
You can subscribe to pretty much most websites via RSS and get notification of new posts or updates they make. To get an RSS link for the site, look for a sideways WiFi looking icon that is usually at the hdeader or footer of the website where they have links to the other social media platforms (you can see an example of this if you scroll to the bottom of my [home page](/)).

Some newer websites are dropping support for RSS in favor of logging in and creating an account (so they can collect your usage data), or subscribing to them on one of the major social media platforms. However, usually there is still an RSS feed on the site, it's just not advertised. To look for it, you can just try and guess the RSS URL in the RSS app by appending one of the following to the site URL:

* `/feed`
* `/rss`
* `.xml`
