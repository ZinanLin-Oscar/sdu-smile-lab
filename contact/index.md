
---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

{% include section.html %}
# <strong>{% include icon.html icon="fa-regular fa-envelope" %}Contact</strong>

{% include section.html %}
## {% include icon.html icon="fas fa-map-marker-alt" %} Address

<div style="text-align: center;">
  <p>
    <strong>SDU Life Cycle Engineering Center</strong><br>
    Department of Green Technology (IGT)<br>
    Faculty of Engineering (TEK)<br>
    University of Southern Denmark<br>
    5230 Odense M<br>
    Denmark
  </p>
</div>

<hr>

{% include section.html %}
{%
  include button.html
  type="Email"
  text="Email"
  link="mailto:wuc@igt.sdu.dk"
%}
{%
  include button.html
  type="Our Location on Google Maps for Easy Navigation"
  text="Address"
  link="https://maps.app.goo.gl/TTVjd6rDn14pykTU6"
%}

{% include section.html %}
{% capture col1 %}
{%
  include figure.html
  image="images/sdu_campus.png"
  caption="SDU Campus"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/TEK.jpg"
  caption="TEK Building"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

