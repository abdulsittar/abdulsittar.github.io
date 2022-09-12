---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the complete list of articles on my <a href="https://scholar.google.com/citations?user=7cm4SVgAAAAJ&hl=en"><b>Google Scholar</b></a> profile.

Cheema, Gullal S; Hakimov, Sherzod; Sittar, Abdul; Müller-Budack, Eric; Otto, Christian; Ewerth, Ralph; MM-Claims: A Dataset for Multimodal Claim Detection in Social Media Findings of the North American Chapter of the Association for Computational Linguistics (Findings of NAACL 2022) [PDF](https://arxiv.org/pdf/2205.01989.pdf) [Git repo](https://github.com/TIBHannover/MM_Claims)





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
