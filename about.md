---
layout: page
permalink: /about/
title: About Me
tags: [Jekyll, diy, home improvement, Drake's Brewhouse, Dennis Rogers]
image:
  feature: breakfast.jpg
date: 2014-02-10
---

My name is Dennis Rogers. I am a web developer living and working in Indiana, and mostly trying not to make things worse.

> "Shorts over six inches are capri pants, shorts under six inches are European."
> - Ron Swanson

<figure class="third">
    <img src="{{ site.url }}/images/avatar.jpg" alt="avatar" />
    <img src="{{ site.url }}/images/avatar-2.jpg" alt="avatar-2" />
    <img src="{{ site.url }}/images/avatar-3.jpg" alt="avatar-3" />
</figure>

I closed on my first home on {{ page.date | date: "%B %d, %Y" }}. This blog will be my attempt to chronicle the process of renovating the house to make it more livable, and add to its value. I'll be relying on the experience and knowledge of my dad, and probably a little labor from two of my brothers, and documenting the process along the way.

As a web developer, I'll be living in the house and telecommuting while doing the renovations. And probably tweaking this site as time goes on.

{% if site.owner.email %}
* <a href="mailto:{{ site.owner.email }}"><i class="icon-envelope"></i> Email</a>
{% endif %}
{% if site.owner.twitter %}
* <a href="http://twitter.com/{{ site.owner.twitter }}"><i class="icon-twitter"></i> Twitter</a>
{% endif %}
{% if site.owner.facebook %}
* <a href="http://facebook.com/{{ site.owner.facebook }}"><i class="icon-facebook"></i> Facebook</a>
{% endif %}
{% if site.owner.google_plus %}
* <a href="{{ site.owner.google_plus }}"><i class="icon-google-plus"></i> Google+</a>
{% endif %}
{% if site.owner.linkedin %}
* <a href="http://linkedin.com/in/{{ site.owner.linkedin }}"><i class="icon-linkedin"></i> LinkedIn</a>
{% endif %}
{% if site.owner.github %}
* <a href="http://github.com/{{ site.owner.github }}"><i class="icon-github"></i> GitHub</a>
{% endif %}
{% if site.owner.stackexchange %}
* <a href="{{ site.owner.stackexchange }}"><i class="icon-stackexchange"></i> Stackexchange</a>
{% endif %}
{% if site.owner.instagram %}
* <a href="http://instagram.com/{{ site.owner.instagram }}"><i class="icon-instagram"></i> Instagram</a>
{% endif %}
{% if site.owner.flickr %}
* <a href="http://www.flickr.com/photos/{{ site.owner.flickr }}"><i class="icon-flickr"></i> Flickr</a>
{% endif %}
{% if site.owner.tumblr %}
* <a href="http://{{ site.owner.tumblr }}.tumblr.com"><i class="icon-tumblr"></i> Tumblr</a>
{% endif %}