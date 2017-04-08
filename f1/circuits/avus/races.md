---
title: List of All Formula 1® Races at AVUS
layout: page
collectionName: circuits
collectionId: avus
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

| Season | Round | Name | Date | Laps Completed | Race Duration | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|
| 1959 | 6 | 1959 German Grand Prix 🇩🇪 | 1959-08-02 | 60 | 2:09:31.6 | [Tony Brooks 🇬🇧](/f1/drivers/brooks) | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 1 |  |  | 1 |  |  |  |
| **Total Sum** | 6.000 |  |  | 60.000 |  |  |  |
| **Mean μ (Average)** | 6.000 |  |  | 60.000 |  |  |  |
| **Maximum** | 6.000 |  |  | 60.000 |  |  |  |
| **75th Percentile** | 6.000 |  |  | 60.000 |  |  |  |
| **Median** | 6.000 |  |  | 60.000 |  |  |  |
| **25th Percentile** | 6.000 |  |  | 60.000 |  |  |  |
| **Minimum** | 6.000 |  |  | 60.000 |  |  |  |
| **Variance** |  |  |  |  |  |  |  |
| **Standard Deviation σ** |  |  |  |  |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
