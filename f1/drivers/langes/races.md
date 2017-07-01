---
title: List of Formula 1® Races by Claudio Langes
layout: page
collectionName: drivers
collectionId: langes
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
| 1990 | 14 | 1990 Spanish Grand Prix 🇪🇸 | 1990-09-30T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 13 | 1990 Portuguese Grand Prix 🇵🇹 | 1990-09-23T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 12 | 1990 Italian Grand Prix 🇮🇹 | 1990-09-09T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 11 | 1990 Belgian Grand Prix 🇧🇪 | 1990-08-26T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 10 | 1990 Hungarian Grand Prix 🇭🇺 | 1990-08-12T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 9 | 1990 German Grand Prix 🇩🇪 | 1990-07-29T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 8 | 1990 British Grand Prix 🇬🇧 | 1990-07-15T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 7 | 1990 French Grand Prix 🇫🇷 | 1990-07-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 6 | 1990 Mexican Grand Prix 🇲🇽 | 1990-06-24T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | D |
| 1990 | 5 | 1990 Canadian Grand Prix 🇨🇦 | 1990-06-10T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 4 | 1990 Monaco Grand Prix 🇲🇨 | 1990-05-27T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 3 | 1990 San Marino Grand Prix 🇮🇹 | 1990-05-13T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 24 | R |
| 1990 | 2 | 1990 Brazilian Grand Prix 🇧🇷 | 1990-03-25T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 0 | F |
| 1990 | 1 | 1990 United States Grand Prix 🇺🇸 | 1990-03-11T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Euro Brun 🇮🇹 | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 16 | 13 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 14 |  | 14 | 14 |  | 14 | 14 |  |  |  | 14 | 1 |
| **Total Sum** | 105.000 |  | 9061113600.000 |  |  |  |  |  |  |  | 40.000 | 13.000 |
| **Mean μ (Average)** | 7.500 |  | 647222400.000 |  |  |  |  |  |  |  | 2.857 | 13.000 |
| **Maximum** | 14.000 |  | 654652800.000 |  |  |  |  |  |  |  | 24.000 | 13.000 |
| **75th Percentile** | 11.000 |  | 651628800.000 |  |  |  |  |  |  |  |  | 13.000 |
| **Median** | 8.000 |  | 648000000.000 |  |  |  |  |  |  |  |  | 13.000 |
| **25th Percentile** | 4.000 |  | 643766400.000 |  |  |  |  |  |  |  |  | 13.000 |
| **Minimum** | 1.000 |  | 637113600.000 |  |  |  |  |  |  |  |  | 13.000 |
| **Variance** | 16.250 |  | 27769651200000.000 |  |  |  |  |  |  |  | 51.265 |  |
| **Standard Deviation σ** | 4.031 |  | 5269691.756 |  |  |  |  |  |  |  | 7.160 |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
