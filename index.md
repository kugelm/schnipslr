
was sich so an Schnipsln ansammelt:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br />{{ page.date | date: "%B %e, %Y" }}
    </li>
  {% endfor %}
</ul>
