---
layout: post
title:  "Export ReadKit link to Yojimbo using Keyboard Maestro"
date:   2014-01-17 23:29:44
tags: keyboardmaestro readkit yojimbo
---

You need [wget](https://www.gnu.org/software/wget/) for this. You can install *wget* with the [homebrew](http://brew.sh) package manager for OS X.

Open *Terminal.app*

    ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
    brew install wget


In [Keyboard Maestro](http://www.keyboardmaestro.com/) you need to create the following macro.

![keyboardmaestroscreenshot](/img/readkit2yojimbo.png)

