---
title: ""
permalink: /publications/
author_profile: true
---
**J: Journal; C: Conference**

_Any publications currently under review without a preprint provided will be available in peer-reviewed manuscripts or preprints after the reviewing process, as per the submission requirements by the venues._

## 2024 ##
<ul>
  <li>(Under Review) [J1] <b>Qiangeng Yang</b>, Yoo Jin Chung, Juliana Fernandes, Daniela Oliveira<br>
    <b>Does Social Media Labeling Help with Content Moderation? An Analysis of Sentiment Labels</b><br>
    <i>Communication Research and Practice</i>, 2024
  </li>
</ul>


## 2023 ##
<ul>
  <li>(Under Review) [C1] Tess Christensen, Mirela Silva, Shlok Gilda, <b>Qiangeng Yang</b>, Daniel Capecci, Daniela Oliveira<br>
    <b>The Use of Social, Behavioral, and Economic Theories in Human Factors Phishing Research</b><br>
    <i>ACM Computing Surveys</i>, 2023
  </li>
</ul>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
