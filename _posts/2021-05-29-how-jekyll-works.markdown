---
layout: post
title:  "How Jekyll Works!"
date:   2021-05-29 13:59:45 +0530
categories: jekyll update
---

The Jekyll gem makes a `jekyll` executable available to you in your terminal.

The `jekyll` program has several commands but the structure is always:

jekyll command [argument] [option] [argument_to_option]

{% highlight ruby %}
Examples:
    jekyll new site/ --blank
    jekyll serve --config _alternative_config.yml
{% endhighlight %}

Typically you’ll use `jekyll serve` while developing locally and `jekyll build` when you need to generate the site for production.

For a full list of options and their argument, see [Build Command Options][command-options].

[command-options]: https://jekyllrb.com/docs/configuration/options/#build-command-options

