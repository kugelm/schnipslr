
Was sich so an Schnipsln ansammelt:

<ul>
  {% for post in site.posts %}
    <li>
	    <a href="{{ post.url }}"><b>{{ post.title }}</b></a><br /> 
	  
	  <br />
	  {{ post.excerpt }}
       {% if post.date %}
          {{ post.date | date: "%B %e, %Y" }}
	     {% else %}
          (ohne Datum)
	     {% endif %}
	     <br />
	   <hr />
    </li>
  {% endfor %}
</ul>
