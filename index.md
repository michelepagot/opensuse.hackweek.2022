---
title: Opensuse h4ckweek 2022
toc: true
---

# Opensuse hackweek 2022 - navigation log

This project is about writing and running a set of tests for a GUI application using openQA.
This project is also about reading and digesting the Wezterm documentation and become a ninja of its lua configuration system.

[Project page](https://hackweek.opensuse.org/projects/give-back-to-wezterm)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Backlog and ideas

* Research and contact the opensuse Wezterm package maintainer
* Look at where to start from (openQA)
  - where to let the test run?
  - where to version the test code (test/lib/schedule): in os-autoinst-distri-opensuse or on the wezterm repo directly (I like more the second one but I'm not sure if it is feasible)
* try to start natively to code test in python?
* look at how to trigger:
  - Wezterm github action
  - monitoring osd for Wezterm package

## Documentation and link collection

- [openQA doc](http://open.qa/docs/)
- [Wezterm doc](https://wezfurlong.org/wezterm/)
- [Wezterm repo](https://github.com/wez/wezterm)
- Lua
- [Jekyll and github pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
