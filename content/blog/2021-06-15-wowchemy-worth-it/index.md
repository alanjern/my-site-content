---
authors:
- admin
categories:
- Site info
date: "2021-06-15T00:00:00Z"
draft: true
featured: false
image:
  caption: 'Image credit: **[Kelly Sikkema](https://unsplash.com/@kellysikkema?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)** on **[Unsplash](https://unsplash.com/s/photos/frustrated?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash)**.'
  focal_point: ""
  placement: 2
  preview_only: false
#lastmod: "2020-12-13T00:00:00Z"
projects: []
subtitle: "Probably not. 😕"
summary: "I spent about a week migrating my personal website from Wordpress to Wowchemy. The result looks great, but in the end, I'm not sure I'd recommend most people do the same."
tags:
- wowchemy
- blogdown
- wordpress
title: Is building your personal website using Wowchemy and blogdown worth it?
---

## tl;dr

I spent the past week making this site using {{< icon name="r-project" pack="fab" >}} [blogdown](https://bookdown.org/yihui/blogdown/) and the [Wowchemy](https://wowchemy.com/) website building for Hugo and migrating all of the content from my previous Wordpress-based page. Despite some encouraging blog posts (like [this helpful one](https://alison.rbind.io/blog/2020-12-new-year-new-blogdown/) by Alison Hill) suggesting that doing this would be pretty easy, I found the process frustrating and tedious.

In this post, I share a bit of what I learned, but here's my most important lesson: **if you just want a basic site to share your papers and some other professional information, just use Wordpress, or something similar**.

## I just want to post my papers! 😩

I started with the [Wowchemy Starter Academic theme](https://github.com/wowchemy/starter-hugo-academic) and modified it.

This theme presents publications in a neat and professional way. (You can see mine [here](http://localhost:4321/#publications). Getting them there turned out to be much more of a pain than I expected. I thought the whole point of using markdown was that I could, for example, just write up a quick markdown document with my publications and then run a command and -- ta-da! 🪄 -- I get a beatiful rendering of my document. 

Not so simple.

Wowchemy handles publications is a somewhat complicated way that is not well documented.

First, you have to make 



## Overview

1. The Wowchemy website builder for Hugo, along with its starter templates, is designed for professional creators, educators, and teams/organizations - although it can be used to create any kind of site
2. The template can be modified and customised to suit your needs. It's a good platform for anyone looking to take control of their data and online identity whilst having the convenience to start off with a **no-code solution (write in Markdown and customize with YAML parameters)** and having **flexibility to later add even deeper personalization with HTML and CSS**
3. You can work with all your favourite tools and apps with hundreds of plugins and integrations to speed up your workflows, interact with your readers, and much more

{{< figure src="https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/master/academic.png" title="The template is mobile first with a responsive design to ensure that your site looks stunning on every device." >}}

## Get Started

- 👉 [**Create a new site**](https://wowchemy.com/templates/)
- 📚 [**Personalize your site**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/guide/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Wowchemy's future ❤️](https://wowchemy.com/plans/)

As a token of appreciation for sponsoring, you can **unlock [these](https://wowchemy.com/plans/) awesome rewards and extra features 🦄✨**

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

## Inspiration

[Check out the latest **demo**](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the **showcase**](https://wowchemy.com/user-stories/) of personal, project, and business sites.

## Features

- **Page builder** - Create *anything* with [**widgets**](https://wowchemy.com/docs/page-builder/) and [**elements**](https://wowchemy.com/docs/writing-markdown-latex/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://wowchemy.com/docs/writing-markdown-latex/), [**Jupyter**](https://wowchemy.com/docs/import/jupyter/), or [**RStudio**](https://wowchemy.com/docs/install-locally/)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://wowchemy.com/docs/customization/)
- **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 34+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Wowchemy and its templates come with **automatic day (light) and night (dark) mode** built-in. Alternatively, visitors can choose their preferred mode - click the moon icon in the top right of the [Demo](https://academic-demo.netlify.com/) to see it in action! Day/night mode can also be disabled by the site admin in `params.toml`.

[Choose a stunning **theme** and **font**](https://wowchemy.com/docs/customization) for your site. Themes are fully customizable.

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-modules/blob/master/LICENSE.md) license.
