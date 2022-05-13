# Readme 
## Contributors 42

{% for student in site.students %} <br />
{{ student.content }} = &#187;{{ student.content }}
  &nbsp;&nbsp;&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ student.null }}&#187;{{ student.content }}
{% endfor %}

{% for student in site.students %} <br />
&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br /> 
{{ student.content }}
{% endfor %}
<html>
<head>
<style>
         p {
            padding:5px;
            border:1px solid black;
            color:green;
            font-size:24px;
 
          }
         #p2{
             display:inline;
          }
</style>
</head>

