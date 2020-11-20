# Welcome

You can find info about me [here](https://peymanmahdavi.github.io/).

<hr>

# Posts

<div class="posts">
  {% for post in site.posts %}
    {% unless post.draft %}  
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      {{ post.excerpt }}
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      <hr>
    {% endunless %}
  {% endfor %}
</div>