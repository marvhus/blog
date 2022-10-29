+++
title = "Writing Hugo blog in Org"
author = ["martin"]
date = 2022-10-29
lastmod = 2022-10-29T14:26:26+02:00
tags = ["hugo", "org"]
categories = ["emacs"]
draft = false
weight = 2001
foo = "ar"
baz = "zoo"
alpha = 1
beta = "two words"
gamma = 10
[menu]
  [menu.main]
    identifier = "writing-hugo-blog-in-org"
+++

## First heading withing the post {#first-heading-withing-the-post}

-   This post will be exported as
    `content/posts/writing-hugo-blog-in-org-file-export.md`.
-   Its title will be "Writing Hugo blog in Org".
-   It will have _hugo_ and _org_ tags and _emacs_ as category.
-   The _lastmod_ property in the front_matter is set automatically to the time of export.
-   The menu item _identified_ is auto-set.
-   The menu item _weight_ and post _weight_ if needed to have to be menually specified as shown above.


### A sub heading under that heading {#a-sub-heading-under-that-heading}

-   It's draft state will be marked as `true` brcause of `#+hugo_draft: true`

With the point <span class="underline">anywhere</span>, do `M-x RET ox-hugo RET` to export this whole fole titles _Writing Hugo blog in Org_ to a Hugo post.

The exported Markdown has a little comment footer set in the _Local Variables_ section bellow.


[//]: # "Exported with love from a port written in Org mode"
[//]: # "- https://github.com/kaushalmodi/ox-hugo"