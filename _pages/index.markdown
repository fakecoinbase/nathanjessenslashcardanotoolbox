---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /
---

<h3 class="f3 near-black mt0">Tools</h3>

<ul class="list pl0">
  {% for tool in site.data.tools %}
  <li class="mb3 relative">
    <a href="{{ tool.link }}" class="db link bg-white hover-bg-dark-white primary f3 h-100 pa4 {{tool.class}}" target="_blank">
      <h3 class="f3 mv0 tc">{{ tool.name }}</h3>
      <p class="f5 fw5 mt2 mb0 tc">{{ tool.description }}</p>
    </a>
  </li>
  {% endfor %}
</ul>
