---
title: List of Formula 1® Races by Cliff Griffith
layout: page
collectionName: drivers
collectionId: griffith
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
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Jim Rathmann 🇺🇸](/f1/drivers/rathmann) | 10 | 2 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Sam Hanks 🇺🇸](/f1/drivers/hanks) | 5 | 3 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Art Cross 🇺🇸](/f1/drivers/cross) | 20 | 5 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Jimmy Bryan 🇺🇸](/f1/drivers/bryan) | 21 | 6 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Jimmy Reece 🇺🇸](/f1/drivers/reece) | 23 | 7 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [George Connor 🇺🇸](/f1/drivers/george_connor) | 14 | 8 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Johnnie Parsons 🇺🇸](/f1/drivers/parsons) | 31 | 10 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Jack McGrath 🇺🇸](/f1/drivers/mcgrath) | 3 | 11 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Joe James 🇺🇸](/f1/drivers/james) | 16 | 13 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Bill Vukovich 🇺🇸](/f1/drivers/vukovich) | 8 | 17 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Chuck Stevenson 🇺🇸](/f1/drivers/stevenson) | 11 | 18 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Johnny McDowell 🇺🇸](/f1/drivers/mcdowell) | 33 | 21 |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Rodger Ward 🇺🇸](/f1/drivers/ward) | 22 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Duke Nalon 🇺🇸](/f1/drivers/nalon) | 4 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Bob Sweikert 🇺🇸](/f1/drivers/sweikert) | 32 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Fred Agabashian 🇺🇸](/f1/drivers/agabashian) | 1 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Gene Hartley 🇺🇸](/f1/drivers/hartley) | 18 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Bob Scott 🇺🇸](/f1/drivers/bob_scott) | 25 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Chet Miller 🇺🇸](/f1/drivers/miller) | 27 | R |
| 1952 | 2 | 1952 Indianapolis 500 🇺🇸 | 1952-05-30T00:00:00.000Z | 9 | 9 | 0.0 | 200 | +12:23.76 | Kurtis Kraft 🇺🇸 | [Andy Linden 🇺🇸](/f1/drivers/linden) | 2 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Lee Wallard 🇺🇸](/f1/drivers/wallard) | 2 | 1 |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Mike Nazaruk 🇺🇸](/f1/drivers/nazaruk) | 7 | 2 |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Jack McGrath 🇺🇸](/f1/drivers/mcgrath) | 3 | 3 |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Carl Forberg 🇺🇸](/f1/drivers/forberg) | 24 | 7 |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Duke Nalon 🇺🇸](/f1/drivers/nalon) | 1 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Gene Force 🇺🇸](/f1/drivers/force) | 22 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Sam Hanks 🇺🇸](/f1/drivers/hanks) | 12 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Bill Schindler 🇺🇸](/f1/drivers/schindler) | 16 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Fred Agabashian 🇺🇸](/f1/drivers/agabashian) | 11 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Carl Scarborough 🇺🇸](/f1/drivers/scarborough) | 15 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Johnnie Parsons 🇺🇸](/f1/drivers/parsons) | 8 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Cecil Green 🇺🇸](/f1/drivers/green) | 10 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Troy Ruttman 🇺🇸](/f1/drivers/ruttman) | 6 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Chet Miller 🇺🇸](/f1/drivers/miller) | 28 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Walt Brown 🇺🇸](/f1/drivers/walt_brown) | 13 | R |
| 1951 | 2 | 1951 Indianapolis 500 🇺🇸 | 1951-05-30T00:00:00.000Z | 18 | R | 0.0 | 30 |   | Kurtis Kraft 🇺🇸 | [Manny Ayulo 🇺🇸](/f1/drivers/ayulo) | 3 | 3 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 36 |  | 36 | 36 | 20 | 36 | 36 |  |  |  | 36 | 17 |
| **Total Sum** | 72.000 |  | -20490278400.000 | 468.000 | 180.000 |  | 4480.000 |  |  |  | 507.000 | 137.000 |
| **Mean μ (Average)** | 2.000 |  | -569174400.000 | 13.000 | 9.000 |  | 124.444 |  |  |  | 14.083 | 8.059 |
| **Maximum** | 2.000 |  | -555120000.000 | 18.000 | 9.000 |  | 200.000 |  |  |  | 33.000 | 21.000 |
| **75th Percentile** | 2.000 |  | -555120000.000 | 18.000 | 9.000 |  | 200.000 |  |  |  | 22.000 | 11.000 |
| **Median** | 2.000 |  | -555120000.000 | 9.000 | 9.000 |  | 200.000 |  |  |  | 13.000 | 7.000 |
| **25th Percentile** | 2.000 |  | -586742400.000 | 9.000 | 9.000 |  | 30.000 |  |  |  | 6.000 | 3.000 |
| **Minimum** | 2.000 |  | -586742400.000 | 9.000 | 9.000 |  | 30.000 |  |  |  | 1.000 | 1.000 |
| **Variance** |  |  | 246907699200000.000 | 20.000 |  |  | 7135.802 |  |  |  | 91.354 | 35.232 |
| **Standard Deviation σ** |  |  | 15713296.891 | 4.472 |  |  | 84.474 |  |  |  | 9.558 | 5.936 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
