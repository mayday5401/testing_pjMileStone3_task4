# Readme 
## Contributors au

{% for student in site.students %} <br />
&nbsp;&nbsp;&nbsp;&nbsp; >><img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; >>{{ student.content }}<br />
{% endfor %}
