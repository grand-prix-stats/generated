---
title: List of All Formula 1® Drivers from Finland by Surname
layout: page
collectionName: countries
collectionId: finland
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
| Valtteri | Bottas | [Finland](/f1/countries/finland) | 🇫🇮 |
| Mika | Häkkinen | [Finland](/f1/countries/finland) | 🇫🇮 |
| Jyrki | Järvilehto | [Finland](/f1/countries/finland) | 🇫🇮 |
| Leo | Kinnunen | [Finland](/f1/countries/finland) | 🇫🇮 |
| Heikki | Kovalainen | [Finland](/f1/countries/finland) | 🇫🇮 |
| Mikko | Kozarowitzky | [Finland](/f1/countries/finland) | 🇫🇮 |
| Kimi | Räikkönen | [Finland](/f1/countries/finland) | 🇫🇮 |
| Keke | Rosberg | [Finland](/f1/countries/finland) | 🇫🇮 |
| Mika | Salo | [Finland](/f1/countries/finland) | 🇫🇮 |

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
