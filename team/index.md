---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{%
  include figure.html
  image="images/group_photo_2022F.JPG"
  caption="Xu lab before Corson Hall, 2022 Fall"
  link="team"
  width="600px"
%}


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: visit"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

# <i class="fas fa-users"></i>Alumni

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni" 
%}

{:.center}


