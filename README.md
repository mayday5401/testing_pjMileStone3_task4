# Readme 
## Contributors aq

{% for student in site.students %}

<pre>>> <img src="{{ student.image }}">{: width="50" }@[{{ student.name }}](https://github.com/{{ student.name }})({{ student.name }})
        >> {{ student.content }}
</pre>
{% endfor %}
