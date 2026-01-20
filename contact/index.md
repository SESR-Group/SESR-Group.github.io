---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For more details, please contact [Dr.Georgios Nikiforidis](https://www.ucl.ac.uk/institute-for-materials-discovery/people/dr-georgios-nikiforidis).
UCL East address: Marshgate Building, 7 Sidings St, London E20 2AE (7th floor, MDL Lab, Room 711b)

{%
  include button.html
  type="Email"
  text="Georgios Nikiforidis"
  link="emailto:georgios.nikiforidis@ucl.ac.uk"
%}
{%
  include button.html
  type="Phone"
  text="+44 20 3108 4499"
  link="+44 20 3108 4499"
%}
{%
  include button.html
  type="address"
  text="Our Address at UCL East"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/UCL+East+-+One+Pool+Street/@51.5428653,-0.0208815,16z/data=!4m10!1m2!2m1!1sUCL+EAST!3m6!1s0x48761d66f90b73d1:0xcc0139dfc8c5e7c7!8m2!3d51.5382654!4d-0.0097532!15sCghVQ0wgRUFTVCIDiAEBkgEKdW5pdmVyc2l0eeABAA!16s%2Fg%2F11cnb5znhy?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/applied mathmatics.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/chemical engineering.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}
