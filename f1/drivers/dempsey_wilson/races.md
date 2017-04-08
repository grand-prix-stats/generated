---
title: List of Formula 1® Races by Dempsey Wilson
layout: page
collectionName: drivers
collectionId: dempsey_wilson
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
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Bob Christie 🇺🇸](/f1/drivers/christie) | 14 | 10 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Gene Hartley 🇺🇸](/f1/drivers/hartley) | 24 | 14 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Shorty Templeman 🇺🇸](/f1/drivers/templeman) | 19 | 17 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Don Freeland 🇺🇸](/f1/drivers/freeland) | 11 | 22 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Anthony Foyt 🇺🇸](/f1/drivers/foyt) | 16 | 25 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Eddie Russo 🇺🇸](/f1/drivers/russo) | 29 | 26 |
| 1960 | 3 | 1960 Indianapolis 500 🇺🇸 | 1960-05-30 | 33 | 33 | 0.0 | 11 |   | Kurtis Kraft 🇺🇸 | [Gene Force 🇺🇸](/f1/drivers/force) | 20 | 28 |
| 1958 | 4 | 1958 Indianapolis 500 🇺🇸 | 1958-05-30 | 32 | R | 0.0 | 151 |   | Kuzma 🇺🇸 | [Johnnie Tolan 🇺🇸](/f1/drivers/tolan) | 30 | 13 |
| 1958 | 4 | 1958 Indianapolis 500 🇺🇸 | 1958-05-30 | 32 | R | 0.0 | 151 |   | Kuzma 🇺🇸 | [Anthony Foyt 🇺🇸](/f1/drivers/foyt) | 12 | R |
| 1958 | 4 | 1958 Indianapolis 500 🇺🇸 | 1958-05-30 | 32 | R | 0.0 | 151 |   | Kuzma 🇺🇸 | [Eddie Sachs 🇺🇸](/f1/drivers/sachs) | 18 | R |
| 1958 | 4 | 1958 Indianapolis 500 🇺🇸 | 1958-05-30 | 32 | R | 0.0 | 151 |   | Kuzma 🇺🇸 | [Art Bisch 🇺🇸](/f1/drivers/bisch) | 28 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 11 |  |  | 11 | 7 | 11 | 11 |  |  |  | 11 | 8 |
| **Total Sum** | 37.000 |  |  | 359.000 | 231.000 |  | 681.000 |  |  |  | 221.000 | 155.000 |
| **Mean μ (Average)** | 3.364 |  |  | 32.636 | 33.000 |  | 61.909 |  |  |  | 20.091 | 19.375 |
| **Maximum** | 4.000 |  |  | 33.000 | 33.000 |  | 151.000 |  |  |  | 30.000 | 28.000 |
| **75th Percentile** | 4.000 |  |  | 33.000 | 33.000 |  | 151.000 |  |  |  | 28.000 | 26.000 |
| **Median** | 3.000 |  |  | 33.000 | 33.000 |  | 11.000 |  |  |  | 19.000 | 22.000 |
| **25th Percentile** | 3.000 |  |  | 32.000 | 33.000 |  | 11.000 |  |  |  | 14.000 | 14.000 |
| **Minimum** | 3.000 |  |  | 32.000 | 33.000 |  | 11.000 |  |  |  | 11.000 | 10.000 |
| **Variance** | 0.231 |  |  | 0.231 |  |  | 4535.537 |  |  |  | 42.083 | 39.984 |
| **Standard Deviation σ** | 0.481 |  |  | 0.481 |  |  | 67.346 |  |  |  | 6.487 | 6.323 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
