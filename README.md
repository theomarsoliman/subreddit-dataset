# Subreddit Dataset

**When posts actually get engagement in 144 subreddits.** Per hour, per community, with the sample size shown for every row.

> Built and maintained by **[Peeklens](https://peeklens.ai?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset)**, which finds the Reddit threads where someone is asking for a product like yours. The per-subreddit pages are free and need no account: **[browse them here](https://peeklens.ai/best-time-to-post?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset)**.

All times are **UTC**. Day 0 is Sunday. Generated .

![Where each subreddit's best hour falls](https://raw.githubusercontent.com/theomarsoliman/subreddit-dataset/main/images/all-subreddits-heatmap.png)

## The finding

There is no universal best time to post on Reddit.

Across 144 subreddits, the single best hour lands in **93 of the 168 weekly slots**, and the most crowded slot in the entire week holds just **4 subreddits**. The most common single best hour is **15:00 UTC**, and it applies to only **13 of 144** communities.

So advice like "post Monday at 9am EST" is right for a handful of subreddits and wrong for the rest. The useful question is what *your* community does.

![Every community has its own rhythm](https://raw.githubusercontent.com/theomarsoliman/subreddit-dataset/main/images/subreddit-comparison.png)

## What is in here

| File | Contents |
|---|---|
| [`data/subreddits.csv`](data/subreddits.csv) | One row per subreddit, best two windows |
| [`data/subreddits.json`](data/subreddits.json) | Full records, top five windows each |
| `data/heatmaps/{subreddit}.json` | Complete 7x24 hourly grid |

## Top 50 by weekly active users

| Subreddit | Weekly active | Best window (UTC) | Second best | Posts analysed | Full heatmap |
|---|---:|---|---|---:|---|
| [r/ChatGPT](https://reddit.com/r/ChatGPT) | 1,862,369 | Tue 11:00 | Sat 18:00 | 31 ⚠️ | [view](https://peeklens.ai/subreddit/ChatGPT?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/ClaudeAI](https://reddit.com/r/ClaudeAI) | 1,569,379 | Thu 15:00 | Mon 11:00 | 15 ⚠️ | [view](https://peeklens.ai/subreddit/ClaudeAI?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/sysadmin](https://reddit.com/r/sysadmin) | 907,213 | Tue 11:00 | Mon 02:00 | 63 | [view](https://peeklens.ai/subreddit/sysadmin?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) | 859,630 | Mon 15:00 | Mon 19:00 | 55 | [view](https://peeklens.ai/subreddit/LocalLLaMA?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/OpenAI](https://reddit.com/r/OpenAI) | 642,541 | Thu 03:00 | Mon 10:00 | 52 | [view](https://peeklens.ai/subreddit/OpenAI?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/selfhosted](https://reddit.com/r/selfhosted) | 601,701 | Fri 17:00 | Sun 05:00 | 49 ⚠️ | [view](https://peeklens.ai/subreddit/selfhosted?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/cscareerquestions](https://reddit.com/r/cscareerquestions) | 595,994 | Mon 19:00 | Tue 15:00 | 67 | [view](https://peeklens.ai/subreddit/cscareerquestions?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/homelab](https://reddit.com/r/homelab) | 574,942 | Mon 19:00 | Tue 20:00 | 54 | [view](https://peeklens.ai/subreddit/homelab?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/Accounting](https://reddit.com/r/Accounting) | 396,310 | Tue 21:00 | Mon 15:00 | 79 | [view](https://peeklens.ai/subreddit/Accounting?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/webdev](https://reddit.com/r/webdev) | 382,161 | Sat 16:00 | Fri 02:00 | 60 | [view](https://peeklens.ai/subreddit/webdev?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/SideProject](https://reddit.com/r/SideProject) | 333,785 | Mon 16:00 | Thu 21:00 | 56 | [view](https://peeklens.ai/subreddit/SideProject?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/software](https://reddit.com/r/software) | 331,765 | Tue 01:00 | Sat 15:00 | 77 | [view](https://peeklens.ai/subreddit/software?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/cybersecurity](https://reddit.com/r/cybersecurity) | 327,704 | Fri 08:00 | Mon 06:00 | 77 | [view](https://peeklens.ai/subreddit/cybersecurity?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/smallbusiness](https://reddit.com/r/smallbusiness) | 323,580 | Fri 06:00 | Tue 22:00 | 91 | [view](https://peeklens.ai/subreddit/smallbusiness?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/Entrepreneur](https://reddit.com/r/Entrepreneur) | 266,998 | Tue 20:00 | Tue 05:00 | 74 | [view](https://peeklens.ai/subreddit/Entrepreneur?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/AI_Agents](https://reddit.com/r/AI_Agents) | 264,421 | Thu 05:00 | Wed 11:00 | 70 | [view](https://peeklens.ai/subreddit/AI_Agents?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/artificial](https://reddit.com/r/artificial) | 258,714 | Thu 16:00 | Sun 19:00 | 70 | [view](https://peeklens.ai/subreddit/artificial?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/digitalnomad](https://reddit.com/r/digitalnomad) | 251,755 | Fri 15:00 | Fri 20:00 | 85 | [view](https://peeklens.ai/subreddit/digitalnomad?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/SaaS](https://reddit.com/r/SaaS) | 241,191 | Tue 01:00 | Tue 13:00 | 55 | [view](https://peeklens.ai/subreddit/SaaS?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/graphic_design](https://reddit.com/r/graphic_design) | 235,106 | Sun 08:00 | Fri 20:00 | 59 | [view](https://peeklens.ai/subreddit/graphic_design?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/ExperiencedDevs](https://reddit.com/r/ExperiencedDevs) | 214,439 | Thu 15:00 | Thu 12:00 | 71 | [view](https://peeklens.ai/subreddit/ExperiencedDevs?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/programming](https://reddit.com/r/programming) | 209,017 | Sat 06:00 | Fri 13:00 | 83 | [view](https://peeklens.ai/subreddit/programming?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/sales](https://reddit.com/r/sales) | 199,261 | Fri 10:00 | Fri 13:00 | 80 | [view](https://peeklens.ai/subreddit/sales?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/rust](https://reddit.com/r/rust) | 142,438 | Wed 05:00 | Wed 23:00 | 81 | [view](https://peeklens.ai/subreddit/rust?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/PromptEngineering](https://reddit.com/r/PromptEngineering) | 139,287 | Thu 15:00 | Wed 11:00 | 67 | [view](https://peeklens.ai/subreddit/PromptEngineering?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/remotework](https://reddit.com/r/remotework) | 134,790 | Sat 07:00 | Wed 13:00 | 61 | [view](https://peeklens.ai/subreddit/remotework?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/devops](https://reddit.com/r/devops) | 128,682 | Wed 08:00 | Sun 16:00 | 80 | [view](https://peeklens.ai/subreddit/devops?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/consulting](https://reddit.com/r/consulting) | 121,766 | Sat 17:00 | Sat 05:00 | 90 | [view](https://peeklens.ai/subreddit/consulting?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/MachineLearning](https://reddit.com/r/MachineLearning) | 119,294 | Tue 17:00 | Thu 15:00 | 85 | [view](https://peeklens.ai/subreddit/MachineLearning?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/dataengineering](https://reddit.com/r/dataengineering) | 115,807 | Thu 10:00 | Wed 21:00 | 86 | [view](https://peeklens.ai/subreddit/dataengineering?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/Python](https://reddit.com/r/Python) | 109,066 | Mon 15:00 | Sat 18:00 | 84 | [view](https://peeklens.ai/subreddit/Python?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/startups](https://reddit.com/r/startups) | 108,045 | Mon 23:00 | Sun 09:00 | 80 | [view](https://peeklens.ai/subreddit/startups?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/aws](https://reddit.com/r/aws) | 103,383 | Mon 07:00 | Mon 15:00 | 92 | [view](https://peeklens.ai/subreddit/aws?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/opensource](https://reddit.com/r/opensource) | 98,143 | Mon 15:00 | Sun 03:00 | 84 | [view](https://peeklens.ai/subreddit/opensource?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/socialmedia](https://reddit.com/r/socialmedia) | 96,327 | Sun 19:00 | Wed 20:00 | 94 | [view](https://peeklens.ai/subreddit/socialmedia?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/dotnet](https://reddit.com/r/dotnet) | 95,571 | Sun 17:00 | Fri 00:00 | 85 | [view](https://peeklens.ai/subreddit/dotnet?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/UXDesign](https://reddit.com/r/UXDesign) | 94,650 | Tue 03:00 | Thu 20:00 | 77 | [view](https://peeklens.ai/subreddit/UXDesign?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/golang](https://reddit.com/r/golang) | 90,318 | Fri 20:00 | Thu 03:00 | 85 | [view](https://peeklens.ai/subreddit/golang?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/Wordpress](https://reddit.com/r/Wordpress) | 90,271 | Fri 15:00 | Wed 21:00 | 83 | [view](https://peeklens.ai/subreddit/Wordpress?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/datascience](https://reddit.com/r/datascience) | 89,879 | Sat 02:00 | Mon 11:00 | 93 | [view](https://peeklens.ai/subreddit/datascience?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/humanresources](https://reddit.com/r/humanresources) | 79,093 | Mon 21:00 | Sun 07:00 | 91 | [view](https://peeklens.ai/subreddit/humanresources?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/ProductManagement](https://reddit.com/r/ProductManagement) | 77,652 | Wed 00:00 | Tue 13:00 | 80 | [view](https://peeklens.ai/subreddit/ProductManagement?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/reactjs](https://reddit.com/r/reactjs) | 71,478 | Sun 02:00 | Tue 13:00 | 94 | [view](https://peeklens.ai/subreddit/reactjs?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/LLMDevs](https://reddit.com/r/LLMDevs) | 68,502 | Mon 10:00 | Tue 18:00 | 92 | [view](https://peeklens.ai/subreddit/LLMDevs?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/marketing](https://reddit.com/r/marketing) | 64,550 | Wed 01:00 | Sun 12:00 | 92 | [view](https://peeklens.ai/subreddit/marketing?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/WorkOnline](https://reddit.com/r/WorkOnline) | 64,499 | Sat 02:00 | Wed 23:00 | 94 | [view](https://peeklens.ai/subreddit/WorkOnline?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/docker](https://reddit.com/r/docker) | 62,766 | Sun 16:00 | Fri 12:00 | 96 | [view](https://peeklens.ai/subreddit/docker?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/SocialMediaMarketing](https://reddit.com/r/SocialMediaMarketing) | 62,187 | Sun 12:00 | Mon 22:00 | 93 | [view](https://peeklens.ai/subreddit/SocialMediaMarketing?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/shopify](https://reddit.com/r/shopify) | 61,730 | Mon 14:00 | Thu 20:00 | 86 | [view](https://peeklens.ai/subreddit/shopify?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |
| [r/kubernetes](https://reddit.com/r/kubernetes) | 59,742 | Sat 15:00 | Tue 09:00 | 82 | [view](https://peeklens.ai/subreddit/kubernetes?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) |

Full table in [`data/subreddits.csv`](data/subreddits.csv). ⚠️ marks low-confidence rows, see Limitations.

## How it was built

1. For each subreddit, the top posts of the past year were collected via a commercial Reddit API.
2. Each post was bucketed by its UTC day and hour of creation.
3. A bucket's engagement score is mean upvotes plus twice mean comments, normalised to 0-100 within that subreddit's own grid. Comments count double because they signal discussion rather than a passing upvote.
4. The five highest-scoring buckets become that subreddit's best windows.

Engagement is **relative to the subreddit itself**. A 100 in a small community is not comparable to a 100 in a large one.

![When each subreddit's single best hour falls](https://raw.githubusercontent.com/theomarsoliman/subreddit-dataset/main/images/best-hour-distribution.png)

## Limitations, please read

- **Correlation, not causation.** These are hours when well-performing posts happened to be published. Posting at 03:00 UTC will not rescue a bad post.
- **Sample sizes vary**, roughly 15 to 100 posts. `posts_analyzed` is in every file, and three subreddits are flagged `confidence: low` (under 40 posts or under 25% grid coverage). Treat those as directional.
- **Median grid coverage is 39%** of the 168 weekly hours. Most communities simply have no posts in many overnight hours, so those cells are empty rather than zero-engagement.
- **Top posts only**, which biases toward what worked. Not a random sample.
- **A snapshot**, not a live feed. Communities drift. Check `last_updated`.
- Two subreddits were excluded for having only 1 and 8 analysable posts.

## Licence

Data is [CC BY 4.0](LICENSE-DATA), so commercial use is fine with credit. Code is [MIT](LICENSE).

Attribution: `Subreddit Dataset by Peeklens (https://peeklens.ai)`

## Who made this

[Peeklens](https://peeklens.ai?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) monitors Reddit for conversations where someone is actively asking for a product like yours, scores them by buying intent, and drafts a reply you post from your own account.

Free, no account needed: [r/SideProject](https://peeklens.ai/subreddit/SideProject?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) · [r/webdev](https://peeklens.ai/subreddit/webdev?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset) · [best time to post](https://peeklens.ai/best-time-to-post?utm_source=github&utm_medium=dataset&utm_campaign=subreddit-dataset)

## Contributing

Want a subreddit added? Open an issue with the name and why it is useful. Corrections and methodology critiques are welcome, especially if you can show a bucket is wrong.
