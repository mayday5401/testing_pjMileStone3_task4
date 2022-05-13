# Readme 
## Contributors ad

{% for student in site.students %}
  > <img src="{{ student.image }}">{: width="50" }
  > <@{{ student.name }} alt="https://github.com/{{ student.name }}">
  > ({{ student.name }})
  > 
  >>{{ student.content | markdownify }}
  >>
  >>
{% endfor %}

