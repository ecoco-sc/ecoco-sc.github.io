---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for fitxa in site.fitxes %}

  <h2>
    <a href="{{ fitxa.url }}">
      {{ fitxa.title }}
    </a>
  </h2>
  
{% endfor %}
