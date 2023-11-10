---
title: Neural & ML Group
permalink: /team/
---

{% assign people_sorted = site.people | sort: "joined" %}
{% assign people_array = "pi|collab|postdoc|researchassistant|gradstudent|others" | split: "|" %}


<!--
  {% assign people_array = "pi|postdoc|gradstudent|others" | split: "|" %}
  
{% assign people_sorted = site.people | sort: "joined" %}
<ul>
{% for y in yearsSorted %}
  <li>{{ y.name }}
    <ul>
      {% assign yearTitlesSorted = y.items | sort: "title" %}
      {% for t in yearTitlesSorted %}
      <li>{{ t.title }}</li>
      {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>-->

{% for item in people_array %}

<div class="pos_header">
{% if item == 'postdoc' %}
<h3>Postdoctoral research associates</h3>
 {% elsif item == 'pi' %}
<h3>Principal investigator</h3>
{% elsif item == 'researchassistant' %}
<h3>Research Assistants</h3>
 {% elsif item == 'gradstudent' %}
<h3><br>Doctoral students</h3>
{% elsif item == 'alumni' %}
<h3>Alumni</h3>
{% endif %}
</div>

<div class="content list people">
  {% for profile in people_sorted %}
    {% if profile.position contains item %}
    <div class="list-item-people">
      <p class="list-post-title">
        {% if profile.website %}
          {% assign url_tmp = profile.website %}
        {% else %}
          {% assign url_tmp = site.baseurl | append: profile.url %}
        {% endif %}
        {% if profile.avatar %}
        <a href="{{url_tmp}}"><img width="200" height="230" src="{{site.baseurl}}/images/people/{{profile.avatar}}"></a>
        {% else %}
        <a href=""><img width="200" height="230" src="http://evansheline.com/wp-content/uploads/2011/02/facebook-Storm-Trooper.jpg"></a>
        {% endif %}
        <a class="name" href="{{url_tmp}}">{{ profile.name }}</a>
        {% if profile.affiliation %}
          <br><small><span style="color:#9d9d9d">{{ profile.affiliation }}</span></small>
        {% else %}
          <br><small><span style="color:#FFFFFF">.</span></small>
        {% endif %}
      </p>
    </div>
    {% endif %}
  {% endfor %}
</div>
{% endfor %}
<hr>
<div class="pos_header">
<h3>Rotation/MEng/BSc/MSc students</h3>
</div>
- `Alexia Duriez` [Master project, EPFL]
- `Milan Sobota` [PhD rotation, BioDTP]
- `Ben Ibbott` [PhD rotation, BioDTP]

<hr>
<div class="pos_header">
<h3>Collaborators:</h3>
</div>

(non-exhaustive)

- `Randy Bruno`, `Chris Summerfield`, `Armin Lak`, `Helen Barron`, `Clare Mackay`, `Tim Behrens` and several others [Neuro @ University of Oxford, UK]
- `Yarin Gal` [ML @ University of Oxford, UK]
- `Jack Mellor`, `Paul Anastasiades`, `Liz Coulthard`, `Paul Chadderton`, `Paul Dodson`, `Matt Jones`, `Jeff Bowers`, `Richard Apps` [Neuro @ University of Bristol, UK]
- `Rob Froemke` [New York University, US]
- `Adam Kepecs` [Washington University, US]
- `Kim Stachenfeld`, `‪Caglar Gulcehre‬`, `Max Jaderberg` [Google Deepmind, UK]
- `Adil Khan` [Kings College London]
- `Jasper Poort` [Cambridge University]
- `Joao Sacramento` [ETH, Switzerland]
- `Yoshua Bengio` [MILA; University of Montreal, Canada]



<hr>
<a href="https://neuralml.github.io/joinus/" target="_blank"><b>Join us!</b></a> <br>

List of [NML alumni](/people/alumni).

<hr>

{% include footer.html %}


