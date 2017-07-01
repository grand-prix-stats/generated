---
title: List of Formula 1® Races by Jimmy Stewart
layout: page
collectionName: drivers
collectionId: jimmy_stewart
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
| 1953 | 6 | 1953 British Grand Prix 🇬🇧 | 1953-07-18T00:00:00.000Z | 15 | R | 0.0 | 79 |   | Cooper 🇬🇧 | [Ken Wharton 🇬🇧](/f1/drivers/wharton) | 11 | 8 |
| 1953 | 6 | 1953 British Grand Prix 🇬🇧 | 1953-07-18T00:00:00.000Z | 15 | R | 0.0 | 79 |   | Cooper 🇬🇧 | [Peter Whitehead 🇬🇧](/f1/drivers/whitehead) | 14 | 9 |
| 1953 | 6 | 1953 British Grand Prix 🇬🇧 | 1953-07-18T00:00:00.000Z | 15 | R | 0.0 | 79 |   | Cooper 🇬🇧 | [Alan Brown 🇬🇧](/f1/drivers/alan_brown) | 21 | R |
| 1953 | 6 | 1953 British Grand Prix 🇬🇧 | 1953-07-18T00:00:00.000Z | 15 | R | 0.0 | 79 |   | Cooper 🇬🇧 | [Tony Crook 🇬🇧](/f1/drivers/crook) | 25 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 4 |  | 4 | 4 |  | 4 | 4 |  |  |  | 4 | 2 |
| **Total Sum** | 24.000 |  | -2077401600.000 | 60.000 |  |  | 316.000 |  |  |  | 71.000 | 17.000 |
| **Mean μ (Average)** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 17.750 | 8.500 |
| **Maximum** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 25.000 | 9.000 |
| **75th Percentile** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 25.000 | 9.000 |
| **Median** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 21.000 | 9.000 |
| **25th Percentile** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 14.000 | 8.000 |
| **Minimum** | 6.000 |  | -519350400.000 | 15.000 |  |  | 79.000 |  |  |  | 11.000 | 8.000 |
| **Variance** |  |  |  |  |  |  |  |  |  |  | 30.688 | 0.250 |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |  | 5.540 | 0.500 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
