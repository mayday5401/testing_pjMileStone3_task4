{% for bird in site.birds %}
  <img src="{{ bird.image }}" alt="{{ bird.image_alt }}">
  <span>{{ bird.description }}</span>
{% endfor %}
