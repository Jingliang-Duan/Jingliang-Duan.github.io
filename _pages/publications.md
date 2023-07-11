---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Education
======
* 09/2011 – 07/2015, B.S. in Automotive Engineering, Jilin University
* 09/2015 – 01/2021, Ph.D. in Automotive Engineering, Tsinghua University, Advisor: Prof. Bo Cheng 
* 10/2018 – 10/2019, Visiting Student, UC Berkeley, Advisor: Prof. Francesco Borrelli,

Academic Appointments
======
* 01/2021 – 07/2021, Research Assistant, School of Vehicle and Mobility, Tsinghua University, Advisor: Prof. Shengbo Eben Li
* 07/2021 - 09/2022, Research Fellow, ECE, National University of Singapore, Advisor: Prof. Lin Zhao
* 09/2022 - Now, Associate Professor, Department of Vehicle Engineering, School of Mechanical Engineering, University of Science and Technology Beijing

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
