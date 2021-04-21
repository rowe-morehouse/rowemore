+++
author = "Rowe Morehouse"
title = "Rich Content"
filename = "rich-content.md"
draft = "false"
date = "2020-03-22"
# lastmod = ""
description = "A descripton of the uncertainty and risk article."
summary = "This is the summary of the uncertainty and risk article"
#tags = [
#    "shortcodes",
#    "privacy",
#]
+++

Hugo ships with several [Built-in Shortcodes](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes) for rich content, along with a [Privacy Config](https://gohugo.io/about/hugo-and-gdpr/) and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.
<!--more-->
---

## YouTube Embed

{{< youtube SgeAxcbNo1c >}}

<br>

---
## Twitter Simple

{{< twitter_simple 1085870671291310081 >}}

<br>

---
## Twitter

{{< twitter 1382363239204466699 >}}

<br>

---
## Gist

{{< gist rowe-morehouse 3c1a1922740f5ca1754cc60a1a0222d8 >}}

<br>

---
## Figure

{{< figure src="./../../../images/www-550x360.png" title="The 3 Ws" >}}

<br>

---
## todo
 
{{< todo "note for programmer">}}


Look in here for additional shortcodes, as used in the documentation:
/Users/dickhertz/dev/hugo-playground-20200421/docs/layouts/shortcodes/todo.html



<br>

---



## Instagram


---

## Highligt Code

<!-- https://gohugo.io/content-management/syntax-highlighting/ highlighting options -->

{{< highlight go "linenos=table,hl_lines=8 15-17,linenostart=199" >}}
// ... This is coded $$ 123 <b>
// ... code
// ... code
// ... code
{{< / highlight >}}



<br>



<br>

---

## Vimeo Simple Shortcode

{{< vimeo_simple 48912912 >}}
