#### 分类

{% for categorie in site.categories %}
<span>
{{category[0]}}
</span>
{% endfor %}

#### 文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
