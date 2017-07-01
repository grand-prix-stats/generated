---
title: List of Formula 1® Races by Karl Kling
layout: page
collectionName: drivers
collectionId: kling
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
| 1955 | 7 | 1955 Italian Grand Prix 🇮🇹 | 1955-09-11T00:00:00.000Z | 3 | R | 0.0 | 32 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 1 |
| 1955 | 7 | 1955 Italian Grand Prix 🇮🇹 | 1955-09-11T00:00:00.000Z | 3 | R | 0.0 | 32 |   | Mercedes 🇩🇪 | [Piero Taruffi 🇮🇹](/f1/drivers/taruffi) | 9 | 2 |
| 1955 | 7 | 1955 Italian Grand Prix 🇮🇹 | 1955-09-11T00:00:00.000Z | 3 | R | 0.0 | 32 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 2 | R |
| 1955 | 6 | 1955 British Grand Prix 🇬🇧 | 1955-07-16T00:00:00.000Z | 4 | 3 | 4.0 | 90 | +1:11.8 | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 1 | 1 |
| 1955 | 6 | 1955 British Grand Prix 🇬🇧 | 1955-07-16T00:00:00.000Z | 4 | 3 | 4.0 | 90 | +1:11.8 | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 2 | 2 |
| 1955 | 6 | 1955 British Grand Prix 🇬🇧 | 1955-07-16T00:00:00.000Z | 4 | 3 | 4.0 | 90 | +1:11.8 | Mercedes 🇩🇪 | [Piero Taruffi 🇮🇹](/f1/drivers/taruffi) | 5 | 4 |
| 1955 | 5 | 1955 Dutch Grand Prix 🇳🇱 | 1955-06-19T00:00:00.000Z | 3 | R | 0.0 | 21 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 1 |
| 1955 | 5 | 1955 Dutch Grand Prix 🇳🇱 | 1955-06-19T00:00:00.000Z | 3 | R | 0.0 | 21 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 2 | 2 |
| 1955 | 4 | 1955 Belgian Grand Prix 🇧🇪 | 1955-06-05T00:00:00.000Z | 6 | R | 0.0 | 21 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 2 | 1 |
| 1955 | 4 | 1955 Belgian Grand Prix 🇧🇪 | 1955-06-05T00:00:00.000Z | 6 | R | 0.0 | 21 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 3 | 2 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 3 | 1 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 8 | R |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 3 | 1 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 8 | R |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 6 | R | 0.0 | 2 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 3 | 1 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 8 | R |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 3 | 1 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 10 | 4 |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 8 | R |
| 1955 | 1 | 1955 Argentine Grand Prix 🇦🇷 | 1955-01-16T00:00:00.000Z | 10 | 4 | 1.0 | 94 |   | Mercedes 🇩🇪 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 10 | 4 |
| 1954 | 9 | 1954 Spanish Grand Prix 🇪🇸 | 1954-10-24T00:00:00.000Z | 12 | 5 | 2.0 | 79 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 2 | 3 |
| 1954 | 9 | 1954 Spanish Grand Prix 🇪🇸 | 1954-10-24T00:00:00.000Z | 12 | 5 | 2.0 | 79 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 9 | R |
| 1954 | 8 | 1954 Italian Grand Prix 🇮🇹 | 1954-09-05T00:00:00.000Z | 4 | R | 0.0 | 36 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 1 |
| 1954 | 8 | 1954 Italian Grand Prix 🇮🇹 | 1954-09-05T00:00:00.000Z | 4 | R | 0.0 | 36 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 8 | 4 |
| 1954 | 7 | 1954 Swiss Grand Prix 🇨🇭 | 1954-08-22T00:00:00.000Z | 5 | R | 0.0 | 38 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 2 | 1 |
| 1954 | 7 | 1954 Swiss Grand Prix 🇨🇭 | 1954-08-22T00:00:00.000Z | 5 | R | 0.0 | 38 |   | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 7 | 3 |
| 1954 | 6 | 1954 German Grand Prix 🇩🇪 | 1954-08-01T00:00:00.000Z | 23 | 4 | 4.0 | 22 | +6:06.5 | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 1 |
| 1954 | 6 | 1954 German Grand Prix 🇩🇪 | 1954-08-01T00:00:00.000Z | 23 | 4 | 4.0 | 22 | +6:06.5 | Mercedes 🇩🇪 | [Hermann Lang 🇩🇪](/f1/drivers/lang) | 13 | R |
| 1954 | 6 | 1954 German Grand Prix 🇩🇪 | 1954-08-01T00:00:00.000Z | 23 | 4 | 4.0 | 22 | +6:06.5 | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 4 | R |
| 1954 | 5 | 1954 British Grand Prix 🇬🇧 | 1954-07-17T00:00:00.000Z | 6 | 7 | 0.0 | 87 |   | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 4 |
| 1954 | 4 | 1954 French Grand Prix 🇫🇷 | 1954-07-04T00:00:00.000Z | 2 | 2 | 6.0 | 61 | +0.1 | Mercedes 🇩🇪 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 1 | 1 |
| 1954 | 4 | 1954 French Grand Prix 🇫🇷 | 1954-07-04T00:00:00.000Z | 2 | 2 | 6.0 | 61 | +0.1 | Mercedes 🇩🇪 | [Hans Herrmann 🇩🇪](/f1/drivers/herrmann) | 7 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 38 |  | 38 | 38 | 19 | 38 | 38 | 2 |  |  | 38 | 29 |
| **Total Sum** | 152.000 |  | -17936121600.000 | 288.000 | 74.000 | 48.000 | 1799.000 | 0.200 |  |  | 208.000 | 70.000 |
| **Mean μ (Average)** | 4.000 |  | -472003200.000 | 7.579 | 3.895 | 1.263 | 47.342 | 0.100 |  |  | 5.474 | 2.414 |
| **Maximum** | 9.000 |  | -451526400.000 | 23.000 | 7.000 | 6.000 | 94.000 | 0.100 |  |  | 13.000 | 4.000 |
| **75th Percentile** | 6.000 |  | -459993600.000 | 10.000 | 4.000 | 2.000 | 90.000 | 0.100 |  |  | 9.000 | 4.000 |
| **Median** | 4.000 |  | -472089600.000 | 6.000 | 4.000 |  | 36.000 | 0.100 |  |  | 5.000 | 2.000 |
| **25th Percentile** | 1.000 |  | -483580800.000 | 4.000 | 3.000 |  | 21.000 | 0.100 |  |  | 2.000 | 1.000 |
| **Minimum** | 1.000 |  | -489024000.000 | 2.000 | 2.000 |  | 2.000 | 0.100 |  |  | 1.000 | 1.000 |
| **Variance** | 7.842 |  | 126218722357894.734 | 28.191 | 1.147 | 3.247 | 1292.436 |  |  |  | 13.881 | 1.829 |
| **Standard Deviation σ** | 2.800 |  | 11234710.604 | 5.310 | 1.071 | 1.802 | 35.950 |  |  |  | 3.726 | 1.352 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
