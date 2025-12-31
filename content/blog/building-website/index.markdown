---
title: "Building website with R"
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

Over the past few days, I've been experimenting with different ways of building a website with R. It turns out that creating an website project and deploying it on Github is simple and incredibly flexible! GitHub is full of templates to model after, now the only question is: which framework works the best?

The most common choice is [Jekyll](https://jekyllrb.com/), since it's the framework Github uses to  host sites right from GitHub repositories. One big perk is the large user community, with plenty of detailed guides for popular themes like [al-folio](https://github.com/alshedivat/al-folio). The al-folio theme covers nearly everything I need for an academic website, but I’m just curious to explore what else is out there.

[Hugo](https://gohugo.io/) is another widely used framework with an equally large selections of themes. I’ve noticed a few scholars using Hugo, and the aesthetics are great. Hugo can also be deployed on Github, and it only takes [a few extra steps](https://gohugo.io/host-and-deploy/host-on-github-pages/) to be hosted on Github, or it can be launched on other free static site hosts like Netlify. 

As I searched for more themes, I came across [Quarto](https://quarto.org/), which turns out to be perhaps the most flexible option out there. Even more exciting, I found a Quarto Academic Website Template developed by a CUNY professor! For people interested in migrating their websites to Quarto, there are a few examples [here](https://drganghe.github.io/quarto-academic-site-examples.html). 

I’d say Quarto offers the most convenient way to build a website, and it’s perfect for creating a course site or project page. However, I am not entirely satisfied with the built-in themes that Quarto offers, and customizing them can take quite a bit of work. So right now I created my website using the [blogdown package](https://github.com/rstudio/blogdown) and the [Hugo Apéro](https://hugo-apero-docs.netlify.app/) theme with R. 

Welcome to my website!