---
title: List of Formula 1® Races by Moisés Solana
layout: page
collectionName: drivers
collectionId: solana
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
| 1968 | 12 | 1968 Mexican Grand Prix 🇲🇽 | 1968-11-03T00:00:00.000Z | 11 | R | 0.0 | 14 |   | Lotus-Ford 🇬🇧 | [Graham Hill 🇬🇧](/f1/drivers/hill) | 3 | 1 |
| 1968 | 12 | 1968 Mexican Grand Prix 🇲🇽 | 1968-11-03T00:00:00.000Z | 11 | R | 0.0 | 14 |   | Lotus-Ford 🇬🇧 | [Jackie Oliver 🇬🇧](/f1/drivers/oliver) | 14 | 3 |
| 1968 | 12 | 1968 Mexican Grand Prix 🇲🇽 | 1968-11-03T00:00:00.000Z | 11 | R | 0.0 | 14 |   | Lotus-Ford 🇬🇧 | [Jo Siffert 🇨🇭](/f1/drivers/siffert) | 1 | 6 |
| 1967 | 11 | 1967 Mexican Grand Prix 🇲🇽 | 1967-10-22T00:00:00.000Z | 9 | R | 0.0 | 12 |   | Lotus-BRM 🇬🇧 | [Mike Fisher 🇺🇸](/f1/drivers/fisher) | 10 | R |
| 1967 | 10 | 1967 United States Grand Prix 🇺🇸 | 1967-10-01T00:00:00.000Z | 7 | R | 0.0 | 7 |   | Lotus-Ford 🇬🇧 | [Jim Clark 🇬🇧](/f1/drivers/clark) | 2 | 1 |
| 1967 | 10 | 1967 United States Grand Prix 🇺🇸 | 1967-10-01T00:00:00.000Z | 7 | R | 0.0 | 7 |   | Lotus-Ford 🇬🇧 | [Graham Hill 🇬🇧](/f1/drivers/hill) | 1 | 2 |
| 1966 | 9 | 1966 Mexican Grand Prix 🇲🇽 | 1966-10-23T00:00:00.000Z | 15 | R | 0.0 | 9 |   | Cooper-Maserati 🇬🇧 | [John Surtees 🇬🇧](/f1/drivers/surtees) | 1 | 1 |
| 1966 | 9 | 1966 Mexican Grand Prix 🇲🇽 | 1966-10-23T00:00:00.000Z | 15 | R | 0.0 | 9 |   | Cooper-Maserati 🇬🇧 | [Jo Bonnier 🇸🇪](/f1/drivers/bonnier) | 12 | 6 |
| 1966 | 9 | 1966 Mexican Grand Prix 🇲🇽 | 1966-10-23T00:00:00.000Z | 15 | R | 0.0 | 9 |   | Cooper-Maserati 🇬🇧 | [Jo Siffert 🇨🇭](/f1/drivers/siffert) | 11 | R |
| 1966 | 9 | 1966 Mexican Grand Prix 🇲🇽 | 1966-10-23T00:00:00.000Z | 15 | R | 0.0 | 9 |   | Cooper-Maserati 🇬🇧 | [Jochen Rindt 🇦🇹](/f1/drivers/rindt) | 5 | R |
| 1965 | 10 | 1965 Mexican Grand Prix 🇲🇽 | 1965-10-24T00:00:00.000Z | 9 | R | 0.0 | 55 |   | Lotus-Climax 🇬🇧 | [Mike Spence 🇬🇧](/f1/drivers/spence) | 6 | 3 |
| 1965 | 10 | 1965 Mexican Grand Prix 🇲🇽 | 1965-10-24T00:00:00.000Z | 9 | R | 0.0 | 55 |   | Lotus-Climax 🇬🇧 | [Jim Clark 🇬🇧](/f1/drivers/clark) | 1 | R |
| 1965 | 9 | 1965 United States Grand Prix 🇺🇸 | 1965-10-03T00:00:00.000Z | 17 | 12 | 0.0 | 95 |   | Lotus-Climax 🇬🇧 | [Jim Clark 🇬🇧](/f1/drivers/clark) | 9 | R |
| 1965 | 9 | 1965 United States Grand Prix 🇺🇸 | 1965-10-03T00:00:00.000Z | 17 | 12 | 0.0 | 95 |   | Lotus-Climax 🇬🇧 | [Mike Spence 🇬🇧](/f1/drivers/spence) | 4 | R |
| 1964 | 10 | 1964 Mexican Grand Prix 🇲🇽 | 1964-10-25T00:00:00.000Z | 14 | 10 | 0.0 | 63 |   | Lotus-Climax 🇬🇧 | [Mike Spence 🇬🇧](/f1/drivers/spence) | 5 | 4 |
| 1964 | 10 | 1964 Mexican Grand Prix 🇲🇽 | 1964-10-25T00:00:00.000Z | 14 | 10 | 0.0 | 63 |   | Lotus-Climax 🇬🇧 | [Jim Clark 🇬🇧](/f1/drivers/clark) | 1 | 5 |
| 1963 | 9 | 1963 Mexican Grand Prix 🇲🇽 | 1963-10-27T00:00:00.000Z | 11 | 11 | 0.0 | 57 |   | BRM 🇬🇧 | [Richie Ginther 🇺🇸](/f1/drivers/ginther) | 5 | 3 |
| 1963 | 9 | 1963 Mexican Grand Prix 🇲🇽 | 1963-10-27T00:00:00.000Z | 11 | 11 | 0.0 | 57 |   | BRM 🇬🇧 | [Graham Hill 🇬🇧](/f1/drivers/hill) | 3 | 4 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 18 |  | 18 | 18 | 6 | 18 | 18 |  |  |  | 18 | 12 |
| **Total Sum** | 179.000 |  | -1974240000.000 | 218.000 | 66.000 |  | 644.000 |  |  |  | 94.000 | 39.000 |
| **Mean μ (Average)** | 9.944 |  | -109680000.000 | 12.111 | 11.000 |  | 35.778 |  |  |  | 5.222 | 3.250 |
| **Maximum** | 12.000 |  | -36633600.000 | 17.000 | 12.000 |  | 95.000 |  |  |  | 14.000 | 6.000 |
| **75th Percentile** | 10.000 |  | -71107200.000 | 15.000 | 12.000 |  | 57.000 |  |  |  | 9.000 | 5.000 |
| **Median** | 10.000 |  | -100742400.000 | 11.000 | 11.000 |  | 14.000 |  |  |  | 5.000 | 3.000 |
| **25th Percentile** | 9.000 |  | -134006400.000 | 9.000 | 10.000 |  | 9.000 |  |  |  | 1.000 | 2.000 |
| **Minimum** | 9.000 |  | -195091200.000 | 7.000 | 10.000 |  | 7.000 |  |  |  | 1.000 | 1.000 |
| **Variance** | 1.164 |  | 2419149035520000.000 | 9.765 | 0.667 |  | 924.951 |  |  |  | 16.951 | 3.021 |
| **Standard Deviation σ** | 1.079 |  | 49184845.588 | 3.125 | 0.816 |  | 30.413 |  |  |  | 4.117 | 1.738 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
