# Introduction
This is Team N, and here is the list of things we are going to do:

* Task 1: Starting issues and assign them to each groupmate

* Task 2: Create project board

* Task 3: Set up readme.md

* Task 4: Show your team to the Internet

* Task 5: Keep checking...

* Task 6: Write C code

* Task 7: Get a status badge

* Task 8: Promote your repo

*Summary: we are going to learn to use github by setting up a simple repo using functions built by github.*

---

# Code
```c
{% include_relative code.c %}
```
![](https://github.com/csci3251-2021/project-team-n/workflows/project-team-n/badge.svg)
 
# Contributor
{% for member in site.stu %}
  <h2>
    <a href="https://github.com/{{ member.user }}">
      {{ member.user }} - {{ member.name }}
    </a>
  </h2>
  ![image]({{ member.image }})
  <p>{{ member.content | markdownify }}</p>
{% endfor %}

Last updated: {{ site.time }}
