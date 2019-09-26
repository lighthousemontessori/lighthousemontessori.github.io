---
title: Our Team
css: our-team
staff:
- name: Cynthia Dahl
  role: Head of School
  quote: My goal is to foster a community that feels safe to grow both emotionally and intellectually. This includes parents, staff and the children we serve. 
- name:  Michael Myers
  role: Co-Lead Teacher
  quote:  My goal is to help children hone their mental and physical and spiritual tools, simultaneously facilitating their joy in learning. To support the child's ability to be an independent, curious, and lifelong learner.
- name: Kristina Hunt
  role: Co-Lead Teacher
  quote: My main goal is to help lead a child towards peaceful communication and self-confidence.
- name: Lila Faria
  role: Assistant
  quote: "If you judge a fish by its ability to climb a tree, it will live its whole life believing it is stupid\" - Albert Einstein
- name: Faust Barkovskii
  role: Assistant
  quote:
- name: Connor Bailey
  role: Assistant
  quote: 
- name: Denn Guerrier
  role: French/Science/Reading/Math Teacher, Substitute Assistant
- name: Katrina Kujawa
  role: Music Teacher
  quote: 
board:
- name: LeAnne Chow 
  role: Parent Representative
  quote: 
- name: Jeremy Lightsmith
  role: Co-founder, Chair
  quote: I want to create a community around this school, it's children, and their parents.
- name: January Fredricks
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
  role: Teacher / Former Head of School / Co-founder
- name: Abby Maxwell
  role: Teacher
- name: Rocio Holland
  role: Teacher
- name: Brecca Smith
  role: Teacher
- name: Jenny Roraback-Carson
  role: Parent Representative
- name: Michelle Harrison
  role: Alumni Representative & Secretary
- name: Tyisha Nedd
  role: Assistant
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
- name: Ronnie Bush
  role: Art Teacher / Substitue Assistant
- name: Ferran Canals
  role: Parent Representative
- name: Garrett Carlson
  role: Teacher
- name: Kevin Van Meter
  role: Teacher
- name: Nicolette Riggins
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
