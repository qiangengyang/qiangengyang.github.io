---
title: ""
permalink: /publications/
author_profile: true
---
**J: Journal; C: Conference**

_Any publications currently under review without a preprint provided will be available in peer-reviewed manuscripts or preprints after the reviewing process, as per the submission requirements by the venues._

## 2024 ##
<ul>
  <li> [C1] <b>Qiangeng Yang</b>, Tess Christensen, Shlok Gilda, Juliana Fernandes, Daniela Oliveira, Ronald Wilson, Damon Woodard<br>
    <b>Are Fact-Checking Tools Helpful? An Exploration of the Usability of Google Fact Check</b><br>
    <i>5th EAI International Conference on Data and Information in Online Environments (EAI DIONE
2024)</i>
  </li>
</ul>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
