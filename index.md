---
layout: page
title: 
tagline: Tracking Eli's exciting summer at Viget Labs in Boulder, CO
---

</br>

<div class="span7">
{% for post in site.posts %}
<!-- <div class="well"> -->
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2><br />
{{ post.content }}
<em>Posted on {{ post.date | date_to_long_string }}.</em>
<br />
<!-- </div> -->
<br /><br />
{% endfor %}
</div>


