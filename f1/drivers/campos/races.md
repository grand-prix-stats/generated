---
title: List of Formula 1® Races by Adrián Campos
layout: page
collectionName: drivers
collectionId: campos
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
| 1988 | 5 | 1988 Canadian Grand Prix 🇨🇦 | 1988-06-12T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 21 | 13 |
| 1988 | 4 | 1988 Mexican Grand Prix 🇲🇽 | 1988-05-29T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 25 | 11 |
| 1988 | 3 | 1988 Monaco Grand Prix 🇲🇨 | 1988-05-15T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 15 | R |
| 1988 | 2 | 1988 San Marino Grand Prix 🇮🇹 | 1988-05-01T00:00:00.000Z | 22 | 16 | 0.0 | 57 |   | Minardi 🇮🇹 | [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 18 | 11 |
| 1988 | 1 | 1988 Brazilian Grand Prix 🇧🇷 | 1988-04-03T00:00:00.000Z | 23 | R | 0.0 | 5 |   | Minardi 🇮🇹 | [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 20 | R |
| 1987 | 16 | 1987 Australian Grand Prix 🇦🇺 | 1987-11-15T00:00:00.000Z | 26 | R | 0.0 | 46 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 13 | R |
| 1987 | 15 | 1987 Japanese Grand Prix 🇯🇵 | 1987-11-01T00:00:00.000Z | 21 | R | 0.0 | 2 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 14 | R |
| 1987 | 14 | 1987 Mexican Grand Prix 🇲🇽 | 1987-10-18T00:00:00.000Z | 19 | R | 0.0 | 32 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 14 | R |
| 1987 | 13 | 1987 Spanish Grand Prix 🇪🇸 | 1987-09-27T00:00:00.000Z | 24 | 14 | 0.0 | 68 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 21 | R |
| 1987 | 12 | 1987 Portuguese Grand Prix 🇵🇹 | 1987-09-20T00:00:00.000Z | 20 | R | 0.0 | 24 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 14 | 11 |
| 1987 | 11 | 1987 Italian Grand Prix 🇮🇹 | 1987-09-06T00:00:00.000Z | 20 | R | 0.0 | 34 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 18 | 16 |
| 1987 | 10 | 1987 Austrian Grand Prix 🇦🇹 | 1987-08-16T00:00:00.000Z | 19 | R | 0.0 | 3 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 15 | R |
| 1987 | 9 | 1987 Hungarian Grand Prix 🇭🇺 | 1987-08-09T00:00:00.000Z | 24 | R | 0.0 | 14 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 20 | 11 |
| 1987 | 8 | 1987 German Grand Prix 🇩🇪 | 1987-07-26T00:00:00.000Z | 18 | R | 0.0 | 28 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 16 | R |
| 1987 | 7 | 1987 British Grand Prix 🇬🇧 | 1987-07-12T00:00:00.000Z | 19 | R | 0.0 | 34 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 15 | R |
| 1987 | 6 | 1987 French Grand Prix 🇫🇷 | 1987-07-05T00:00:00.000Z | 21 | R | 0.0 | 52 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 15 | R |
| 1987 | 5 | 1987 Detroit Grand Prix 🇺🇸 | 1987-06-21T00:00:00.000Z | 25 | R | 0.0 | 1 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 18 | R |
| 1987 | 4 | 1987 Monaco Grand Prix 🇲🇨 | 1987-05-31T00:00:00.000Z | 0 | W | 0.0 | 0 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 13 | R |
| 1987 | 3 | 1987 Belgian Grand Prix 🇧🇪 | 1987-05-17T00:00:00.000Z | 19 | R | 0.0 | 0 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 14 | R |
| 1987 | 2 | 1987 San Marino Grand Prix 🇮🇹 | 1987-05-03T00:00:00.000Z | 16 | R | 0.0 | 30 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 15 | R |
| 1987 | 1 | 1987 Brazilian Grand Prix 🇧🇷 | 1987-04-12T00:00:00.000Z | 16 | D | 0.0 | 3 |   | Minardi 🇮🇹 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 15 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 21 |  | 21 | 21 | 2 | 21 | 21 |  |  |  | 21 | 6 |
| **Total Sum** | 151.000 |  | 11774246400.000 | 352.000 | 30.000 |  | 433.000 |  |  |  | 349.000 | 73.000 |
| **Mean μ (Average)** | 7.190 |  | 560678400.000 | 16.762 | 15.000 |  | 20.619 |  |  |  | 16.619 | 12.167 |
| **Maximum** | 16.000 |  | 582076800.000 | 26.000 | 16.000 |  | 68.000 |  |  |  | 25.000 | 16.000 |
| **75th Percentile** | 11.000 |  | 563932800.000 | 22.000 | 16.000 |  | 34.000 |  |  |  | 18.000 | 13.000 |
| **Median** | 6.000 |  | 557884800.000 | 19.000 | 16.000 |  | 14.000 |  |  |  | 15.000 | 11.000 |
| **25th Percentile** | 3.000 |  | 552441600.000 | 16.000 | 14.000 |  | 1.000 |  |  |  | 14.000 | 11.000 |
| **Minimum** | 1.000 |  | 545184000.000 |  | 14.000 |  |  |  |  |  | 13.000 | 11.000 |
| **Variance** | 22.154 |  | 134206709760000.000 | 72.753 | 1.000 |  | 457.379 |  |  |  | 9.855 | 3.472 |
| **Standard Deviation σ** | 4.707 |  | 11584761.964 | 8.530 | 1.000 |  | 21.386 |  |  |  | 3.139 | 1.863 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
