---
title: Neural & ML Group
permalink: /people/alumni
---

{% assign people_sorted = site.people | sort: "joined" %}
{% assign people_array = "alumni_ra|alumni_phd" | split: "|" %}


<!--
{% assign people_array = "alumni_ra|alumni_phd" | split: "|" %}

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
<h3>Core faculty</h3>
 {% elsif item == 'gradstudent' %}
<h3>Doctoral students</h3>
{% elsif item == 'visiting' %}
<h3>Visiting scholars</h3>
 {% elsif item == 'others' %} 
<h3>Affiliated faculty</h3>
{% elsif item == 'alumni_ra' %}
<h3>Alumni postdoctoral research associate</h3>
{% elsif item == 'alumni_phd' %}
<h3>Alumni doctoral student</h3>
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
<hr>
{% endfor %}

<div class="pos_header">
<h3>Rotation/MEng/BSc/MSc students</h3>
</div>

<p><b>2023/2024</b>:</p>
- `Angeliki Papathanasiou` [DPhil rotation, Health DS CDT]
- `Milan Sobota` [DPhil rotation, BioDTP]
- `Ben Ibbott` [DPhil rotation, BioDTP]
- `Marius Urbonas` [DPhil rotation, SABS CDT]
- `Iris Marmouset-De La Taille Tretin` [DPhil rotation, SABS CDT]
- `Junde Wu` [DPhil rotation, SABS CDT]
- `Quentin Guilhot` [Master project, ETH]
- `Alexia Duriez` [Master project, EPFL]

<p><b>2022/2023</b>:</p>
- `Ayodya Samarawickrama` [undergrad]
- `Robert Popescy` [undergrad]
- `Evgenia Karnavou` [undergrad]
- `Viktor Kusheliev` [undergrad]
- `Baiquan Zhang` [undergrad]
- `Jushua Hall` [undergrad]
- `Katia Vasilonikolidaki` [undergrad]
- `Aadith Pillai` [undergrad]
- `Jadadish Kumar` [Data Science MSc]
- `Olly Hill` [Data Science MSc]
<p><b>2020/2021</b>:</p>
- `Ainesh Sevellaraja` [CS MEng]
- `Nicole Li` [CS MEng]
- `Lizzie Hull` [CS MSc Conv]
- `Jason Park` [CS BSc]
- `Matt Friend` [CS BSc]
- `Martin Noruisis` [CS BSc]
<p><b>2019/2020</b>:</p>
- `Priyanka Sukumaran` [WT Neural Dynamics PhD rotation; w/ Paul Anastasiades]
- `Dabal Pedamonti` [Farscope PhD rotation; w/ Nathan Lepora; now a PhD student]
- `Can Liu` [CS MEng]
- `Daniel Davies` [CS MEng; w/ Jane Memmott]
- `Graciela Putri` [CS MSc Conv]
- `Abdullah Khwaja` [CS BSc]
- `Martin Dimitrov` [CS BSc]
- `Andrei Bogdan` [CS BSc]
- `Alfred Brown` [EngMath MEng; w/ Nathan Lepora]
<p><b>2018/2019</b>:</p>
- `Ellen Boven` [WT Neural Dynamics Program, w/ Richard Apps; now a PhD student]
- `Heng Wei Zhu` [WT Neural Dynamics Program, w/ Jack Mellor; now a PhD student]
- `Samia Mohinta` [Advanced CS MSc w/ Stephane Ciocchi; now PhD at Cambridge]
- `Ruben Powar` [Advanced CS MSc]
- `Raymond Chua` [Visiting MSc; Technical University of Munich; now a visiting PhD student]
- `Ellis Pridgeon` [CS MEng]
- `Jun Zhou` [CS MSc]
- `Callum Macmillan` [CS BSc]
<hr>

{% include footer.html %}


