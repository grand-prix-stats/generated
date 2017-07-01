---
title: List of Formula 1® Races by Max Chilton
layout: page
collectionName: drivers
collectionId: chilton
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
| 2014 | 15 | 2014 Japanese Grand Prix 🇯🇵 | 2014-10-05T00:00:00.000Z | 21 | 18 | 0.0 | 43 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 18 | 20 |
| 2014 | 14 | 2014 Singapore Grand Prix 🇸🇬 | 2014-09-21T00:00:00.000Z | 21 | 17 | 0.0 | 59 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 16 |
| 2014 | 13 | 2014 Italian Grand Prix 🇮🇹 | 2014-09-07T00:00:00.000Z | 20 | R | 0.0 | 5 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 18 |
| 2014 | 12 | 2014 Belgian Grand Prix 🇧🇪 | 2014-08-24T00:00:00.000Z | 19 | 16 | 0.0 | 43 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 16 | 18 |
| 2014 | 11 | 2014 Hungarian Grand Prix 🇭🇺 | 2014-07-27T00:00:00.000Z | 18 | 16 | 0.0 | 69 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 15 | 15 |
| 2014 | 10 | 2014 German Grand Prix 🇩🇪 | 2014-07-20T00:00:00.000Z | 21 | 17 | 0.0 | 65 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 17 | 15 |
| 2014 | 9 | 2014 British Grand Prix 🇬🇧 | 2014-07-06T00:00:00.000Z | 17 | 16 | 0.0 | 50 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 12 | 14 |
| 2014 | 8 | 2014 Austrian Grand Prix 🇦🇹 | 2014-06-22T00:00:00.000Z | 21 | 17 | 0.0 | 69 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 18 | 15 |
| 2014 | 7 | 2014 Canadian Grand Prix 🇨🇦 | 2014-06-08T00:00:00.000Z | 18 | R | 0.0 | 0 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | R |
| 2014 | 6 | 2014 Monaco Grand Prix 🇲🇨 | 2014-05-25T00:00:00.000Z | 19 | 14 | 0.0 | 75 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 9 |
| 2014 | 5 | 2014 Spanish Grand Prix 🇪🇸 | 2014-05-11T00:00:00.000Z | 17 | 19 | 0.0 | 64 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 18 | 18 |
| 2014 | 4 | 2014 Chinese Grand Prix 🇨🇳 | 2014-04-20T00:00:00.000Z | 21 | 19 | 0.0 | 52 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 17 |
| 2014 | 3 | 2014 Bahrain Grand Prix 🇧🇭 | 2014-04-06T00:00:00.000Z | 21 | 13 | 0.0 | 57 | +59.909 | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 16 |
| 2014 | 2 | 2014 Malaysian Grand Prix 🇲🇾 | 2014-03-30T00:00:00.000Z | 21 | 15 | 0.0 | 54 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | R |
| 2014 | 1 | 2014 Australian Grand Prix 🇦🇺 | 2014-03-16T00:00:00.000Z | 17 | 13 | 0.0 | 55 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 18 | N |
| 2013 | 19 | 2013 Brazilian Grand Prix 🇧🇷 | 2013-11-24T00:00:00.000Z | 22 | 19 | 0.0 | 69 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 17 |
| 2013 | 18 | 2013 United States Grand Prix 🇺🇸 | 2013-11-17T00:00:00.000Z | 21 | 21 | 0.0 | 54 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 18 |
| 2013 | 17 | 2013 Abu Dhabi Grand Prix 🇦🇪 | 2013-11-03T00:00:00.000Z | 20 | 21 | 0.0 | 53 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 20 |
| 2013 | 16 | 2013 Indian Grand Prix 🇮🇳 | 2013-10-27T00:00:00.000Z | 22 | 17 | 0.0 | 58 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 18 |
| 2013 | 15 | 2013 Japanese Grand Prix 🇯🇵 | 2013-10-13T00:00:00.000Z | 18 | 19 | 0.0 | 52 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | R |
| 2013 | 14 | 2013 Korean Grand Prix 🇰🇷 | 2013-10-06T00:00:00.000Z | 21 | 17 | 0.0 | 55 | +1:12.898 | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 22 | 16 |
| 2013 | 13 | 2013 Singapore Grand Prix 🇸🇬 | 2013-09-22T00:00:00.000Z | 22 | 17 | 0.0 | 60 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 18 |
| 2013 | 12 | 2013 Italian Grand Prix 🇮🇹 | 2013-09-08T00:00:00.000Z | 22 | 20 | 0.0 | 52 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 19 |
| 2013 | 11 | 2013 Belgian Grand Prix 🇧🇪 | 2013-08-25T00:00:00.000Z | 16 | 19 | 0.0 | 42 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 15 | 18 |
| 2013 | 10 | 2013 Hungarian Grand Prix 🇭🇺 | 2013-07-28T00:00:00.000Z | 22 | 17 | 0.0 | 67 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 21 | 16 |
| 2013 | 9 | 2013 German Grand Prix 🇩🇪 | 2013-07-07T00:00:00.000Z | 21 | 19 | 0.0 | 59 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | R |
| 2013 | 8 | 2013 British Grand Prix 🇬🇧 | 2013-06-30T00:00:00.000Z | 20 | 17 | 0.0 | 52 | +1:07.660 | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 16 |
| 2013 | 7 | 2013 Canadian Grand Prix 🇨🇦 | 2013-06-09T00:00:00.000Z | 20 | 19 | 0.0 | 67 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 17 |
| 2013 | 6 | 2013 Monaco Grand Prix 🇲🇨 | 2013-05-26T00:00:00.000Z | 22 | 14 | 0.0 | 78 | +49.885 | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 20 | R |
| 2013 | 5 | 2013 Spanish Grand Prix 🇪🇸 | 2013-05-12T00:00:00.000Z | 21 | 19 | 0.0 | 64 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 20 | 18 |
| 2013 | 4 | 2013 Bahrain Grand Prix 🇧🇭 | 2013-04-21T00:00:00.000Z | 21 | 20 | 0.0 | 56 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 19 |
| 2013 | 3 | 2013 Chinese Grand Prix 🇨🇳 | 2013-04-14T00:00:00.000Z | 19 | 17 | 0.0 | 55 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 18 | 15 |
| 2013 | 2 | 2013 Malaysian Grand Prix 🇲🇾 | 2013-03-24T00:00:00.000Z | 21 | 16 | 0.0 | 54 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 13 |
| 2013 | 1 | 2013 Australian Grand Prix 🇦🇺 | 2013-03-17T00:00:00.000Z | 20 | 17 | 0.0 | 56 |   | Marussia 🇷🇺 | [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 19 | 15 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 34 |  | 34 | 34 | 32 | 34 | 34 | 2 |  |  | 34 | 28 |
| **Total Sum** | 310.000 |  | 47175350400.000 | 683.000 | 555.000 |  | 1863.000 | 109.794 |  |  | 640.000 | 464.000 |
| **Mean μ (Average)** | 9.118 |  | 1387510305.882 | 20.088 | 17.344 |  | 54.794 | 54.897 |  |  | 18.824 | 16.571 |
| **Maximum** | 19.000 |  | 1412467200.000 | 22.000 | 21.000 |  | 78.000 | 59.909 |  |  | 22.000 | 20.000 |
| **75th Percentile** | 13.000 |  | 1402185600.000 | 21.000 | 19.000 |  | 64.000 | 59.909 |  |  | 20.000 | 18.000 |
| **Median** | 9.000 |  | 1384646400.000 | 21.000 | 17.000 |  | 56.000 | 59.909 |  |  | 19.000 | 17.000 |
| **25th Percentile** | 5.000 |  | 1373155200.000 | 19.000 | 16.000 |  | 52.000 | 49.885 |  |  | 18.000 | 15.000 |
| **Minimum** | 1.000 |  | 1363478400.000 | 16.000 | 13.000 |  |  | 49.885 |  |  | 12.000 | 9.000 |
| **Variance** | 25.986 |  | 241832267586436.062 | 2.786 | 4.288 |  | 240.811 | 25.120 |  |  | 4.028 | 5.102 |
| **Standard Deviation σ** | 5.098 |  | 15550957.128 | 1.669 | 2.071 |  | 15.518 | 5.012 |  |  | 2.007 | 2.259 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
