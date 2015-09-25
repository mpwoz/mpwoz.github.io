---
layout: post
title:  "About this site"
date:   2015-09-23 17:04:07
permalink: "/about-this-site"
tags: meta jekyll blog
---

I've just finished porting my old website over to Jekyll.

Why? 

For one, to take advantage of the free static site hosting Github is nice enough to offer. In fact, that's the main reason.

I was already using another static site generator called [Wintersmith](http://wintersmith.io).
I recommend it a lot, actually. Especially if you like Node.js.
In my opinion, it's much better than Jekyll, both in features and ease of setup.
If I didn't want to use Github pages, then I would have stayed on it without a doubt.

It's just that I really like the ability to dynamically edit my site without having to check out, build, and ftp 
to a static http server. Because Github supports file editing via its web interface, it overcomes the one shortcoming
of all static site generators: that you can't dynamically edit their content without a rebuild.

In fact, I'm using a great tool called [Prose.io](http://prose.io), which provides a minimal interface for writing
content that's checked into Github.
This lets me edit or add posts on the fly, without having a development environment set up.

Say I'm on somebody's Windows laptop without Jekyll installed, and come up with an idea for a blog post.
With my old setup, I would have had to make note of it, wait until I got home, then write it and rebuild my site
on my development machine.

Now, I just visit prose.io/#mpwoz, write the post, and hit 'Save'. It gets checked into Github, and their automatic
Jekyll build publishes it immediately. Within a minute, the content is live at [mpwoz.com](http://mpwoz.com).

There may be a more powerful setup out there, or a more customizable one. I could host my own build/publish server.
I could even run Wordpress. But for now, this toolchain hits the sweet spot of scalability, simplicity, and
flexibility that I've been looking for for several years now (ever since discovering static site generators, in fact).

### Technologies Used

- [Prose.io](http://prose.io) for live editing Github pages.
- [Github Pages](https://pages.github.com/) for free static hosting.
- [Jekyll](https://jekyllrb.com/) for templating and static site generation.

