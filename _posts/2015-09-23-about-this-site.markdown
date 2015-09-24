---
layout: post
title:  "How this site works"
date:   2015-09-23 17:04:07
permalink: "/about-this-site"
tags: blog meta
---

I've just rewritten my site to take advantage of github's free hosting. I was already using another static site
generator called wintersmith. It's a much better generator than Jekyll in my opinion, but unfortunately github
pages only supports Jekyll.

The reason I wanted native GHP support is so that I could use a neat tool called [Prose.io](http://prose.io).
It lets you access a github repository using a slick, minimalist UI and automatically commit to it from their site.
This lets me edit or add posts on the fly, without having a development environment set up.

Say I'm on a friend's Windows laptop, and come up with an idea for a blog post. I can just go to prose.io/#mpwoz, 
create the draft, and save it. It'll get committed to the repo and Github's Jekyll builder will publish it
automatically. This gives me the live-editing benefits of a CMS combined with the portability and robustness
of a static site generator.

## Technologies Used

- Jekyll
- Github Pages
- Prose.io
- Skeleton

