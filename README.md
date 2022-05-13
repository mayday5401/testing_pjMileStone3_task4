# Readme 
## Contributors ac

{% for student in site.students %}
  > <img src="{{ student.image }}">{: width="250" }
  > <@{{ student.name }} alt="https://github.com/{{ student.name }}">
  > ({{ student.name }})
  > 
  >>{{ student.content | markdownify }}
  >>
{% endfor %}

