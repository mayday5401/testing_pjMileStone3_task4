{% for student in site.students %}
  <img src="{{ student.image }}" alt="{{ bird.student_alt }}">
  <span>{{ student.content }}</span>
{% endfor %}
