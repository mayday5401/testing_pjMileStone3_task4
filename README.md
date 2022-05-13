# Readmea
## Contributors

{% for student in site.students %}
  >{{ student.image }}
  <@{{ student.name }} alt="https://github.com/{{ student.name }}"> ({{ student.name }})
  >>{{ student.content | markdownify }}
  >>
  >><img src="{{ student.image }}" alt="{{ student.image_alt }}">
{% endfor %}

