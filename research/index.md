---
title: Research
nav:
  order: 1
  tooltip: Learn about our research
---

# {% include icon.html icon="fa-solid fa-flask-vial" %}Research
<!--
During development cells specialise in response to signaling cues. To accomplish this, they must turn on and (importantly!) off gene expression programs. Cis-regulatory elements are stretches of DNA within the non-coding genome that can control gene expression with exquisite spatial and temporal precision. We know that cis-regulatory elements are bound by transcription factors, but it is still not trivial to find them and we are not able to predict their activity from sequence.

The primary goal of our research is to understand how the **non-coding genome** regulates cell fate decisions during development. Our strategy to achieve this is to study the **mechanistic principles** of cis-regulatory elements in a developmentally relevant model, the developing spinal cord. Long-term, our aim is to predict the functional outcomes of non-coding variation in development and disease.
-->

{% capture text %}

<!--
# Section header

brief description

To  bridge molecular mechanisms of cis regulation to developmental phenotypic consequences, we combine _in vivo_ embryology with _in vitro_ cellular models that recapitulate the same cell fate decisions. Our favourite model system is the developing spinal cord, where a small combination of signals directs the specification of neural progenitors and therefore which neurons they will make.
-->
{% endcapture %}

{%
  include feature.html
  image=""
  text=text
%}

{% capture text %}
<!--
# Section header

brief description

We use a variety of novel genomics and computational methods, developing new approaches when needed to answer the questions. Our current projects include state-of-the art proteomics and microscopy approaches to address the mechanistic principles of how cis-regulatory elements control cell fate choice between neural progenitors.
-->
{%
  include button.html
  link="publications"
  text="Read more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image=""
  link="publications"
  flip=true
  style="bare"
  text=text
%}


<!--
{% include tags.html tags="publication, resource, website" %}


{% include section.html %}

## Resources

{% include list.html component="card" data="projects" filters="group: featured" style="small" %}

{% include section.html %}
-->

<!---
## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
-->
