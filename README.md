{% for student in site.students %}
  <img src="{{ student.image }}" alt="{{ student.image_alt }}">
  <span>{{ student.content }}</span>
{% endfor %}
