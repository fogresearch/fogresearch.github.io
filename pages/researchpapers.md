---
layout: page
show_meta: false
title: "Research Papers"
#subheadline: "Research papers related to "
#teaser: "These are your options to style the header of each webpage individually. <em>Feeling Responsive</em> uses <a href='http://srobbin.com/jquery-plugins/backstretch/'>Backstretch by Scott Robin</a> to expand them from left to right. The width should be 1600 pixel or higher using a ratio like 16:9 or 21:9 or 2:1."
permalink: "/researchpapers/"
---
<ul>
    {% for post in site.tags.researchpaper %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>