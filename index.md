#### 标签

#### 分类

{% for categorie in site.categories.CATEGORY %}
<span>
{{categorie}}
</span>
{% endfor %}

<h2>文章</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
