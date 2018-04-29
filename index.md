---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<ul>
{% for item in site.menus.header %}
  <li class="menu-item-{{ loop.index }}">
    <a href="{{ item.url }}" title="Go to {{ item.title }}">{{ item.title }}</a>
  </li>
{% endfor %}
</ul>
