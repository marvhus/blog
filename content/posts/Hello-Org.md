+++
title = "Hello Org"
author = ["martin"]
date = 2022-10-29
lastmod = 2022-10-29T14:27:21+02:00
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
    identifier = "hello-org"
    weight = 2001
+++

## This was written using org mode {#this-was-written-using-org-mode}

Yes you read that correctly, this post was written in orgmode, and generated for use with hugo using ox-hugo.


## [ox-hugo](https://github.com/kaushalmodi/) {#ox-hugo}

it's a plugin for emacs, that exports org files to markdown files usable with hugo.
So with the use of this emacs plugin, I might start writing posts here, so keep an eye out for that.


## installing ox-hugo {#installing-ox-hugo}

Installing the plugin wasn't as easy as I first thought it would be.
Part of that might be because I use my own custom emacs config, instead of using a pre-existing one like Doom emacs, and Spacemacs.
Though I managed to get it working with some manual instalation.


## use-package {#use-package}

Funnily enough, it wasn't ox-hugo that was causing the issues.
It was the package they used in the install guide that caused the issues.

For some reason, the package `use-package` wouldn't propperly install.
So I had to manually clone the repo to my emacs config, then `git checkout` the latest version.
And from there it was smooth sailing.


## using ox-hugo {#using-ox-hugo}

Luckily using the package wasn't as complicated as the installation.
I just write an org file (that you can see on [The GitHub Repo](https://github.com/marvhus/my-blogg)),
and then I just press `C-c C-e H h`, and it makes the markdown file for me.


[//]: # "Exported with love from a port written in Org mode"
[//]: # "- https://github.com/kaushalmodi/ox-hugo"