---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

Our diverse team is composed of a highly enthusiastic and collaborative researchers. We foster a friendly and collaborative environment, where team members can learn from each other.


{% capture html %}
{% include team-list.html role="pi" group="" %}
{% include team-list.html role="postdoc" group="" %}
{% include team-list.html role="phd" group="" %}
{% include team-list.html role="masters" group="" %}
{% include team-list.html role="pharmd" group="" %}
{% include team-list.html role="undergrad" group="" %}
{% include team-list.html role="highschool" group="" %}
{% include team-list.html role="programmer" group="" %}
{% include team-list.html role="mascot" group="" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

The Koslicki Lab is committed to ensuring an inclusive and supportive environment regardless of age, gender, sexual orientation, disability, race, ethnicity, religion, nationality, or socioeconomic background.

{%
  include big-link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
%}{:.center}


## Alumni

These alumni from the lab have graduated and moved on to other positions.

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="postdoc" group="alum" mini="true" %}
{% include team-list.html role="phd" group="alum" mini="true" %}
{% include team-list.html role="masters" group="alum" mini="true" %}
{% include team-list.html role="pharmd" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% include team-list.html role="highschool" group="alum" mini="true" %}
{% include team-list.html role="programmer" group="alum" mini="true" %}
{% include team-list.html role="mascot" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- ## Funding

{:.center}
Our work is made possible by funding from several organizations. -->

<!-- {%
  include gallery.html
  flat="true"
  fit="false"

  image1="images/team/gordon-and-betty-moore-foundation.png"
  link1="https://www.moore.org/"
  tooltip1="Gordon and Betty Moore Foundation"

  image2="images/team/national-cancer-institute.png"
  link2="https://www.cancer.gov/"
  tooltip2="National Cancer Institute"

  image3="images/team/alex's-lemonade-stand-foundation-for-childhood-cancer.png"
  link3="https://www.alexslemonade.org/"
  tooltip3="Alex's Lemonade Stand Foundation for Childhood Cancer"

  image4="images/team/chan-zuckerberg-initiative.png"
  link4="https://chanzuckerberg.com/"
  tooltip4="Chan Zuckerberg Initiative"

  image5="images/team/cystic-fibrosis-foundation.png"
  link5="https://www.cff.org/"
  tooltip5="Cystic Fibrosis Foundation"

  image6="images/team/alfred-p-sloan-foundation.png"
  link6="https://sloan.org/"
  tooltip6="Alfred P. Sloan Foundation"

  image7="images/team/national-human-genome-research-institute.png"
  link7="https://www.genome.gov/"
  tooltip7="National Human Genome Research Institute"

  image8="images/team/national-heart-lung-and-blood-institute.png"
  link8="https://www.nhlbi.nih.gov/"
  tooltip8="National Heart, Lung, and Blood Institute"

  image9="images/team/national-institute-of-neurological-disorders-and-stroke.png"
  link9="https://www.ninds.nih.gov/"
  tooltip9="National Institute of Neurological Disorders and Stroke"
%} -->

<!-- {%
  include figure.html
  image="images/team/group.jpg"
  caption="Mangul Lab Research Group"
  width="100%" 
%} -->
