---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a team of researchers, chemists, and engineers working to make energy processes more efficient and sustainable. 
Through technical innovation and collaboration, we develop practical solutions for the energy sector.


{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}<p></p>
{% include list.html data="members" component="portrait" filters="role: phd" %}<p></p>
{% include list.html data="members" component="portrait" filters="role: undergrad" %}


{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}


