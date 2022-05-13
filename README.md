# Readme 
## Contributors ae

{% for student in site.students %}
  > <img src="{{ student.image }}">{: width="50" }
  > @{{ student.name }}>
  > ({{ student.name }})
  > 
  >{{student.image}}
  >
  <span>{{ student.content | markdownify }}<span>
  >>
  >>
{% endfor %}

