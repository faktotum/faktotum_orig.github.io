---
layout: post
title:  "How to mirror two harddisks under OS X with rsync"
date:   2014-01-05 22:44:27
categories: mac shell backup
lang: de
---

Einfaches Spiegeln zweier Festplatten.

{% highlight bash %}
sudo /Users/foo/bin/rsync -vvaHX \
 --delete --exclude=.Spotlight-V100 --exclude=/.Trashes --progress \
 /Volumes/Source/ /Volumes/Target
{% endhighlight %}
