---
layout: post
title:  "Spiegeln zweier Festplatten mit rsync"
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
