---
title: List of Formula 1® Races by Hideki Noda
layout: page
collectionName: drivers
collectionId: noda
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
| 1994 | 16 | 1994 Australian Grand Prix 🇦🇺 | 1994-11-13T00:00:00.000Z | 23 | R | 0.0 | 18 |   | Larrousse 🇫🇷 | [Jean-Denis Délétraz 🇨🇭](/f1/drivers/deletraz) | 25 | R |
| 1994 | 15 | 1994 Japanese Grand Prix 🇯🇵 | 1994-11-06T00:00:00.000Z | 23 | R | 0.0 | 0 |   | Larrousse 🇫🇷 | [Érik Comas 🇫🇷](/f1/drivers/comas) | 22 | 9 |
| 1994 | 14 | 1994 European Grand Prix 🇪🇸 | 1994-10-16T00:00:00.000Z | 24 | R | 0.0 | 10 |   | Larrousse 🇫🇷 | [Érik Comas 🇫🇷](/f1/drivers/comas) | 23 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 3 |  | 3 | 3 |  | 3 | 3 |  |  |  | 3 | 1 |
| **Total Sum** | 45.000 |  | 2351030400.000 | 70.000 |  |  | 28.000 |  |  |  | 70.000 | 9.000 |
| **Mean μ (Average)** | 15.000 |  | 783676800.000 | 23.333 |  |  | 9.333 |  |  |  | 23.333 | 9.000 |
| **Maximum** | 16.000 |  | 784684800.000 | 24.000 |  |  | 18.000 |  |  |  | 25.000 | 9.000 |
| **75th Percentile** | 16.000 |  | 784684800.000 | 24.000 |  |  | 18.000 |  |  |  | 25.000 | 9.000 |
| **Median** | 15.000 |  | 784080000.000 | 23.000 |  |  | 10.000 |  |  |  | 23.000 | 9.000 |
| **25th Percentile** | 14.000 |  | 782265600.000 | 23.000 |  |  |  |  |  |  | 22.000 | 9.000 |
| **Minimum** | 14.000 |  | 782265600.000 | 23.000 |  |  |  |  |  |  | 22.000 | 9.000 |
| **Variance** | 0.667 |  | 1056706560000.000 | 0.222 |  |  | 54.222 |  |  |  | 1.556 |  |
| **Standard Deviation σ** | 0.816 |  | 1027962.334 | 0.471 |  |  | 7.364 |  |  |  | 1.247 |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
