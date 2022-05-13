{% for staff_member in site.staff_members %}
  <h2>
    <a href="{{ site.baseurl }}{{ staff_member.url }}">
      {{ staff_member.name }} - {{ staff_member.position }}
    </a>
  </h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
