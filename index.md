---
layout: page
title: CS294-189: Fall 2025
# nav_exclude: true
permalink: /

seo:
  type: Course
  name: CS294-189: Designing CS Education at Scale
nav_order: 1
---

# CS294-189: Designing CS Education at Scale


{% if site.projects %}
## Fall 2025 Projects
<ul>
{% for project in site.projects %}
  <li style="margin: 1em 0;">
    <strong>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    </strong>
    {% if project.class_type %}
      <strong class="label label-purple">Class Type: {{ project.class_type }}</strong><br/>
    {% endif %}
    {% if project.description %}
      <p>
      {{ project.description }}
      </p>
    {% endif %}
    {% if project.authors %}
      <strong>Authors:</strong>
      <ul class="authors">
        {% for author in project.authors %}
          <li>
            {% if author.url %}
              <a href="{{ author.url }}">{{ author.name }}</a>
            {% else %}
              {{ author.name }}
            {% endif %}
            {% if author.email %} (<a href="mailto:{{ author.email }}">{{ author.email }}</a>){% endif %}
          </li>
        {% endfor %}
      </ul>
    {% endif %}
    <hr/>
  </li>
{% endfor %}
</ul>
{% endif %}
