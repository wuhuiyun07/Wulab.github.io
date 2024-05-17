---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="huiyun.wu@wsu.edu"
  link="huiyun.wu@wsu.edu"
%}
{%
  include button.html
  type="phone"
  text="509-335-2576"
  link="+1-509-335-2576"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Department+of+Civil+and+Environmental+Engineering/@46.7307914,-117.1717632,17z/data=!3m2!4b1!5s0x549f871928629d53:0x7a5bbace5297cfb8!4m6!3m5!1s0x549f871ed2c91753:0x6ae8c4867ad607ed!8m2!3d46.7307878!4d-117.1691883!16s%2Fg%2F1ptxlzp3l?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/MisRiver.HEIC"
  caption="River"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/WaterPark.HEIC"
  caption="Lorem ipsum"
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
