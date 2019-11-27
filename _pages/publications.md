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
Vision (WACV) 2020, Colorado, USA</i>.
</p>


<p align="justify">
  * <b>[Under Review]</b> <b> S. Shorewala </b>, A. Kumar, A. Garg, H. Kothari, T. Singla, E. Suriya, N.K. Vernekar and Y.S. Upadhyaya. GPS-based autonomous navigation in extreme outdoor environments. In <i> Intelligent Service Robotics (2019). </i>
</p>

<p align="justify">
* <b>[Poster Presentation only] </b> D.K. Rajamani, E.D. Pitchika, K.S. Dhankar, <b> S. Shorewala</b>, D. Bansal and Y.S. Upadhyaya.Design Overview of a Planetary Exploration Rover for Unstructured Terrain. In <i> 3rd International and 18th National Conference on Machines & Mechanisms 2017, India </i>.
</p>

