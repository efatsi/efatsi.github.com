---
layout: page
title: ELI'S VIGEBLOG
tagline: 
---

</br>

<div class="span9">
  {% for post in site.posts %}
    <div class="span2">
      <div class="date">
        {{ post.tagline }}
      </div>
    </div>
    <div class="span6">
      <div class="post-head">
        <a href="{{ post.url }}">{{ post.title }}</a>
        <div class="line">
          
        </div>
      </div><br />
      <div class="post-content">
        {{ post.content }}
        <em>Posted on {{ post.date | date_to_long_string }}.</em><br /><br /><br /><br />
      </div>
    </div>
  {% endfor %}
</div>

