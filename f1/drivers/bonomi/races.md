---
title: List of Formula 1® Races by Roberto Bonomi
layout: page
collectionName: drivers
collectionId: bonomi
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

| Season | Round | Name | Date | Grid | Final Position | Points | Laps Completed | Time | Constructor | Teammate | Teammate Grid | Teammate Final Position |
|--|--|--|--|--|--|--|--|--|--|--|--|--|
| 1960 | 1 | 1960 Argentine Grand Prix 🇦🇷 | 1960-02-07 | 17 | 11 | 0.0 | 76 |   | Cooper-Maserati 🇬🇧 | [Carlos Menditeguy 🇦🇷](/f1/drivers/menditeguy) | 12 | 4 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 1 |  |  | 1 | 1 | 1 | 1 |  |  |  | 1 | 1 |
| **Total Sum** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **Mean μ (Average)** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **Maximum** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **75th Percentile** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **Median** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **25th Percentile** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **Minimum** | 1.000 |  |  | 17.000 | 11.000 |  | 76.000 |  |  |  | 12.000 | 4.000 |
| **Variance** |  |  |  |  |  |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
