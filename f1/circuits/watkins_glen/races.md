---
title: List of All Formula 1® Races at Watkins Glen
layout: page
collectionName: circuits
collectionId: watkins_glen
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
| 1980 | 14 | 1980 United States Grand Prix 🇺🇸 | 1980-10-05T00:00:00.000Z | 59 | 1:34:36.05 | [Alan Jones 🇦🇺](/f1/drivers/jones) | Williams 🇬🇧 |
| 1979 | 15 | 1979 United States Grand Prix 🇺🇸 | 1979-10-07T00:00:00.000Z | 59 | 1:52:17.734 | [Gilles Villeneuve 🇨🇦](/f1/drivers/gilles_villeneuve) | Ferrari 🇮🇹 |
| 1978 | 15 | 1978 United States Grand Prix 🇺🇸 | 1978-10-01T00:00:00.000Z | 59 | 1:40:48.800 | [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | Ferrari 🇮🇹 |
| 1977 | 15 | 1977 United States Grand Prix 🇺🇸 | 1977-10-02T00:00:00.000Z | 59 | 1:58:23.267 | [James Hunt 🇬🇧](/f1/drivers/hunt) | McLaren 🇬🇧 |
| 1976 | 15 | 1976 United States Grand Prix 🇺🇸 | 1976-10-10T00:00:00.000Z | 59 | 1:42:40.742 | [James Hunt 🇬🇧](/f1/drivers/hunt) | McLaren 🇬🇧 |
| 1975 | 14 | 1975 United States Grand Prix 🇺🇸 | 1975-10-05T00:00:00.000Z | 59 | 1:42:58.175 | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | Ferrari 🇮🇹 |
| 1974 | 15 | 1974 United States Grand Prix 🇺🇸 | 1974-10-06T00:00:00.000Z | 59 | 1:40:21.439 | [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | Brabham 🇬🇧 |
| 1973 | 15 | 1973 United States Grand Prix 🇺🇸 | 1973-10-07T00:00:00.000Z | 59 | 1:41:15.779 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | Team Lotus 🇬🇧 |
| 1972 | 12 | 1972 United States Grand Prix 🇺🇸 | 1972-10-08T00:00:00.000Z | 59 | 1:41:45.354 | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | Tyrrell 🇬🇧 |
| 1971 | 11 | 1971 United States Grand Prix 🇺🇸 | 1971-10-03T00:00:00.000Z | 59 | 1:43:51.991 | [François Cevert 🇫🇷](/f1/drivers/cevert) | Tyrrell 🇬🇧 |
| 1970 | 12 | 1970 United States Grand Prix 🇺🇸 | 1970-10-04T00:00:00.000Z | 108 | 1:57:32.79 | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | Team Lotus 🇬🇧 |
| 1969 | 10 | 1969 United States Grand Prix 🇺🇸 | 1969-10-05T00:00:00.000Z | 108 | 1:57:56.84 | [Jochen Rindt 🇦🇹](/f1/drivers/rindt) | Lotus-Ford 🇬🇧 |
| 1968 | 11 | 1968 United States Grand Prix 🇺🇸 | 1968-10-06T00:00:00.000Z | 108 | 1:59:20.29 | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | Matra-Ford 🇫🇷 |
| 1967 | 10 | 1967 United States Grand Prix 🇺🇸 | 1967-10-01T00:00:00.000Z | 108 | 2:03:13.2 | [Jim Clark 🇬🇧](/f1/drivers/clark) | Lotus-Ford 🇬🇧 |
| 1966 | 8 | 1966 United States Grand Prix 🇺🇸 | 1966-10-02T00:00:00.000Z | 108 | 2:09:40.11 | [Jim Clark 🇬🇧](/f1/drivers/clark) | Lotus-BRM 🇬🇧 |
| 1965 | 9 | 1965 United States Grand Prix 🇺🇸 | 1965-10-03T00:00:00.000Z | 110 | 2:20:36.1 | [Graham Hill 🇬🇧](/f1/drivers/hill) | BRM 🇬🇧 |
| 1964 | 9 | 1964 United States Grand Prix 🇺🇸 | 1964-10-04T00:00:00.000Z | 110 | 2:16:38.0 | [Graham Hill 🇬🇧](/f1/drivers/hill) | BRM 🇬🇧 |
| 1963 | 8 | 1963 United States Grand Prix 🇺🇸 | 1963-10-06T00:00:00.000Z | 110 | 2:19:22.1 | [Graham Hill 🇬🇧](/f1/drivers/hill) | BRM 🇬🇧 |
| 1962 | 8 | 1962 United States Grand Prix 🇺🇸 | 1962-10-07T00:00:00.000Z | 100 | 2:07:13.0 | [Jim Clark 🇬🇧](/f1/drivers/clark) | Lotus-Climax 🇬🇧 |
| 1961 | 8 | 1961 United States Grand Prix 🇺🇸 | 1961-10-08T00:00:00.000Z | 100 | 2:13:45.8 | [Innes Ireland 🇬🇧](/f1/drivers/ireland) | Lotus-Climax 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 20 |  | 20 | 20 |  |  |  |
| **Total Sum** | 234.000 |  | 794448000.000 | 1660.000 |  |  |  |
| **Mean μ (Average)** | 11.700 |  | 39722400.000 | 83.000 |  |  |  |
| **Maximum** | 15.000 |  | 339552000.000 | 110.000 |  |  |  |
| **75th Percentile** | 15.000 |  | 213753600.000 | 108.000 |  |  |  |
| **Median** | 12.000 |  | 55296000.000 | 100.000 |  |  |  |
| **25th Percentile** | 9.000 |  | -102556800.000 | 59.000 |  |  |  |
| **Minimum** | 8.000 |  | -259804800.000 | 59.000 |  |  |  |
| **Variance** | 7.610 |  | 33112651436928000.000 | 582.500 |  |  |  |
| **Standard Deviation σ** | 2.759 |  | 181968819.958 | 24.135 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
