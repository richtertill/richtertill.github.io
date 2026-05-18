---
layout: page
permalink: /repositories/
title: code
description: A curated set of open-source projects associated with my research on self-supervised learning, multimodal foundation models, and generative dynamics for single-cell omics.
nav: true
nav_order: 4
---

These are the open-source repositories that accompany my publications. Each card links to the GitHub project. For the full list, see my [GitHub profile](https://github.com/{{ site.data.repositories.github_users | first }}).

{% if site.data.repositories.github_repos %}

<div class="repo-grid">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
