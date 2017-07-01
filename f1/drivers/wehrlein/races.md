---
title: List of Formula 1® Races by Pascal Wehrlein
layout: page
collectionName: drivers
collectionId: wehrlein
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
| 2017 | 8 | 2017 Azerbaijan Grand Prix 🇦🇿 | 2017-06-25T00:00:00.000Z | 14 | 10 | 1.0 | 51 | +1:29.093 | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 17 | 11 |
| 2017 | 7 | 2017 Canadian Grand Prix 🇨🇦 | 2017-06-11T00:00:00.000Z | 20 | 15 | 0.0 | 68 |   | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 19 | 13 |
| 2017 | 6 | 2017 Monaco Grand Prix 🇲🇨 | 2017-05-28T00:00:00.000Z | 18 | R | 0.0 | 57 |   | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 19 | R |
| 2017 | 5 | 2017 Spanish Grand Prix 🇪🇸 | 2017-05-14T00:00:00.000Z | 15 | 8 | 4.0 | 65 |   | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 16 | 11 |
| 2017 | 4 | 2017 Russian Grand Prix 🇷🇺 | 2017-04-30T00:00:00.000Z | 17 | 16 | 0.0 | 50 |   | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 18 | 15 |
| 2017 | 3 | 2017 Bahrain Grand Prix 🇧🇭 | 2017-04-16T00:00:00.000Z | 13 | 11 | 0.0 | 56 |   | Sauber 🇨🇭 | [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 19 | R |
| 2016 | 21 | 2016 Abu Dhabi Grand Prix 🇦🇪 | 2016-11-27T00:00:00.000Z | 16 | 14 | 0.0 | 54 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 20 | 13 |
| 2016 | 20 | 2016 Brazilian Grand Prix 🇧🇷 | 2016-11-13T00:00:00.000Z | 19 | 15 | 0.0 | 71 | +1:00.498 | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 22 | 12 |
| 2016 | 19 | 2016 Mexican Grand Prix 🇲🇽 | 2016-10-30T00:00:00.000Z | 16 | R | 0.0 | 0 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 20 | 21 |
| 2016 | 18 | 2016 United States Grand Prix 🇺🇸 | 2016-10-23T00:00:00.000Z | 20 | 17 | 0.0 | 55 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 22 | 18 |
| 2016 | 17 | 2016 Japanese Grand Prix 🇯🇵 | 2016-10-09T00:00:00.000Z | 21 | 22 | 0.0 | 52 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 20 | 21 |
| 2016 | 16 | 2016 Malaysian Grand Prix 🇲🇾 | 2016-10-02T00:00:00.000Z | 21 | 15 | 0.0 | 55 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 20 | 16 |
| 2016 | 15 | 2016 Singapore Grand Prix 🇸🇬 | 2016-09-18T00:00:00.000Z | 19 | 16 | 0.0 | 60 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 21 | 18 |
| 2016 | 14 | 2016 Italian Grand Prix 🇮🇹 | 2016-09-04T00:00:00.000Z | 13 | R | 0.0 | 26 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 22 | 18 |
| 2016 | 13 | 2016 Belgian Grand Prix 🇧🇪 | 2016-08-28T00:00:00.000Z | 15 | R | 0.0 | 0 |   | Manor Marussia 🇬🇧 | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 17 | 16 |
| 2016 | 12 | 2016 German Grand Prix 🇩🇪 | 2016-07-31T00:00:00.000Z | 17 | 17 | 0.0 | 65 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 19 | 20 |
| 2016 | 11 | 2016 Hungarian Grand Prix 🇭🇺 | 2016-07-24T00:00:00.000Z | 20 | 19 | 0.0 | 68 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 21 | 21 |
| 2016 | 10 | 2016 British Grand Prix 🇬🇧 | 2016-07-10T00:00:00.000Z | 20 | R | 0.0 | 6 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 19 | R |
| 2016 | 9 | 2016 Austrian Grand Prix 🇦🇹 | 2016-07-03T00:00:00.000Z | 12 | 10 | 1.0 | 70 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 20 | 16 |
| 2016 | 8 | 2016 European Grand Prix 🇦🇿 | 2016-06-19T00:00:00.000Z | 17 | R | 0.0 | 39 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 16 | 18 |
| 2016 | 7 | 2016 Canadian Grand Prix 🇨🇦 | 2016-06-12T00:00:00.000Z | 17 | 17 | 0.0 | 68 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 19 | 19 |
| 2016 | 6 | 2016 Monaco Grand Prix 🇲🇨 | 2016-05-29T00:00:00.000Z | 20 | 14 | 0.0 | 76 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 19 | 15 |
| 2016 | 5 | 2016 Spanish Grand Prix 🇪🇸 | 2016-05-15T00:00:00.000Z | 21 | 16 | 0.0 | 65 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 22 | 17 |
| 2016 | 4 | 2016 Russian Grand Prix 🇷🇺 | 2016-05-01T00:00:00.000Z | 20 | 18 | 0.0 | 51 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 21 | R |
| 2016 | 3 | 2016 Chinese Grand Prix 🇨🇳 | 2016-04-17T00:00:00.000Z | 21 | 18 | 0.0 | 55 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 20 | 21 |
| 2016 | 2 | 2016 Bahrain Grand Prix 🇧🇭 | 2016-04-03T00:00:00.000Z | 16 | 13 | 0.0 | 56 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 20 | 17 |
| 2016 | 1 | 2016 Australian Grand Prix 🇦🇺 | 2016-03-20T00:00:00.000Z | 21 | 16 | 0.0 | 56 |   | Manor Marussia 🇬🇧 | [Rio Haryanto 🇮🇩](/f1/drivers/haryanto) | 22 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 27 |  | 27 | 27 | 21 | 27 | 27 |  |  |  | 27 | 22 |
| **Total Sum** | 264.000 |  | 39832473600.000 | 479.000 | 317.000 | 6.000 | 1395.000 |  |  |  | 530.000 | 367.000 |
| **Mean μ (Average)** | 9.778 |  | 1475276800.000 | 17.741 | 15.095 | 0.222 | 51.667 |  |  |  | 19.630 | 16.682 |
| **Maximum** | 21.000 |  | 1498348800.000 | 21.000 | 22.000 | 4.000 | 76.000 |  |  |  | 22.000 | 21.000 |
| **75th Percentile** | 15.000 |  | 1480204800.000 | 20.000 | 17.000 |  | 65.000 |  |  |  | 21.000 | 19.000 |
| **Median** | 8.000 |  | 1472947200.000 | 18.000 | 16.000 |  | 56.000 |  |  |  | 20.000 | 17.000 |
| **25th Percentile** | 5.000 |  | 1465689600.000 | 16.000 | 14.000 |  | 51.000 |  |  |  | 19.000 | 15.000 |
| **Minimum** | 1.000 |  | 1458432000.000 | 12.000 | 8.000 |  |  |  |  |  | 16.000 | 11.000 |
| **Variance** | 34.395 |  | 148933406720000.000 | 7.599 | 10.467 | 0.617 | 410.222 |  |  |  | 2.974 | 9.944 |
| **Standard Deviation σ** | 5.865 |  | 12203827.544 | 2.757 | 3.235 | 0.786 | 20.254 |  |  |  | 1.725 | 3.153 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
