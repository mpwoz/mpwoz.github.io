+++
title = "How This Site Works"
date = "2025-06-18"
description = "Description of how the site is set up"
+++

This post serves as a sort of README for my future self, to make setting up the
site for local development easier.

I've set up this site using [Zola](https://www.getzola.org/) and the [Tabi
theme](https://github.com/welpo/tabi). Here's how to set this up on another
computer, in case I (or you!) ever have to:

```
winget install zola
git clone --recursive https://github.com/mpwoz/mpwoz.github.io
cd mpwoz.github.io
zola serve
```

The `mpwoz.com` domain is hosted at
[Squarespace](https://account.squarespace.com/domains/managed/mpwoz.com). It
used to be registered at Google Domains but that shut down and got migrated to
Squarespace. I've got several other domains registered with Cloudflare, so at
some point I'll migrate this one too. One thing to note is that because this is
an old Google Domains account, you need to log into Squarespace with Google (not
email).

Finally, all the source is hosted (and served from) [Github
pages](https://github.com/mpwoz/mpwoz.github.io/settings/pages) since it's just
a static HTML site once it's built. The Github repo has a few CI actions that
build the site every time I commit, which lets me add posts or make small tweaks
without having everything set up locally.