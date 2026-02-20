---
layout: default
title: Insights & Research
---

# Insights & Research
*Thought leadership on AI Governance, Cyber Resilience, and Enterprise Architecture.*

<hr style="border: 0; border-top: 1px solid #eee; margin: 20px 0;">

{% for post in site.posts %}
<div style="margin-bottom: 40px; display: block; width: 100%;">
  <h2 style="margin-bottom: 5px; font-size: 1.6em;">
    <a href="{{ post.url }}" style="text-decoration: none; color: #2c3e50;">{{ post.title }}</a>
  </h2>
  
  <p style="color: #7f8c8d; font-size: 0.9em; margin-bottom: 10px;">
    <strong>Published:</strong> {{ post.date | date: "%B %d, %Y" }}
  </p>
  
  <p style="line-height: 1.6;">
    {{ post.excerpt | strip_html | truncatewords: 30 }}
  </p>
  
  <a href="{{ post.url }}" style="color: #2c3e50; font-weight: bold; text-decoration: underline;">Read Full Article →</a>
</div>
<hr style="border: 0; border-top: 1px solid #f9f9f9; margin: 20px 0;">
{% endfor %}

<br>
<p><a href="/" style="font-weight: bold;">← Back to Home</a></p>