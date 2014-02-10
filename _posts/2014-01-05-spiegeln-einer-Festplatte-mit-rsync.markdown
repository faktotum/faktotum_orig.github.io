---
layout: post
title:  "How to mirror two harddisks under OS X using rsync"
date:   2014-01-05 22:44:27
tags: osx backup osx
lang: de
---

Simple command for mirroring two harddisks.

{% highlight bash %}
sudo /Users/foo/bin/rsync -vvaHX \
 --delete --exclude=.Spotlight-V100 --exclude=/.Trashes --progress \
 /Volumes/Source/ /Volumes/Target
{% endhighlight %}
