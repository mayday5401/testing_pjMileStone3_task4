# Readme 
## Contributors af

{% for student in site.students %}
  > <img src="{{ student.image }}">{: width="50" }
  > @[{{ student.name }}](https://github.com/{{ student.name }})
  > ({{ student.name }})
  > 
  >{{student.image}}
  >
  >{{ student.content }}
  >>
  >>
{% endfor %}

