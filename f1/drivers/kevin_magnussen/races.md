---
title: List of Formula 1® Races by Kevin Magnussen
layout: page
collectionName: drivers
collectionId: kevin_magnussen
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
| 2017 | 8 | 2017 Azerbaijan Grand Prix 🇦🇿 | 2017-06-25T00:00:00.000Z | 12 | 7 | 6.0 | 51 | +41.753 | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 16 | 13 |
| 2017 | 7 | 2017 Canadian Grand Prix 🇨🇦 | 2017-06-11T00:00:00.000Z | 18 | 12 | 0.0 | 69 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 14 | 10 |
| 2017 | 6 | 2017 Monaco Grand Prix 🇲🇨 | 2017-05-28T00:00:00.000Z | 11 | 10 | 1.0 | 78 | +21.443 | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 8 | 8 |
| 2017 | 5 | 2017 Spanish Grand Prix 🇪🇸 | 2017-05-14T00:00:00.000Z | 11 | 14 | 0.0 | 64 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 14 | 10 |
| 2017 | 4 | 2017 Russian Grand Prix 🇷🇺 | 2017-04-30T00:00:00.000Z | 13 | 13 | 0.0 | 51 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 19 | R |
| 2017 | 3 | 2017 Bahrain Grand Prix 🇧🇭 | 2017-04-16T00:00:00.000Z | 20 | R | 0.0 | 8 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 9 | 8 |
| 2017 | 2 | 2017 Chinese Grand Prix 🇨🇳 | 2017-04-09T00:00:00.000Z | 12 | 8 | 4.0 | 55 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 19 | 11 |
| 2017 | 1 | 2017 Australian Grand Prix 🇦🇺 | 2017-03-26T00:00:00.000Z | 17 | R | 0.0 | 46 |   | Haas F1 Team 🇺🇸 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 6 | R |
| 2016 | 21 | 2016 Abu Dhabi Grand Prix 🇦🇪 | 2016-11-27T00:00:00.000Z | 18 | R | 0.0 | 5 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 15 | 17 |
| 2016 | 20 | 2016 Brazilian Grand Prix 🇧🇷 | 2016-11-13T00:00:00.000Z | 18 | 14 | 0.0 | 71 | +51.555 | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 16 | R |
| 2016 | 19 | 2016 Mexican Grand Prix 🇲🇽 | 2016-10-30T00:00:00.000Z | 14 | 17 | 0.0 | 70 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 21 | 14 |
| 2016 | 18 | 2016 United States Grand Prix 🇺🇸 | 2016-10-23T00:00:00.000Z | 18 | 12 | 0.0 | 55 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 15 | 13 |
| 2016 | 17 | 2016 Japanese Grand Prix 🇯🇵 | 2016-10-09T00:00:00.000Z | 17 | 14 | 0.0 | 52 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 16 | 12 |
| 2016 | 16 | 2016 Malaysian Grand Prix 🇲🇾 | 2016-10-02T00:00:00.000Z | 14 | R | 0.0 | 17 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 19 | 10 |
| 2016 | 15 | 2016 Singapore Grand Prix 🇸🇬 | 2016-09-18T00:00:00.000Z | 15 | 10 | 1.0 | 61 | +1:59.952 | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 18 | 15 |
| 2016 | 14 | 2016 Italian Grand Prix 🇮🇹 | 2016-09-04T00:00:00.000Z | 21 | 17 | 0.0 | 52 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 20 | R |
| 2016 | 13 | 2016 Belgian Grand Prix 🇧🇪 | 2016-08-28T00:00:00.000Z | 12 | R | 0.0 | 5 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 13 | 15 |
| 2016 | 12 | 2016 German Grand Prix 🇩🇪 | 2016-07-31T00:00:00.000Z | 16 | 16 | 0.0 | 66 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 14 | 19 |
| 2016 | 11 | 2016 Hungarian Grand Prix 🇭🇺 | 2016-07-24T00:00:00.000Z | 19 | 15 | 0.0 | 69 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 17 | 12 |
| 2016 | 10 | 2016 British Grand Prix 🇬🇧 | 2016-07-10T00:00:00.000Z | 16 | 17 | 0.0 | 49 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 18 | R |
| 2016 | 9 | 2016 Austrian Grand Prix 🇦🇹 | 2016-07-03T00:00:00.000Z | 17 | 14 | 0.0 | 70 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 19 | 12 |
| 2016 | 8 | 2016 European Grand Prix 🇦🇿 | 2016-06-19T00:00:00.000Z | 22 | 14 | 0.0 | 50 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 21 | 15 |
| 2016 | 7 | 2016 Canadian Grand Prix 🇨🇦 | 2016-06-12T00:00:00.000Z | 22 | 16 | 0.0 | 68 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 16 | R |
| 2016 | 6 | 2016 Monaco Grand Prix 🇲🇨 | 2016-05-29T00:00:00.000Z | 16 | R | 0.0 | 32 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 18 | R |
| 2016 | 5 | 2016 Spanish Grand Prix 🇪🇸 | 2016-05-15T00:00:00.000Z | 15 | 14 | 0.0 | 65 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 17 | 13 |
| 2016 | 4 | 2016 Russian Grand Prix 🇷🇺 | 2016-05-01T00:00:00.000Z | 17 | 7 | 6.0 | 52 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 18 | 13 |
| 2016 | 3 | 2016 Chinese Grand Prix 🇨🇳 | 2016-04-17T00:00:00.000Z | 17 | 17 | 0.0 | 55 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 19 | 22 |
| 2016 | 2 | 2016 Bahrain Grand Prix 🇧🇭 | 2016-04-03T00:00:00.000Z | 22 | 11 | 0.0 | 56 |   | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 19 | W |
| 2016 | 1 | 2016 Australian Grand Prix 🇦🇺 | 2016-03-20T00:00:00.000Z | 14 | 12 | 0.0 | 57 | +1:25.606 | Renault 🇫🇷 | [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 13 | 11 |
| 2015 | 1 | 2015 Australian Grand Prix 🇦🇺 | 2015-03-15T00:00:00.000Z | 17 | W | 0.0 | 0 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 16 | 11 |
| 2014 | 19 | 2014 Abu Dhabi Grand Prix 🇦🇪 | 2014-11-23T00:00:00.000Z | 9 | 11 | 0.0 | 55 | +1:30.376 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 6 | 5 |
| 2014 | 18 | 2014 Brazilian Grand Prix 🇧🇷 | 2014-11-09T00:00:00.000Z | 7 | 9 | 2.0 | 71 | +1:10.085 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 5 | 4 |
| 2014 | 17 | 2014 United States Grand Prix 🇺🇸 | 2014-11-02T00:00:00.000Z | 7 | 8 | 4.0 | 56 | +1:40.682 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 12 | 12 |
| 2014 | 16 | 2014 Russian Grand Prix 🇷🇺 | 2014-10-12T00:00:00.000Z | 11 | 5 | 10.0 | 53 | +53.616 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 4 | 4 |
| 2014 | 15 | 2014 Japanese Grand Prix 🇯🇵 | 2014-10-05T00:00:00.000Z | 7 | 14 | 0.0 | 43 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 8 | 5 |
| 2014 | 14 | 2014 Singapore Grand Prix 🇸🇬 | 2014-09-21T00:00:00.000Z | 9 | 10 | 1.0 | 60 | +1:02.230 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 11 | R |
| 2014 | 13 | 2014 Italian Grand Prix 🇮🇹 | 2014-09-07T00:00:00.000Z | 5 | 10 | 1.0 | 53 | +1:06.171 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 6 | 8 |
| 2014 | 12 | 2014 Belgian Grand Prix 🇧🇪 | 2014-08-24T00:00:00.000Z | 7 | 12 | 0.0 | 44 | +1:14.262 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 10 | 6 |
| 2014 | 11 | 2014 Hungarian Grand Prix 🇭🇺 | 2014-07-27T00:00:00.000Z | 21 | 12 | 0.0 | 70 | +1:18.465 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 7 | 10 |
| 2014 | 10 | 2014 German Grand Prix 🇩🇪 | 2014-07-20T00:00:00.000Z | 4 | 9 | 2.0 | 66 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 11 | 8 |
| 2014 | 9 | 2014 British Grand Prix 🇬🇧 | 2014-07-06T00:00:00.000Z | 5 | 7 | 6.0 | 52 | +1:02.563 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 3 | 4 |
| 2014 | 8 | 2014 Austrian Grand Prix 🇦🇹 | 2014-06-22T00:00:00.000Z | 6 | 7 | 6.0 | 71 | +32.031 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 11 | 11 |
| 2014 | 7 | 2014 Canadian Grand Prix 🇨🇦 | 2014-06-08T00:00:00.000Z | 12 | 9 | 2.0 | 70 | +29.254 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 9 | 4 |
| 2014 | 6 | 2014 Monaco Grand Prix 🇲🇨 | 2014-05-25T00:00:00.000Z | 8 | 10 | 1.0 | 77 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 12 | 6 |
| 2014 | 5 | 2014 Spanish Grand Prix 🇪🇸 | 2014-05-11T00:00:00.000Z | 14 | 12 | 0.0 | 65 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 8 | 11 |
| 2014 | 4 | 2014 Chinese Grand Prix 🇨🇳 | 2014-04-20T00:00:00.000Z | 15 | 13 | 0.0 | 53 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 12 | 11 |
| 2014 | 3 | 2014 Bahrain Grand Prix 🇧🇭 | 2014-04-06T00:00:00.000Z | 8 | R | 0.0 | 40 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 6 | 17 |
| 2014 | 2 | 2014 Malaysian Grand Prix 🇲🇾 | 2014-03-30T00:00:00.000Z | 8 | 9 | 2.0 | 55 |   | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 10 | 6 |
| 2014 | 1 | 2014 Australian Grand Prix 🇦🇺 | 2014-03-16T00:00:00.000Z | 4 | 2 | 18.0 | 57 | +26.777 | McLaren 🇬🇧 | [Jenson Button 🇬🇧](/f1/drivers/button) | 10 | 3 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 49 |  | 49 | 49 | 41 | 49 | 49 | 7 |  |  | 49 | 40 |
| **Total Sum** | 458.000 |  | 70952716800.000 | 658.000 | 470.000 | 73.000 | 2610.000 | 256.429 |  |  | 644.000 | 419.000 |
| **Mean μ (Average)** | 9.347 |  | 1448014628.571 | 13.429 | 11.463 | 1.490 | 53.265 | 36.633 |  |  | 13.143 | 10.475 |
| **Maximum** | 21.000 |  | 1498348800.000 | 22.000 | 17.000 | 18.000 | 78.000 | 53.616 |  |  | 21.000 | 22.000 |
| **75th Percentile** | 14.000 |  | 1475971200.000 | 17.000 | 14.000 | 1.000 | 66.000 | 51.555 |  |  | 18.000 | 13.000 |
| **Median** | 8.000 |  | 1463270400.000 | 14.000 | 12.000 |  | 55.000 | 32.031 |  |  | 14.000 | 11.000 |
| **25th Percentile** | 4.000 |  | 1410048000.000 | 9.000 | 9.000 |  | 51.000 | 26.777 |  |  | 9.000 | 8.000 |
| **Minimum** | 1.000 |  | 1394928000.000 | 4.000 | 2.000 |  |  | 21.443 |  |  | 3.000 | 3.000 |
| **Variance** | 34.798 |  | 1283424673959184.500 | 26.367 | 12.151 | 10.454 | 338.930 | 134.401 |  |  | 24.612 | 19.249 |
| **Standard Deviation σ** | 5.899 |  | 35824916.943 | 5.135 | 3.486 | 3.233 | 18.410 | 11.593 |  |  | 4.961 | 4.387 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
