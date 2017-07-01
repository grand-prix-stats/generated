---
title: List of All Formula 1® Races at Reims-Gueux
layout: page
collectionName: circuits
collectionId: reims
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
| 1966 | 3 | 1966 French Grand Prix 🇫🇷 | 1966-07-03T00:00:00.000Z | 48 | 1:48:31.3 | [Jack Brabham 🇦🇺](/f1/drivers/jack_brabham) | Brabham-Repco 🇬🇧 |
| 1963 | 4 | 1963 French Grand Prix 🇫🇷 | 1963-06-30T00:00:00.000Z | 53 | 2:10:54.3 | [Jim Clark 🇬🇧](/f1/drivers/clark) | Lotus-Climax 🇬🇧 |
| 1961 | 4 | 1961 French Grand Prix 🇫🇷 | 1961-07-02T00:00:00.000Z | 52 | 2:14:17.5 | [Giancarlo Baghetti 🇮🇹](/f1/drivers/baghetti) | Ferrari 🇮🇹 |
| 1960 | 6 | 1960 French Grand Prix 🇫🇷 | 1960-07-03T00:00:00.000Z | 50 | 1:57:24.9 | [Jack Brabham 🇦🇺](/f1/drivers/jack_brabham) | Cooper-Climax 🇬🇧 |
| 1959 | 4 | 1959 French Grand Prix 🇫🇷 | 1959-07-05T00:00:00.000Z | 50 | 2:01:26.5 | [Tony Brooks 🇬🇧](/f1/drivers/brooks) | Ferrari 🇮🇹 |
| 1958 | 6 | 1958 French Grand Prix 🇫🇷 | 1958-07-06T00:00:00.000Z | 50 | 2:03:21.3 | [Mike Hawthorn 🇬🇧](/f1/drivers/hawthorn) | Ferrari 🇮🇹 |
| 1956 | 5 | 1956 French Grand Prix 🇫🇷 | 1956-07-01T00:00:00.000Z | 61 | 2:34:23.4 | [Peter Collins 🇬🇧](/f1/drivers/collins) | Ferrari 🇮🇹 |
| 1954 | 4 | 1954 French Grand Prix 🇫🇷 | 1954-07-04T00:00:00.000Z | 61 | 2:42:47.9 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Mercedes 🇩🇪 |
| 1953 | 5 | 1953 French Grand Prix 🇫🇷 | 1953-07-05T00:00:00.000Z | 60 | 2:44:18.6 | [Mike Hawthorn 🇬🇧](/f1/drivers/hawthorn) | Ferrari 🇮🇹 |
| 1951 | 4 | 1951 French Grand Prix 🇫🇷 | 1951-07-01T00:00:00.000Z | 77 | 3:22:11.0 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Alfa Romeo 🇮🇹 |
| 1950 | 6 | 1950 French Grand Prix 🇫🇷 | 1950-07-02T00:00:00.000Z | 64 | 2:57:52.8 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Alfa Romeo 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 11 |  | 11 | 11 |  |  |  |
| **Total Sum** | 51.000 |  | -4212604800.000 | 626.000 |  |  |  |
| **Mean μ (Average)** | 4.636 |  | -382964072.727 | 56.909 |  |  |  |
| **Maximum** | 6.000 |  | -110419200.000 | 77.000 |  |  |  |
| **75th Percentile** | 6.000 |  | -268272000.000 | 61.000 |  |  |  |
| **Median** | 4.000 |  | -362620800.000 | 53.000 |  |  |  |
| **25th Percentile** | 4.000 |  | -520473600.000 | 50.000 |  |  |  |
| **Minimum** | 3.000 |  | -615427200.000 | 48.000 |  |  |  |
| **Variance** | 0.959 |  | 23224115395660164.000 | 68.992 |  |  |  |
| **Standard Deviation σ** | 0.979 |  | 152394604.221 | 8.306 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
