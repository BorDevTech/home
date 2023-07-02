
<h1>welcome to home page</h1>
<nav>
  <ul>
    {% for doc in site.docs %}
  {% if doc.category == "navbar" %}
  <li>
    <a href="{{doc.url}}">{{doc.title}}</a>
  </li>
  {% endif %}
  {% endfor %}
  </ul>
</nav>
