---
layout: template.html
title: Chocolate Bars Project
tags: page
---

# This is my {{ title }}
Well Known Chocolate Bars
    <ul>
        {% for bar in bars -%}
            <li> {{bar}} </li>
        {% endfor -%}
    </ul>
