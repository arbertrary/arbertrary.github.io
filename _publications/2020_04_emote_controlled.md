---
title: "Emote-Controlled: Obtaining Implicit Viewer Feedback Through Emote-Based Sentiment Analysis on Comments of Popular Twitch.Tv Channels"
collection: publications
permalink: /publication/2020_04_emote_controlled
excerpt: ''
date: 2020-04-19
venue: 'ACM Transactions on Social Computing, Volume 3, Issue 2, June 2020'
paperurl: 'https://dl.acm.org/doi/10.1145/3365523'
citation: 'Kobs, K., Zehe, A., Bernstetter, A., Chibane, J., Pfister, J., Tritscher, J., and Hotho, A.
(2020). &quot;Emote-controlled: Obtaining implicit viewer feedback through emote-based
sentiment analysis on comments of popular twitch.tv channels.&quot; <i>Trans. Soc. Comput.</i>,
3(2).'
---

# Abstract

In recent years, streaming platforms for video games have seen increasingly large interest, as so-called esports have developed into a lucrative branch of business. Like for other sports, watching esports has become a new kind of entertainment medium, which is possible due to platforms that allow gamers to live stream their gameplay, the most popular platform being Twitch.tv. On these platforms, users can comment on streams in real time and thereby express their opinion about the events in the stream. Due to the popularity of Twitch.tv, this can be a valuable source of feedback for streamers aiming to improve their reception in a gaming-oriented audience. In this work, we explore the possibility of deriving feedback for video streams on Twitch.tv by analyzing the sentiment of live text comments made by stream viewers in highly active channels. Automatic sentiment analysis on these comments is a challenging task, as one can compare the language used in Twitch.tv with that used by an audience in a stadium, shouting as loud as possible in sometimes nonorganized ways. This language is very different from common English, mixing Internet slang and gaming-related language with abbreviations, intentional and unintentional grammatical and orthographic mistakes, and emoji-like images called emotes. Classic lexicon-based sentiment analysis techniques therefore fail when applied to Twitch comments.

To overcome the challenge posed by the nonstandard language, we propose two unsupervised lexicon-based approaches that make heavy use of the information encoded in emotes, as well as a weakly supervised neural network–based classifier trained on the lexicon-based outputs, which is supposed to help generalization to unknown words by use of domain-specific word embeddings. To enable better understanding of Twitch.tv comments, we analyze a large dataset of comments, uncovering specific properties of their language, and provide a smaller set of comments labeled with sentiment information by crowdsourcing.

We present two case studies showing the effectiveness of our methods in generating sentiment trajectories for events live streamed on Twitch.tv that correlate well with specific topics in the given stream. This allows for a new kind of implicit real-time feedback gathering for Twitch streamers and companies producing games or streaming content on Twitch.

We make our datasets and code publicly available for further research.

## Bibtex

```bibtex
@article{10.1145/3365523,
author = {Kobs, Konstantin and Zehe, Albin and Bernstetter, Armin and Chibane, Julian and Pfister, Jan and Tritscher, Julian and Hotho, Andreas},
title = {Emote-Controlled: Obtaining Implicit Viewer Feedback Through Emote-Based Sentiment Analysis on Comments of Popular Twitch.Tv Channels},
year = {2020},
issue_date = {April 2020},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {3},
number = {2},
issn = {2469-7818},
url = {https://doi.org/10.1145/3365523},
doi = {10.1145/3365523},
journal = {Trans. Soc. Comput.},
month = apr,
articleno = {Article 7},
numpages = {34},
keywords = {emotes, feedback, sentiment analysis, Twitch}
}
```