---
title: Announcing Plume
published: 2026-09-20 09:30:42
author: Chris Kankiewicz
tags: [Code, Plume, PHP, Open Source]
---

<!-- excerpt -->
Today I'm happy to announce the first release candidate of [Plume](https://plume.pub),
a self-hosted, Markdown-powered, flat-file publishing platform. You can find the source on
[GitHub](https://github.com/PHLAK/Plume) and documentation at [docs.plume.pub](https://docs.plume.pub).

![Plume Screenshot](/files/announcing-plume/screenshot.png)
<!-- /excerpt -->


# What it does

At its core Plume is a publishing (i.e. blogging) platform. It's designed to
make writing and publishing simple and easy. Features include:

  - **Easy self-hosting:** Plume is Dockerized to make installation and
    self-hosting easy. And with [Plume Compose](https://docs.plume.pub) you can
    be up and running in as little as a few minutes.
  - **Everything is a file:** Posts and pages are plain Markdown in a flat-file
    structure. No database, no lock-in. Write locally and upload via SFTP, or
    keep everything in Git and sync automatically. The workflow is entirely up
    to you.
  - **Markdown everywhere:** Write in Markdown and get fully rendered HTML posts
    and pages, including [Shiki](https://shiki.style)-powered syntax
    highlighting.
  - **Built-in full-text search:** Pre-configured
    [YetiSearch](https://github.com/yetidevworks/yetisearch) so readers (and
    you) can find any post without wiring up an external service.

Additionally, Plume includes automatic light and dark modes and RSS feeds
generated for you.

# Why I built it

I'm not a prolific blogger but I do like to write occasionally, mostly
short-form posts on Twitter and Bluesky. Over time I grew tired of handing *my*
content to someone else's platform to publish. I wanted to fully own it.

Long-form writing had the opposite problem of too much friction. Whenever an
idea struck, the overhead of getting it published often killed my motivation
before I started. With Plume, publishing is as simple as creating a file and
writing.

# Built by a human

Much of the software written today is done with heavy AI involvement. Plume is
an exception. I spent the last year working on it in my spare time, initially
using no AI at all. Only recently have I adopted the use of AI, and only
sparingly, mostly for debugging, small pieces of code (e.g. tests) and
documentation help. However, every line exists because I put it there with
intention. This means I understand the application from top to bottom. The
architecture also stands on prior work. It's largely based on [Directory
Lister](https://www.directorylister.com), a project I created long before AI was
part of the conversation and have continued to maintain with little AI
assistance to this day.

I've also been building open source software for about 20 years and, while my
use of AI has increased, I still feel the need to understand every bit of code I
produce. That's not to say I'm perfect, I make mistakes like anyone else.
However, it does mean I know *how* and *why* everything works, which matters for
keeping Plume maintained for the foreseeable future.

For additional insight you can find more of my work on [GitHub](https://github.com/PHLAK).

# What's next

Until now I've been building the product *I* want. I'm sharing Plume today to
start collecting feedback on what *you* want and would love for you to help
shape its future. If you have any comments or ideas, drop us a line on the
[GitHub Discussions](https://github.com/PHLAK/Plume/discussions) board or
[Bluesky](https://bsky.app/profile/plume.pub). Longer term I'd like to expanded
the configuration options and add custom themes (experimental theme support is
already in place) so others can modify Plume to suit their personal style.

# How you can help

Most importantly, try it out. Install Plume, report bugs, submit your feedback
and ideas, talk about it, share it or, if you're feeling generous, [sponsor or
donate](https://github.com/sponsors/PHLAK).

Thanks, I hope you'll check out Plume!
