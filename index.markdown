---
layout: default
title: Sparkhoom' Blog
---

Hi there, I am [Sparkhoom](resume.html), right now I am doing a start-up business with my college friends.
This site is basically my learning and thinking blog. Hope you will enjoy it.
Thank you.

<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><b>Find me on:</b></p>

<ul>

<li><a href="http://github.com/sparkhoom/">Github</a></li>

</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>
176072396@qq.com
</blockquote>

