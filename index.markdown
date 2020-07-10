---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div class="mt5">
  <p class="lh-copy f4 tl measure-narrow">
    Nana is an Accra-based software engineer, currently working at Petra Trust.
  </p>
</div>

<div class="mt5">
  <h2 class="b dib w-auto">Articles</h2>
  <ul>
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
