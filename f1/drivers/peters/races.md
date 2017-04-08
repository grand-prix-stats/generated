---
title: List of Formula 1® Races by Josef Peters
layout: page
collectionName: drivers
collectionId: peters
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
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Fritz Riess 🇩🇪](/f1/drivers/riess) | 12 | 7 |
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Toni Ulmen 🇩🇪](/f1/drivers/ulmen) | 15 | 8 |
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Hans Klenk 🇩🇪](/f1/drivers/klenk) | 8 | 11 |
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Adolf Brudes 🇩🇪](/f1/drivers/brudes) | 19 | R |
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Paul Pietsch 🇩🇪](/f1/drivers/pietsch) | 7 | R |
| 1952 | 6 | 1952 German Grand Prix 🇩🇪 | 1952-08-03 | 20 | R | 0.0 | 1 |   | Veritas 🇩🇪 | [Theo Helfrich 🇩🇪](/f1/drivers/helfrich) | 18 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 6 |  |  | 6 |  | 6 | 6 |  |  |  | 6 | 3 |
| **Total Sum** | 36.000 |  |  | 120.000 |  |  | 6.000 |  |  |  | 79.000 | 26.000 |
| **Mean μ (Average)** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 13.167 | 8.667 |
| **Maximum** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 19.000 | 11.000 |
| **75th Percentile** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 18.000 | 11.000 |
| **Median** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 15.000 | 8.000 |
| **25th Percentile** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 8.000 | 7.000 |
| **Minimum** | 6.000 |  |  | 20.000 |  |  | 1.000 |  |  |  | 7.000 | 7.000 |
| **Variance** |  |  |  |  |  |  |  |  |  |  | 21.139 | 2.889 |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |  | 4.598 | 1.700 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
