---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We would be happy to connect with anyone who is interested in our research

{%
  include button.html
  type="email"
  text="Vignir.Helgason@glasgow.ac.uk"
  link="Vignir.Helgason@glasgow.ac.uk"
%}
{%
  include button.html
  type="phone"
  text="0141 330 7245"
  link="+44-141-330-7245"
%}
{%
  include button.html
  type="Wolfson Wohl Cancer Research Centre"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/XBHQctoT9ejEgRvF6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="University of Glasgow"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Cancer Research UK"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Research
{% endcapture %}

{% capture col2 %}
Engage
{% endcapture %}

{% capture col3 %}
Translate
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
