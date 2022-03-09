# gamedevspace.github.io

A sample blog creation using Jekyll and Pages

## My Posts

{% for post in site.posts %}
  <article>
    <h2>
        <a href="{{ site.url }}{{ post.url }}">
            {{ post.title }}
        </a>
    </h2>
  </article>
{% endfor %}

Some more text