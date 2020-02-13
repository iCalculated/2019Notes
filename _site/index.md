Don't have high expectations.

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

If you have any suggestions feel free to submit a PR or if less familiar with GitHub open an [issue](https://github.com/iCalculated/2019Notes/issues/newcd)