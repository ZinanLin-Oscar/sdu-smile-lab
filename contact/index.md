---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---
 
# **{% include icon.html icon="fa-regular fa-envelope" %}  Contact**
{% include section.html %}
## <span style="color: red;">{% include icon.html icon="fas fa-map-marker-alt" %}</span> Address
<div style="text-align: center;">
  <p style="font-size: 1.2rem;"><em>

    Life Cycle Engineering Center<br>
    Department of Green Technology (IGT)<br>
    Faculty of Engineering (TEK)<br>
    University of Southern Denmark<br>
    5230 Odense M<br>
    Denmark
  </em></p>
</div>
 
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
 
{% include section.html dark=true %}
 

