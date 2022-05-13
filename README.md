# Readme 
## Contributors ab

{% for student in site.students %}
  > <img src="{{ student.image }}" alt="{{ student.image_alt }}">
  > <@{{ student.name }} alt="https://github.com/{{ student.name }}">
  > ({{ student.name }})
  > 
  >>{{ student.content | markdownify }}
{% endfor %}

