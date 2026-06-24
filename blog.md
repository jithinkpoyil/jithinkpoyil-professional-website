---
layout: default
title: Blog
permalink: /blog/
---

# Blog and news

This section can be used for short professional updates, publication notes, project summaries, technical explainers,
conference notes, and tutorials.

<div class="post-list">
  {% for post in site.posts %}
    <article class="post-preview">
      <p class="post-date">{{ post.date | date: "%B %-d, %Y" }}</p>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
      <a href="{{ post.url | relative_url }}">Read more →</a>
    </article>
  {% endfor %}
</div>

## Suggested post ideas

- Notes on EMFAC and regulatory emissions inventory workflows.
- Lessons from air quality monitoring QA/QC.
- Practical differences between MOVES and EMFAC outputs.
- Using machine learning for ozone forecasting without losing interpretability.
- PM<sub>2.5</sub> source apportionment in industrial coastal airsheds.
