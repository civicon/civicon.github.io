---
layout: post
title: I ♥ .txt (Workshop)
published: true
permalink: /i-heart-txt/
description: A workshop covering great free/open source and text-based technology for social scientists.
categories:
- blog
- teaching
lang: en
comments: true
tags:
- open source
- technology
- science
image:
  feature: http://dl.dropboxusercontent.com/u/5341489/images/keyboard-keys-2_crop.jpg
  caption: Red Alt Moffett Towers
  captionlink: https://www.flickr.com/photos/hjl/8205547070/in/photolist-dv6zgu-9bjAo7-5j1DP4-dfiJT-mMwh-idr62E-86wy7X-REYo4-cJNow-8n1pd-5cFeZ-9t3jTh-96Aq4R-8Lttyn-8JoDpy-89NEwb-7UyBLT-4SAVZF-BJXFt-upNTu-eBUHY-7XHGL-b4h6uT-6jZokA-k6TeEL-8pmRLD-5ANBA7-5D1MRE-6jkoD1-4w9Uum-22TxWf-DQShZ-9jeqKN-7KRgsP-771N9b-5Z1oAJ-4mQ7wM-4mkPs9-xu8t9-pmMRS-9REL1T-9hDq6M-fdL8b-8KRqq-9djcr8-tCZSi-6qpXH-9Q2PgS-92PYvZ-8Jsayx
  credit: Ho John Lee
  creditlink: https://www.flickr.com/photos/hjl/
  location:
  locationlink:
---

<div markdown="0"><a href="http://www.bigsss-bremen.de" class="btn btn-warning">These are some early sketches for a possible workshop at BIGSSS.</a></div>

Why bother? Because:

> Learning from hackers is learning to win.

Over the past few years of working on my PhD, I've spent a fair amount of time figuring out the best possible tech-setup.
Ok, to be honest, I procrastinated.
But: While I am still not a programmer (sadly), I've come to the conclusion that hackers have developed a set of great tools, technology and practices that are applicable to social scientists and other knowledge workers, too.

I thought I'd offer a workshop for whomever is interested in this.

<!--more-->


## Themes

Overall themes would include:

1. [(Free and) open source software (FOSS)](http://en.wikipedia.org/wiki/Free_and_open-source_software) enables [open science](http://en.wikipedia.org/wiki/Open_science).
If you control your own means of production, you also get to control access.
Also, FOSS and open science share a mode of production: both rely on recognition and collaboration – not property rights [^1].
2. Professional tools improve efficiency and self-sufficiency in academic writing.
You'll be faster and more focused on your work if you separate content from presentation.
If you can typeset and publish your own work, you cut a (closed science?) middleman, and get faster, too.
3. Text (not proprietary/binary) files future-proof your work and data.
`*.txt`, or, equivalently for data, `*.csv` can be opened and edited on pretty much *any* computer today, could be 30 years go, today, and probably still will be widely accessible in 30 years time.
Try that with, say, `*.doc`, or, even worse, `*.pages`.
Text files also give you control over your work and afford great transparency, something that is helpful to maintain *rigor* and *reproduceability*.
(Ever tried to *reproduce* a `*.doc`?)
Additionally, text (not proprietary/binary) files play nice with general-purpose versioning software and diff tools, such as [git](http://git-scm.com/).

[^1]: Not sure how the marxist lingo got in here.

## Tools & Programs

We might cover the following tools and programs:

1. [Markdown](http://daringfireball.net/projects/markdown/): A quick and easy, *human-readable* markup language for simple documents.
(Depending on the projects progress, we might also look at relevant markdown flavors including [scholarly](http://blog.martinfenner.org/2013/06/17/what-is-scholarly-markdown/) / [Markdown for science](https://github.com/karthik/markdown_science))
2. [LaTeX](http://www.latex-project.org/) is two things, really.
    1. a professional typesetting program that makes *real* pretty PDFs (et al.).
    2. and, arguably more important for the future, a fairly comprehensive, somewhat-human-readable, *markup* language with an incredibly rich and vibrant [package (a.k.a. plugins) community](http://www.ctan.org/) covering every conceivable academic need (think formulae, endnotes, glossaries, statistics, coding …).
3. [Git](http://git-scm.com/): An open source, *distributed* version control system.
4. [Github](https://github.com/) is three things:
    1. a commercial provider of hosted git repositories,
    2. a social network for developers (and academics?)
    3. a canonizer of clever conventions for collaboration (e.g. [pull requests](https://help.github.com/articles/using-pull-requests)) and central, well, *hub*.
4. Great general-purpose, medium-difficulty editors, including:
    - [Sublime Text](http://www.sublimetext.com/)
    - [Atom](https://atom.io/) (? – if sufficiently progressed/stable at the time)
    - … [^2]
5. [BibDesk](http://bibdesk.sourceforge.net/) (for OS X), and [JabRef](http://jabref.sourceforge.net/) (for Windows OS), both open source bibliography management tools.
Bibliographies are stored as human-readable text files `*.bib`.
6. [Skim](http://skim-app.sourceforge.net/) (for OS X), and Windows alternatives ([Sumatra PDF](http://blog.kowalczyk.info/software/sumatrapdf/free-pdf-reader.html)?), both open source PDF readers, including clever annotation.
7. [Pandoc](http://johnmacfarlane.net/pandoc/), the swiss-army knife for converting different markup formats (including all of the above).
8. As a bonus, [Jekyll](http://jekyllrb.com/), a neat tool that converts Markdown text files (`*.md`) into static, well-formated HTML.
For your project website, blog – you name it.
Can be hosted commercially, but for free via [Github Pages](https://pages.github.com/).
9. Obviously, [R](http://www.r-project.org/), the FOSS statistics project would also fit well into this tech stack, but its too big a topic and relevant only for quantative researchers.
There's also already plenty of resources [out there](https://www.coursera.org/course/rprog), including, I believe, classes at [BIGSSS](http://www.bigsss-bremen.de).

[^2]: Admittedly, neither Sublime Text nor Atom are free and/or open source – even though many of the plugins are. I just haven't had the guts to try out [vim](http://www.vim.org/) and [emacs](http://www.gnu.org/software/emacs/) yet – learning curve seems *really* steep.