---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'Assistant Professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'Postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'PhD Student'" %}

