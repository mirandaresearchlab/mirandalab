---
---

# Miranda Lab Website

<div style="text-align: center>
We develop machine learning methods to decode cellular behavior by integrating microscopy images and omics data to simulate, predict, and understand complex biological processes. Our work bridges the gap between raw biological data and meaningful clinical impact.
</div>

{% include section.html %}

## Highlights

{% capture text %}

<div style="text-align: center>
From self-supervised learning to flow matching, explore the methods and applications we are developing across our research projects.
</div>

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

<div style="text-align: center>
Check out our latest papers and preprints.
</div>

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

<div style="text-align: center>
The people making it happen.
</div>

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
