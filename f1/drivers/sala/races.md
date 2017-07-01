---
title: List of Formula 1® Races by Luis Pérez-Sala
layout: page
collectionName: drivers
collectionId: sala
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
| 1989 | 16 | 1989 Australian Grand Prix 🇦🇺 | 1989-11-05T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 3 | 6 |
| 1989 | 15 | 1989 Japanese Grand Prix 🇯🇵 | 1989-10-22T00:00:00.000Z | 14 | R | 0.0 | 0 |   | Minardi 🇮🇹 | [Paolo Barilla 🇮🇹](/f1/drivers/barilla) | 19 | R |
| 1989 | 14 | 1989 Spanish Grand Prix 🇪🇸 | 1989-10-01T00:00:00.000Z | 20 | R | 0.0 | 47 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 4 | R |
| 1989 | 13 | 1989 Portuguese Grand Prix 🇵🇹 | 1989-09-24T00:00:00.000Z | 9 | 12 | 0.0 | 69 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 5 | 5 |
| 1989 | 12 | 1989 Italian Grand Prix 🇮🇹 | 1989-09-10T00:00:00.000Z | 26 | 8 | 0.0 | 51 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 15 | 7 |
| 1989 | 11 | 1989 Belgian Grand Prix 🇧🇪 | 1989-08-27T00:00:00.000Z | 25 | 15 | 0.0 | 41 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 14 | 9 |
| 1989 | 10 | 1989 Hungarian Grand Prix 🇭🇺 | 1989-08-13T00:00:00.000Z | 23 | R | 0.0 | 57 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 10 | R |
| 1989 | 9 | 1989 German Grand Prix 🇩🇪 | 1989-07-30T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 13 | 9 |
| 1989 | 8 | 1989 British Grand Prix 🇬🇧 | 1989-07-16T00:00:00.000Z | 15 | 6 | 1.0 | 63 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 11 | 5 |
| 1989 | 7 | 1989 French Grand Prix 🇫🇷 | 1989-07-09T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 23 | R |
| 1989 | 6 | 1989 Canadian Grand Prix 🇨🇦 | 1989-06-18T00:00:00.000Z | 24 | R | 0.0 | 11 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 11 | R |
| 1989 | 5 | 1989 United States Grand Prix 🇺🇸 | 1989-06-04T00:00:00.000Z | 20 | R | 0.0 | 46 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 15 | R |
| 1989 | 4 | 1989 Mexican Grand Prix 🇲🇽 | 1989-05-28T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 22 | R |
| 1989 | 3 | 1989 Monaco Grand Prix 🇲🇨 | 1989-05-07T00:00:00.000Z | 26 | R | 0.0 | 48 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 11 | R |
| 1989 | 2 | 1989 San Marino Grand Prix 🇮🇹 | 1989-04-23T00:00:00.000Z | 15 | R | 0.0 | 43 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 11 | R |
| 1989 | 1 | 1989 Brazilian Grand Prix 🇧🇷 | 1989-03-26T00:00:00.000Z | 23 | R | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 16 | R |
| 1988 | 16 | 1988 Australian Grand Prix 🇦🇺 | 1988-11-13T00:00:00.000Z | 21 | R | 0.0 | 41 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 14 | 7 |
| 1988 | 15 | 1988 Japanese Grand Prix 🇯🇵 | 1988-10-30T00:00:00.000Z | 22 | 15 | 0.0 | 49 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 17 | 13 |
| 1988 | 14 | 1988 Spanish Grand Prix 🇪🇸 | 1988-10-02T00:00:00.000Z | 24 | 12 | 0.0 | 70 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 20 | R |
| 1988 | 13 | 1988 Portuguese Grand Prix 🇵🇹 | 1988-09-25T00:00:00.000Z | 19 | 8 | 0.0 | 68 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 14 | R |
| 1988 | 12 | 1988 Italian Grand Prix 🇮🇹 | 1988-09-11T00:00:00.000Z | 19 | R | 0.0 | 12 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 14 | R |
| 1988 | 11 | 1988 Belgian Grand Prix 🇧🇪 | 1988-08-28T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 0 | F |
| 1988 | 10 | 1988 Hungarian Grand Prix 🇭🇺 | 1988-08-07T00:00:00.000Z | 11 | 10 | 0.0 | 72 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 16 | R |
| 1988 | 9 | 1988 German Grand Prix 🇩🇪 | 1988-07-24T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 0 | F |
| 1988 | 8 | 1988 British Grand Prix 🇬🇧 | 1988-07-10T00:00:00.000Z | 18 | R | 0.0 | 0 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 19 | 15 |
| 1988 | 7 | 1988 French Grand Prix 🇫🇷 | 1988-07-03T00:00:00.000Z | 25 | N | 0.0 | 70 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 22 | 15 |
| 1988 | 6 | 1988 Detroit Grand Prix 🇺🇸 | 1988-06-19T00:00:00.000Z | 25 | R | 0.0 | 54 |   | Minardi 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 16 | 6 |
| 1988 | 5 | 1988 Canadian Grand Prix 🇨🇦 | 1988-06-12T00:00:00.000Z | 21 | 13 | 0.0 | 64 |   | Minardi 🇮🇹 | [Adrián Campos 🇪🇸](/f1/drivers/campos) | 0 | F |
| 1988 | 4 | 1988 Mexican Grand Prix 🇲🇽 | 1988-05-29T00:00:00.000Z | 25 | 11 | 0.0 | 63 |   | Minardi 🇮🇹 | [Adrián Campos 🇪🇸](/f1/drivers/campos) | 0 | F |
| 1988 | 3 | 1988 Monaco Grand Prix 🇲🇨 | 1988-05-15T00:00:00.000Z | 15 | R | 0.0 | 36 |   | Minardi 🇮🇹 | [Adrián Campos 🇪🇸](/f1/drivers/campos) | 0 | F |
| 1988 | 2 | 1988 San Marino Grand Prix 🇮🇹 | 1988-05-01T00:00:00.000Z | 18 | 11 | 0.0 | 58 |   | Minardi 🇮🇹 | [Adrián Campos 🇪🇸](/f1/drivers/campos) | 22 | 16 |
| 1988 | 1 | 1988 Brazilian Grand Prix 🇧🇷 | 1988-04-03T00:00:00.000Z | 20 | R | 0.0 | 46 |   | Minardi 🇮🇹 | [Adrián Campos 🇪🇸](/f1/drivers/campos) | 23 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 32 |  | 32 | 32 | 11 | 32 | 32 |  |  |  | 32 | 12 |
| **Total Sum** | 272.000 |  | 19245772800.000 | 523.000 | 121.000 | 1.000 | 1179.000 |  |  |  | 400.000 | 113.000 |
| **Mean μ (Average)** | 8.500 |  | 601430400.000 | 16.344 | 11.000 | 0.031 | 36.844 |  |  |  | 12.500 | 9.417 |
| **Maximum** | 16.000 |  | 626227200.000 | 26.000 | 15.000 | 1.000 | 72.000 |  |  |  | 23.000 | 16.000 |
| **75th Percentile** | 13.000 |  | 617760000.000 | 24.000 | 13.000 |  | 63.000 |  |  |  | 19.000 | 15.000 |
| **Median** | 9.000 |  | 606873600.000 | 20.000 | 11.000 |  | 46.000 |  |  |  | 14.000 | 9.000 |
| **25th Percentile** | 5.000 |  | 585705600.000 | 14.000 | 8.000 |  |  |  |  |  | 10.000 | 6.000 |
| **Minimum** | 1.000 |  | 576028800.000 |  | 6.000 |  |  |  |  |  |  | 5.000 |
| **Variance** | 21.250 |  | 277286405760000.000 | 78.851 | 7.455 | 0.030 | 719.132 |  |  |  | 53.938 | 16.076 |
| **Standard Deviation σ** | 4.610 |  | 16651918.981 | 8.880 | 2.730 | 0.174 | 26.817 |  |  |  | 7.344 | 4.010 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
