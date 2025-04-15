---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SDU Life Cycle Engineering Unit<br>
Department of Green Technology(IGT)<br>
Faculty of Engineering(TEK)<br>
University of Southern Denmark<br>
5230 Odense M<br>
Denmark

{%
  include button.html
  type="email"
  text="email"
  link="mailto:wuc@igt.sdu.dk"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://www.google.com/maps/place/The+Faculty+of+Engineering/@55.3673846,10.4309481,18.5z/data=!4m6!3m5!1s0x464d204fe2633dd5:0x99cfe0547124d6e9!8m2!3d55.3672411!4d10.4320785!16s%2Fg%2F122tnw5l?entry=ttu&g_ep=EgoyMDI1MDQxMy4wIKXMDSoJLDEwMjExNDU1SAFQAw%3D%3D)"
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

{% capture col2 %}

{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %} Lorem ipsum dolor sit amet
consectetur adipiscing elit
sed do eiusmod tempor {% endcapture %}

{% capture col2 %} Lorem ipsum dolor sit amet
consectetur adipiscing elit
sed do eiusmod tempor {% endcapture %}

{% capture col3 %} Lorem ipsum dolor sit amet
consectetur adipiscing elit
sed do eiusmod tempor {% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
