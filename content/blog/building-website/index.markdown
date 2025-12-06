---
title: "Building website using RStudio"
subtitle: ""
excerpt: "Notes on building my personal blogdown website"
date: 2025-12-01
author: "Qiyao Pan"
draft: false
images:
series:
tags:
categories:
layout: single
---

Over the past few days, I've been experimenting with different ways of building a website using RStudio. It turns out that creating an RStudio website project and deploying it on Github is simple and incredibly flexible! GitHub is full of templates to model after, now the only question is: which framework works the best?

The most common choice is [Jekyll](https://jekyllrb.com/), since it's the framework Github uses to  host sites right from GitHub repositories. One big perk is the large user community, with plenty of detailed guides for popular themes like [al-folio](https://github.com/alshedivat/al-folio). The al-folio theme covers nearly everything I need for an academic website, (and maybe one day I'll use al-folio too) but I’m just curious to explore what else is out there.

[Hugo](https://gohugo.io/) is another widely used framework with an equally large selections of themes. I’ve noticed a few scholars using Hugo, and the aesthetics are great. Hugo can also be deployed on Github, but it takes [a few extra steps](https://gohugo.io/host-and-deploy/host-on-github-pages/) or it can be launched on other free static site hosts like Netlify. 

As I searched for more themes, I came across [Quarto](https://quarto.org/), which turns out to be perhaps the most flexible option out there. Even more exciting, I found a Quarto Academic Website Template developed by a CUNY professor affiliated with the same center as I am! For people interested in migrating their websites to Quarto, there are a few examples out there. 

I’d say Quarto offers the most convenient way to build a website, and it’s perfect for creating a course site or project page. However, I am not entirely satisfied with the built-in themes that Quarto offers, , and customizing them can take quite a bit of work. (I'll save that challenge for the future me lol)

Right now I'm setting in to create a blogdown website using the [Hugo Apéro](https://hugo-apero-docs.netlify.app/) theme in RStudio. It may be a bit more of a hassle to customize and add new content compared to Quarto, but the theme’s aesthetics grabbed me instantly. 

So here it is! I’ll share more updates soon. Stay tuned!
