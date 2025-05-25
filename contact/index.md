---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---
 
# **{% include icon.html icon="fa-regular fa-envelope" %}Contact**
 
<div style="text-align: center;">
SDU Life Cycle Engineering Center<br>
Department of Green Technology (IGT)<br>
Faculty of Engineering (TEK)<br>
University of Southern Denmark<br>
5230 Odense M<br>
Denmark
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
 
{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}
 
{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}
 
{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}
 
{% include cols.html col1=col1 col2=col2 col3=col3 %}

