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

**Y. Jain**, K. Cunningham. "[How Computing Educators Identify Programming Plans: State of the Art, Challenges, and Opportunities]." In
CHI Conference on Human Factors in Computing Systems **(CHI 2024)**. **(Under Submission)**

**Y. Jain**, K. Cunningham. "[Towards Methods for Identifying High-Quality Domain-Specific Programming Plans](https://dl.acm.org/doi/10.1145/3568812.3603478)." In Proceedings of the 2023 ACM Conference on International Computing Education Research V.2 **(ICER ’23 V2)**.

---