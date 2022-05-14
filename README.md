# Readme 
## Contributors 57


{% for student in site.students %}
<img src="{{ student.image }}" alt="">
{% endfor %}

{% for student in site.students %} <br />
  &nbsp;&nbsp;&#187;<img src="{{ student.image }}">{: width="40" }@[{{ student.user }}](https://github.com/{{ student.user }})({{ student.name }}) <br/> 
  "&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» {{ student.content }}"<br /> 
{% endfor %}

{% for student in site.students %}     
<figure>   
   <img src="{{ student.image }}" style="width: 23px ;"/>  
     @<a href="https://github.com/{{ student.user }}">
      {{ student.user }}
     </a>
</figure>    
{% endfor %}
    
{% for student in site.students %} 

<p> »<img src="{{ student.image }}">{: width="40" }
  <a href="https://github.com/{{ student.user }}">
      @{{ student.user }}
  </a>
  ({{ student.name }})</p>
  
<p> »{{ student.content }} </p>
{% endfor %}
