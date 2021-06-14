---
title: Publications
redirect_from: /publications
---

# <i class="fas fa-microscope"></i>Publications



<!-- section break -->

{% include card-search.html subject="papers" %}

<!-- the research-list.html file defiles the structure of the paper presented--> 
<!-- Change this html file for the style-->
{% include research-list.html %}

<!-- section break -->

## More

{% capture html %}
{%
  include big-link.html
  icon="fas fa-book-open"
  text="More on PubMed"
  link="https://pubmed.ncbi.nlm.nih.gov/?term=Koslicki+D&cauthor_id=30832730"
%}
{%
  include big-link.html
  icon="fab fa-google"
  text="More on Google Scholar"
  link="https://scholar.google.com/citations?user=Oz90sQsAAAAJ&hl=en"
%}
{% endcapture %}

{% include centerer.html html=html %}

The citations on this page were generated automatically from just identifiers using the [Manubot cite utility](https://github.com/manubot/manubot#cite) developed in the Greene Lab!

