---
layout: post
title:  "GitHub Pages Not Deploying"
date:   2023-06-29 06:47:54 -0500
categories: blog
---

Yesterday afternoon, I was editing the CSS on this blog to fix things like tables, code blocks and the mobile navigation drop-down. I was tweaking color schemes in the Chrome inspection tools, grabbing the CSS from there and dropping it into my repo. At one point, I found out I couldn't deploy my changes any more.

I searched around for the answer, because I'm still a novice at GitHub pages. My deployments weren't happening quickly enough to hit the "soft limits" on a free account. I rolled back to a previous version of the CSS via my on-computer backup, with no luck. I even tried deleting the blog's repo and reloading the entire website, but it always stopped at the deployment stage, with one unpleasant message:

```
deploy is waiting for github-pages deployment approval
```

I couldn't even get a simple index.html loaded. But luckily, I wasn't the only person experiencing it. Other folks had posted on the GitHub subreddit and community discussions of the deployment issue. They shared the link to the [GitHub Status page](https://www.githubstatus.com/ "GitHub Status") which showed that yes, there was an outage for a good chunk of last night.

Luckily, the backup deployed this morning without issue, and I still have the blog. I'll eventually get around to posting non-blog-deployment stuff, but it's nice to finally get comfortable.