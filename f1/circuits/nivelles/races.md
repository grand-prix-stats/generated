---
title: List of All Formula 1® Races at Nivelles-Baulers
layout: page
collectionName: circuits
collectionId: nivelles
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
| 1974 | 5 | 1974 Belgian Grand Prix 🇧🇪 | 1974-05-12T00:00:00.000Z | 85 | 1:44:20.57 | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | McLaren 🇬🇧 |
| 1972 | 5 | 1972 Belgian Grand Prix 🇧🇪 | 1972-06-04T00:00:00.000Z | 85 | 1:44:07.3 | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | Team Lotus 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 2 |  | 2 | 2 |  |  |  |
| **Total Sum** | 10.000 |  | 214012800.000 | 170.000 |  |  |  |
| **Mean μ (Average)** | 5.000 |  | 107006400.000 | 85.000 |  |  |  |
| **Maximum** | 5.000 |  | 137548800.000 | 85.000 |  |  |  |
| **75th Percentile** | 5.000 |  | 137548800.000 | 85.000 |  |  |  |
| **Median** | 5.000 |  | 137548800.000 | 85.000 |  |  |  |
| **25th Percentile** | 5.000 |  | 76464000.000 | 85.000 |  |  |  |
| **Minimum** | 5.000 |  | 76464000.000 | 85.000 |  |  |  |
| **Variance** |  |  | 932838197760000.000 |  |  |  |  |
| **Standard Deviation σ** |  |  | 30542400.000 |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
