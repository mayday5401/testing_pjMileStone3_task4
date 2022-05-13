# testing_pjMileStone3_task4
## Contributors
{% for students in site.students %}
  <h3>{{ students.user }} - {{ students.image }} - {{ students.name }}</h3>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}


{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
