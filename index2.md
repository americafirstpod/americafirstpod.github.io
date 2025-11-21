---
layout: default
---
<div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
  <h1 class="project-name">{{ page.title | default: site.title | default: site.github.repository_name }}</h1>
  <h2 class="project-tagline">{{ page.description | default: site.description | default: site.github.project_tagline }}</h2>
  <div><a href="./subscribe.html" class="btn">Subscribe to the America First Podcast</a> <a href="https://entropystream.live/nickjfuentes" class="btn">Donate to Nick on Entropy</a></div>
</div>


<h1>Episodes</h1>

{% for post in site.posts %}
  <div style="border: 2px solid #000; padding: 10px; margin-bottom: 20px; border-radius: 5px;">
    <h3>{{ post.title }}</h3>

    {% if post.audio %}
    <audio controls>
      <source src="{{ post.audio }}" type="audio/mpeg">
    </audio>
    {% endif %}

  </div>
{% endfor %}

<h3>For more episodes:</h3>
<a href="https://rumble.com/c/nickjfuentes?e9s=src_v1_cbl" class="btn">Visit Nick's Rumble</a>&nbsp;&nbsp;&nbsp;&nbsp; or <a href="https://americafirst.plus/" class="btn">Visit americafirst.plus</a>
