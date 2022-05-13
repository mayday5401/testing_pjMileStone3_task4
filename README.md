# Readme 
## Contributors ak

{% for student in site.students %}
  $>> <img src="{{ student.image }}">{: width="50" }@[{{ student.name }}](https://github.com/{{ student.name }})({{ student.name }})

    $>>{{ student.content }}
{% endfor %}

