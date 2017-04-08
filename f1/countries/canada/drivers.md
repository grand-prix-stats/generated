---
title: List of All Formula 1® Drivers from Canada by Surname
layout: page
collectionName: countries
collectionId: canada
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

| Forename | Surname | Country | Flag |
|--|--|--|--|
| Allen | Berg | [Canada](/f1/countries/canada) | 🇨🇦 |
| Bill | Brack | [Canada](/f1/countries/canada) | 🇨🇦 |
| Peter | Broeker | [Canada](/f1/countries/canada) | 🇨🇦 |
| John | Cannon | [Canada](/f1/countries/canada) | 🇨🇦 |
| John | Cordts | [Canada](/f1/countries/canada) | 🇨🇦 |
| George | Eaton | [Canada](/f1/countries/canada) | 🇨🇦 |
| Al | Pease | [Canada](/f1/countries/canada) | 🇨🇦 |
| Peter | Ryan | [Canada](/f1/countries/canada) | 🇨🇦 |
| Lance | Stroll | [Canada](/f1/countries/canada) | 🇨🇦 |
| Gilles | Villeneuve | [Canada](/f1/countries/canada) | 🇨🇦 |
| Jacques | Villeneuve | [Canada](/f1/countries/canada) | 🇨🇦 |
| Jacques | Villeneuve Sr. | [Canada](/f1/countries/canada) | 🇨🇦 |
| Eppie | Wietzes | [Canada](/f1/countries/canada) | 🇨🇦 |

#### Statistic Summary

| **Column** | **Surname** | **Country** | **Flag** |
| **Row Count** |  |  |  |
| **Total Sum** |  |  |  |
| **Mean μ (Average)** |  |  |  |
| **Maximum** |  |  |  |
| **75th Percentile** |  |  |  |
| **Median** |  |  |  |
| **25th Percentile** |  |  |  |
| **Minimum** |  |  |  |
| **Variance** |  |  |  |
| **Standard Deviation σ** |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
