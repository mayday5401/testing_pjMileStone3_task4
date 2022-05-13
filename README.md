# Readme 
## Contributors 37

{% for student in site.students %} <br />
  &nbsp;&nbsp;&nbsp;&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
  <p>{{ student.null }}&#187;{{ student.content }}</p>
{% endfor %}




<html>
<head>
<style>
p:first-letter {
    padding-left: 0%;
}
</style>
</head>
<body>
{% for student in site.students %} <br />
  &nbsp;&nbsp;&nbsp;&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
<head>  
<style>
p:first-letter {
    padding-left: 20%;
}
</style>
</head>
  <p>{{ student.null }}&#187;{{ student.content }}</p>
{% endfor %}
<p>{{ student.null }}&#187;{{ student.content }}</p>

<h2>{{ student.null }}&#187;{{ student.user }}</h2>

{% endfor %}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</body>
</html>
