---
title: Our Team
css: our-team
staff:
- name: Cynthia Dahl
  role: Head of School
  quote: My goal is to foster a community that feels safe to grow both emotionally and intellectually. This includes parents, staff and the children we serve. 
- name:  Brecca Smith
  role: Co-Lead Teacher
  quote:  My goal is to provide a beautiful environment in which children are blossoming, and are in every way respected and responsible. I believe children educated in this way will grow up to be the competent, compassionate adults our society needs.
- name: Abby Maxwell
  role: Co-Lead Teacher
  quote: My goal is to learn and grown with the students, and to assist in providing an enriching and fulfilling environment.
- name: Tyisha Nedd
  role: Assistant
  quote: 
- name: Faust Barkovskii
  role: Assistant
  quote:
- name: Denn Guerrier
  role: Assistant
  quote:- name: Ronnie Bush
  role: Art Teacher - Assistant
  quote:
- name: Katrina Kujawa
  role: Music Teacher
  quote: 
board:
- name: Ferran Canals 
  role: Parent Representative
  quote: 
- name: Jeremy Lightsmith
  role: Co-founder, Chair
  quote: I want to create a community around this school, it's children, and their parents.
- name: Michelle Harrison
  role: Alumni Representative & Secretary
  quote: 
- name: Ramsey Ness
  role: Treasurer
  quote: I make sure we know where we are and can get to where we want to be financially.
- name: Tehut Getahun
  role: Montessori Expert
  quote: 
alumni:
- name: Karissa Lightsmith
  role: Teacher / Head of School
- name: Jenny Roraback-Carson
  role: Parent Representative
- name: Rhena-Dae Cwiek
  role: Assistant
- name: Jason Lien
  role: Assistant
- name: Nathan Soccorsy
  role: Parent Representative
- name: Tianna Fallgatter
  role: Fundraising Coordinator
- name: Ada Hamilton
  role: Parent Representative
- name: Carrie Daugherty
  role: Assistant
- name: Rompas Ceci Stell
  role: Assistant
- name: Elizabeth Sylvia
  role: Assistant
- name: Emily Smith
  role: Treasurer
- name: Jean Melom
  role: Teacher
- name: Jen Sexton
  role: Parent Representative
- name: Michael Smith
  role: Board Member
- name: Rachel Light
  role: Assistant

---

### Staff

{% include people.html people=page.staff %}

### Board

{% include people.html people=page.board %}

### Alumni

It takes a village, and we are grateful to all the people that have been our village and helped us get here. These are some of our alumni. Thank you, and best of luck!

{% for person in page.alumni %}

<div class="person-grid">
<div class="person-cell">
<img src="/images/people/{{person.name | downcase | replace:' ','-'}}.jpg"/>

<div class="caption">
<h3>
{{person.name}}

</h3>
<p>
{{person.role}}

</p>
</div>
</div>
</div>
{% endfor %}
