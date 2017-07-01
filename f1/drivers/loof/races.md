---
title: List of Formula 1® Races by Ernst Loof
layout: page
collectionName: drivers
collectionId: loof
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
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 14 | 9 |
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Theo Helfrich 🇩🇪](/f1/drivers/helfrich) | 28 | 12 |
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Wolfgang Seidel 🇩🇪](/f1/drivers/seidel) | 29 | 16 |
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Oswald Karch 🇩🇪](/f1/drivers/karch) | 34 | R |
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Willi Heeks 🇩🇪](/f1/drivers/heeks) | 18 | R |
| 1953 | 7 | 1953 German Grand Prix 🇩🇪 | 1953-08-02T00:00:00.000Z | 31 | R | 0.0 | 0 |   | Veritas 🇩🇪 | [Erwin Bauer 🇩🇪](/f1/drivers/bauer) | 33 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 6 |  | 6 | 6 |  | 6 | 6 |  |  |  | 6 | 3 |
| **Total Sum** | 42.000 |  | -3108326400.000 | 186.000 |  |  |  |  |  |  | 156.000 | 37.000 |
| **Mean μ (Average)** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 26.000 | 12.333 |
| **Maximum** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 34.000 | 16.000 |
| **75th Percentile** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 33.000 | 16.000 |
| **Median** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 29.000 | 12.000 |
| **25th Percentile** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 18.000 | 9.000 |
| **Minimum** | 7.000 |  | -518054400.000 | 31.000 |  |  |  |  |  |  | 14.000 | 9.000 |
| **Variance** |  |  |  |  |  |  |  |  |  |  | 55.667 | 8.222 |
| **Standard Deviation σ** |  |  |  |  |  |  |  |  |  |  | 7.461 | 2.867 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
