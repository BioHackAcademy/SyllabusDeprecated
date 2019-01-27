---
layout: default
title: Organisms
permalink: /bha5/organisms/
---

## Organisms

The following cultures are available in the Waag Society's Open Wetlab. In case you are following the Academy in one of the partner labs, check the availability with your coordinator:

{% for page in site.pages %}
{% if page.categories contains 'culture-collection' %}
{% if page.url contains 'bha5' %}
* [{{ page.title }}]({{ page.url | prepend: site.baseurl }})
{% endif %}
{% endif %}
{% endfor %}

## Cultivation media
Here are all the [recipes for cultivation media](/bha4/cultivation-media/) to grow the microbes on listed above.

## Isolate yourself

* Lactic acid bacteria from unpasteurized dairy product like Yakult
* Acetobacter (acitic acid bacteria) from unpasteurized vinegar
* Yeast from unpasteurized beer like Grimbergen or Duvel
* Nitrogen fixating bacteria from soil
* Sulfuroxidizing bacteria from soil

## To be bought in a store

* Yeast can be found in the baking section of any supermarket
* Lactobacilli are sold as pills at any drug store


