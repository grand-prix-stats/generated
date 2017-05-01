---
title: List of All Formula 1® Drivers that Have Raced in Russia by Number of Times
layout: page
collectionName: countries
collectionId: russia
---

{% assign url_split = page.url | split: "/" %}
<div id="collection-navigation">
<button onclick="selector.options[selector.selectedIndex-1].value && (window.location = selector.options[selector.selectedIndex-1].value);">&lt; Prev</button>
<button onclick="selector.options[selector.selectedIndex+1].value && (window.location = selector.options[selector.selectedIndex+1].value);">Next &gt;</button>
<select id="selector" onchange="this.options[this.selectedIndex].value && (window.location = this.options[this.selectedIndex].value);">
  {% for collectionId in site.data[page.collectionName].refs %}
    {% if collectionId == page.collectionId %}
      {% assign selected = "selected" %}
    {% else %}
      {% assign selected = "" %}
    {% endif %}
    {% assign profile = site.data[page.collectionName][collectionId].profile %}
    <option value="/f1/{{ page.collectionName }}/{{ collectionId }}/{{ url_split[4] }}" {{ selected }}>{{ profile.collection_name }}</option>
  {% endfor %}
</select>
</div>

| Driver | Times |
|--|--|
| [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 4 |
| [Daniil Kvyat 🇷🇺](/f1/drivers/kvyat) | 4 |
| [Felipe Massa 🇧🇷](/f1/drivers/massa) | 4 |
| [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 4 |
| [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 4 |
| [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 |
| [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 4 |
| [Nico Hülkenberg 🇩🇪](/f1/drivers/hulkenberg) | 4 |
| [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 4 |
| [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 4 |
| [Sergio Pérez 🇲🇽](/f1/drivers/perez) | 4 |
| [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 4 |
| [Carlos Sainz 🇪🇸](/f1/drivers/sainz) | 3 |
| [Jenson Button 🇬🇧](/f1/drivers/button) | 3 |
| [Kevin Magnussen 🇩🇰](/f1/drivers/kevin_magnussen) | 3 |
| [Max Verstappen 🇳🇱](/f1/drivers/max_verstappen) | 3 |
| [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 3 |
| [Esteban Gutiérrez 🇲🇽](/f1/drivers/gutierrez) | 2 |
| [Felipe Nasr 🇧🇷](/f1/drivers/nasr) | 2 |
| [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 2 |
| [Pascal Wehrlein 🇩🇪](/f1/drivers/wehrlein) | 2 |
| [Pastor Maldonado 🇻🇪](/f1/drivers/maldonado) | 2 |
| [Adrian Sutil 🇩🇪](/f1/drivers/sutil) | 1 |
| [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 1 |
| [Jean-Éric Vergne 🇫🇷](/f1/drivers/vergne) | 1 |
| [Kamui Kobayashi 🇯🇵](/f1/drivers/kobayashi) | 1 |
| [Lance Stroll 🇨🇦](/f1/drivers/stroll) | 1 |
| [Max Chilton 🇬🇧](/f1/drivers/chilton) | 1 |
| [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 1 |
| [Roberto Merhi 🇪🇸](/f1/drivers/merhi) | 1 |
| [Stoffel Vandoorne 🇧🇪](/f1/drivers/vandoorne) | 1 |
| [Will Stevens 🇬🇧](/f1/drivers/stevens) | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 32 |
| **Total Sum** | 83.000 |
| **Mean μ (Average)** | 2.594 |
| **Maximum** | 4.000 |
| **75th Percentile** | 4.000 |
| **Median** | 3.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.616 |
| **Standard Deviation σ** | 1.271 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
