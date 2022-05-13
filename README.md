# Readme 
## Contributors 47

{% for student in site.students %} <br />
  <p>&nbsp;&nbsp;&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#187;{{ student.content }}</p>
{% endfor %}

{% for student in site.students %} <br />
<p>&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
<span>&#187;{{ student.content }}</span></p>
{% endfor %}
