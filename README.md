# Readme 
## Contributors 33

{% for student in site.students %} <br />
  &nbsp;&nbsp;&nbsp&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
<html>
<head>
<style>
p {
  text-indent: 50px;
}
p:first-letter {
    padding-left: 50%;
}
</style>
</head>
<body>
<p>&#187;
{{ student.content }}</p>

  &nbsp;<h2>{{ student.null }}&nbsp;&#187;{{ student.user }}</h2>

{% endfor %}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</body>
</html>
