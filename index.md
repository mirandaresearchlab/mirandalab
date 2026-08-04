---
---

# Miranda Lab Website

<p style="text-align: center !important;">
We develop machine learning methods to decode cellular behavior by integrating microscopy images and omics data to simulate, predict, and understand complex biological processes. Our work bridges the gap between raw biological data and meaningful clinical impact.
</p>

{% include section.html %}

## Highlights

{% capture text %}

<p style="text-align: center !important;">
From self-supervised learning to flow matching, explore the methods and applications we are developing across our research projects.
</p>

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  style="bare"
  text=text
%}

{% capture text %}

<p style="text-align: center !important;">
Check out our latest papers and preprints.
</p>

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Publications"
  flip=true
  text=text
%}

{% capture text %}

<p style="text-align: center !important;">
The people making it happen.
</p>

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}
