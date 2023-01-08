---
title: Are Birds Real?
summary: A short investigation into the BirdsArentReal movement.
tags:
  - Social Media
  - Twitter
  - Sentiment Analysis
  - Social Opinion Mining
date: '2023-01-08T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Aleksandar Pasaric on Pexels
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/fy_boateng
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Ah yes, yet again we are subject to seemingly unthinkable trends on the internet. I noticed a few months ago that the conspiracy *Birds Aren't Real* was blowing up on Twitter and Reddit, and I wondered if there was anything interesting about who was tweeting it, what they were tweeting about, and why. Welp, I'll give it a shot with the little information I've taught myself.

Wikipedia gives a great explanation of the origins of this theory: https://en.wikipedia.org/wiki/Birds_Aren%27t_Real

## Data - Where is it from?

I grabbed some data from the lovely Kaggle.com from both Reddit and Twitter. Whether I will use both of these datasets... time will tell.

https://www.kaggle.com/gpreda/birds-arent-real
https://www.kaggle.com/gpreda/birds-arent-real-on-twitter-either

I haven't a clue what exactly to do now, but I think I'll start with an exploratory data analysis (EDA) to get an idea of what potential patterns could be present in this data. There might not be any. That's okay too.

I have some theories about what I could potentially see in the data:

1) I have a feeling that Social Identity Theory will have some influence here. An example being that individuals will receive more downvotes if their post or comment is incongruous with the rest of the subreddit.

2) "[This](https://journals.sagepub.com/doi/full/10.1177/1368430220987596)" study influences my second theory. I feel that similar findings will be present here, and that there will be a strong presence of aggressive words, dividing language, etc. I'll use the main words and themes found here to see if their findings are applicable and able to be replicated in this context.

Generally speaking, I have lot of specific questions: What social factors tend to be associated with being more active in the group? Are there certain demographics that are more active than others? What emotional aspects seem to be present in these groups?

I'm not too sure if I even know how to answer these questions yet, but there's no harm in learning as I go along. 

With all of that out of the way, now it's time to get into the data! 

