---
layout: page
title: Release History
permalink: /release-history/
description: Jekyll's built-in [blogging feature](http://import.jekyllrb.com/) could be a good way to communicate changes and updates to the design system. See [Material Design's What's New page](https://material.io/guidelines/material-design/whats-new.html) for inspiration.
---

<div>

    {% for post in site.posts %}
		<div class="c-block">
			<h2 class="c-block__heading"><a href="{{ post.url | prepend: site.baseurl }}" class="c-block__link">{{ post.title }}</a></h2>
			<div class="c-block__desc">
				{{ post.content }}
			</div><!--end c-block__desc-->
		</div><!--end c-block-->
    {% endfor %}
	
</ul><!--end c-block-list-->
