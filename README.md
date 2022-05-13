# testing_pjMileStone3_task4
## Contributors
{% for students in site.students %}
  <h3>{{ students.user }} - {{ students.image }} - {{ students.name }}</h3>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
