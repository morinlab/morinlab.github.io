---
layout: page
title: Publications
permalink: /Publications/
toggle: on
rank: 1
---

<div class="lab-wrapper">
    <ul class="lab-list">
    {% for project in site.data.projects %}
        <li>
            <h2>{{ project.name }}</h2>
            {% if project.collaborators %}
                <p><b>Collaborators: </b>{{ project.collaborators }}</p>
            {% endif %}
        </li>
    {% endfor %}
    </ul>
</div>
