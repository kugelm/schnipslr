
was sich so an Schnipsln ansammelt:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br /> 
       {% if post.date %}
          {{ post.date | date: "%B %e, %Y" }}
	     {% else %}
          (ohne Datum)
	     {% endif %}<!--  --><br />
	  {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
