---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<p align="justify">
  
* <b>[Under Review]</b> R. Krishnapuram, <b>S. Shorewala</b> and P. Rao. Link Speed Estimation for Traffic Flow Modelling Based
on Video Feeds from Monocular Cameras. In <i>Proceedings of the IEEE Winter Conference on Applications of Computer
Vision (WACV) 2020</i>.

* <b>[Under Review] S. Shorewala</b>, A. Garg, A. Kumar, H. Kothari, E. S. Viswanath and T. Singla. GPS-based Autonomous
Navigation System for Exploratory Rovers. In <i>International Conference on Innovations in Computational Intelligence and
Computer Vision 2020, Jaipur, India</i>. 


* <b>[Under Review]</b> P. Rao, <b>S. Shorewala</b>, A. Puri, N. Sharma, P. Singh, S. Srinivasan, A. Sharma and R. Krishnapuram. A Traffic Analytics Architecture and Dataset for Indian Roads Using a Monocular Surveillance Camera Network. In <i>ACM India Joint International Conference on Data Sciences and Management of Data (7th ACM iKDD CoDS and 25th COMAD), Kolkata, India</i>. 

</p>
