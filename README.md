##Contributors
{% for student in site.students %}
  >{{ student.image }}
  <@{{ student.name }} alt="https://github.com/{{ student.name }}"> ({{ student.name }})
  >>{{ student.content | markdownify }}
{% endfor %}
