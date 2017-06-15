---
title: Our Team
css: our-team
staff:
- name: Karissa Lightsmith
  role: teacher / head of school
  quote: In a very concrete, real way, I know that children can change the culture, language, and beliefs of human society.  I personally want to push that in a positive direction.
- name:  Brecca Smith
  role: teacher
  quote:  My goal is to provide a beautiful environment in which children are blossoming, and are in every way respected and responsible. I believe children educated in this way will grow up to be the competent, compassionate adults our society needs.
- name: Abby Maxwell
  role: assistant
  quote: My goal is to learn and grown with the students, and to assist in providing an enriching and fulfilling environment.
- name: Rhena-Dae Cwiek
  role: assistant
  quote: 
- name: Tyisha Nedd
  role: assistant
  quote: 
- name: Ginger Spaulding
  role: assistant
  quote: 
- name: Madeleine Poole
  role: Spanish teacher
  quote: 
- name: Katrina Kujawa
  role: Music Teacher
  quote: 
board:
- name: Jeremy Lightsmith
  role: co-founder, chair
  quote: I want to create a community around this school, it's children, and their parents.
- name: Michelle Harrison
  role: alumni representative & secretary
  quote: 
- name: Jenny Roraback-Carson 
  role: parent representative
  quote: 
- name: Ramsey Ness
  role: treasurer
  quote: I make sure we know where we are and can get to where we want to be financially.
alumni:
- name: Jason Lien
  role: assistant
- name: Nathan Soccorsy
  role: parent representative
- name: Tianna Fallgatter
  role: fundraising coordinator
- name: Ada Hamilton
  role: parent representative
- name: Carrie Daugherty
  role: assistant
- name: Rompas Ceci Stell
  role: assistant
- name: Elizabeth Sylvia
  role: assistant
- name: Emily Smith
  role: treasurer
- name: Jean Melom
  role: teacher
- name: Jen Sexton
  role: parent representative
- name: Michael Smith
  role: board member
- name: Rachel Light
  role: assistant

---

### Staff

{% include people.html people=page.staff %}

### Board

{% include people.html people=page.board %}

### Alumni

It takes a village, and we are greatful to all the people that have been our village and helped us get here. These are some of our alumni. Thank you, and best of luck!

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
