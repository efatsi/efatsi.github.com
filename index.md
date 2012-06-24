---
layout: page
title: 
tagline: Tracking Eli's exciting summer <br /> at Viget Labs in Boulder, CO
---

</br>

<div>
	{% for post in site.posts %}
		<div class="post-head">
			<a href="{{ post.url }}">{{ post.title }}</a>
		</div><br />
		<div class="post-content">
			{{ post.content }}
			{% if post.title != "Day 10.5 - Saturday" %}
				<em>Posted on {{ post.date | date_to_long_string }}.</em><br /><br /><br />
			{% endif %}
		</div>
	{% endfor %}
</div>

