---
layout: page
title: Welcome!
# nav_exclude: true
permalink: /
seo:
  type: Course
  name: Berkeley Class Site
nav_order: 1
---

# UC Berkeley Class Site Template

A template for static UC Berkeley cla

{% if site.projects %}
## Fall 2025 Projects
<ul>
{% for project in site.projects %}
  <li>
    <strong>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    </strong>
    {% if project.class_type %}
      <strong class="label label-purple">Class Type: {{ project.class_type }}</strong><br/>
    {% endif %}
    {% if project.description %}
      {{ project.description }}
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
  </li>
{% endfor %}
</ul>
{% else %}
<p>No projects found.</p>
{% endif %}
