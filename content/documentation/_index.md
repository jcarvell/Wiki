+++
title = "Contributing Documentation"
weight = 100
+++

Contributing documentation is pretty straight forward, follow this basic guide to learn how.

## A brief history
This page was built with the [Hugo](https://gohugo.io/documentation/) framework & static site generator using the [Relearn theme](https://mcshelby.github.io/hugo-theme-relearn/) and hosted on [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).
Every commit to the main branch, will trigger a GitHub Action, causing the page to rebuild itself, this takes only a minute or two before the changes are updated. 
This structure provides a beautiful site, solid uptime, and the ability to even make edits in the GitHub web editor.

## Editing existing pages

{{% badge style="info" %}}Coming Soon{{% /badge %}}

---
## Creating new pages

{{% badge style="info" %}}Coming Soon{{% /badge %}}

---
## Creating new sections

{{% badge style="info" %}}Coming Soon{{% /badge %}}

---
## Learning the syntax

The syntax used here can be as simple Markdown (Discord uses this), however may get more advanced if you want something fancy.

The following two guides are excellent sources for learning Markdown:
- [Relearn Theme Docs](https://mcshelby.github.io/hugo-theme-relearn/cont/markdown/index.html)
- [Markdown Docs](https://commonmark.org/help/)

This framework also allows the use of HTML code instead of Markdown, however Shortcodes may be better suited to what you want to do.

The following two references may help you learn the Shortcodes that may be used:
- [Relearn Shortcodes](https://mcshelby.github.io/hugo-theme-relearn/shortcodes/index.html)
- [Hugo Shortcodes](https://gohugo.io/content-management/shortcodes/)

---
## Making local edits

In order to make local edits on your own machine, we will need to follow a couple steps:
1. [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if you do not already have it
1. [Install Hugo](https://gohugo.io/installation/) (Extended edition)
1. [Install Go](https://go.dev/doc/install)
1. Clone `https://github.com/YCP-Rev-Metrix/Wiki.git` in your favorite IDE or terminal
1. Open a Git terminal in the directory of your new repository. For VS users, this can be *(Toolbar) Git > Open in command prompt*
1. Launch a live server by calling `hugo serve` (git or wsl terminal)
1. Navigate a browser to `http://localhost:1313`
1. Make changes (mostly in content directory). After saving, you should see the page refresh live.
1. After making your changes, push or merge your changes back up to the main branch. Your changes will now be reflected on the WWW in a few minutes.