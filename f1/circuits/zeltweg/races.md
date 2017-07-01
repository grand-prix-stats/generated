---
title: List of All Formula 1® Races at Zeltweg
layout: page
collectionName: circuits
collectionId: zeltweg
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

| Season | Round | Name | Date | Laps Completed | Race Duration | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|
| 1964 | 7 | 1964 Austrian Grand Prix 🇦🇹 | 1964-08-23T00:00:00.000Z | 105 | 2:06:18.23 | [Lorenzo Bandini 🇮🇹](/f1/drivers/bandini) | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  | 1 | 1 |  |  |  |
| **Total Sum** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **Mean μ (Average)** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **Maximum** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **75th Percentile** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **Median** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **25th Percentile** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **Minimum** | 7.000 |  | -169084800.000 | 105.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})