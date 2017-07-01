---
title: List of Formula 1® Races by Brian Henton
layout: page
collectionName: drivers
collectionId: henton
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
| 1982 | 16 | 1982 Caesars Palace Grand Prix 🇺🇸 | 1982-09-25T00:00:00.000Z | 19 | 8 | 0.0 | 74 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 3 | 1 |
| 1982 | 15 | 1982 Italian Grand Prix 🇮🇹 | 1982-09-12T00:00:00.000Z | 20 | R | 0.0 | 0 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 11 | 5 |
| 1982 | 14 | 1982 Swiss Grand Prix 🇫🇷 | 1982-08-29T00:00:00.000Z | 18 | 11 | 0.0 | 78 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 12 | 7 |
| 1982 | 13 | 1982 Austrian Grand Prix 🇦🇹 | 1982-08-15T00:00:00.000Z | 19 | R | 0.0 | 32 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 8 | R |
| 1982 | 12 | 1982 German Grand Prix 🇩🇪 | 1982-08-08T00:00:00.000Z | 17 | 7 | 0.0 | 44 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 7 | 4 |
| 1982 | 11 | 1982 French Grand Prix 🇫🇷 | 1982-07-25T00:00:00.000Z | 23 | 10 | 0.0 | 53 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 15 | 6 |
| 1982 | 10 | 1982 British Grand Prix 🇬🇧 | 1982-07-18T00:00:00.000Z | 17 | 8 | 0.0 | 75 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 9 | R |
| 1982 | 9 | 1982 Dutch Grand Prix 🇳🇱 | 1982-07-03T00:00:00.000Z | 20 | R | 0.0 | 21 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 14 | 7 |
| 1982 | 8 | 1982 Canadian Grand Prix 🇨🇦 | 1982-06-13T00:00:00.000Z | 26 | N | 0.0 | 59 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 15 | R |
| 1982 | 7 | 1982 Detroit Grand Prix 🇺🇸 | 1982-06-06T00:00:00.000Z | 20 | 9 | 0.0 | 60 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 16 | R |
| 1982 | 6 | 1982 Monaco Grand Prix 🇲🇨 | 1982-05-23T00:00:00.000Z | 17 | 8 | 0.0 | 72 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 9 | 10 |
| 1982 | 5 | 1982 Belgian Grand Prix 🇧🇪 | 1982-05-09T00:00:00.000Z | 20 | R | 0.0 | 33 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 5 | R |
| 1982 | 4 | 1982 San Marino Grand Prix 🇮🇹 | 1982-04-25T00:00:00.000Z | 11 | R | 0.0 | 0 |   | Tyrrell 🇬🇧 | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 5 | 3 |
| 1982 | 3 | 1982 United States Grand Prix West 🇺🇸 | 1982-04-04T00:00:00.000Z | 20 | R | 0.0 | 32 |   | Arrows 🇬🇧 | [Mauro Baldi 🇮🇹](/f1/drivers/baldi) | 0 | F |
| 1982 | 2 | 1982 Brazilian Grand Prix 🇧🇷 | 1982-03-21T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Arrows 🇬🇧 | [Mauro Baldi 🇮🇹](/f1/drivers/baldi) | 19 | 10 |
| 1982 | 1 | 1982 South African Grand Prix 🇿🇦 | 1982-01-23T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Arrows 🇬🇧 | [Mauro Baldi 🇮🇹](/f1/drivers/baldi) | 0 | F |
| 1981 | 15 | 1981 Caesars Palace Grand Prix 🇺🇸 | 1981-10-17T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 22 | R |
| 1981 | 14 | 1981 Canadian Grand Prix 🇨🇦 | 1981-09-27T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 13 | 1981 Italian Grand Prix 🇮🇹 | 1981-09-13T00:00:00.000Z | 23 | 10 | 0.0 | 49 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 12 | 1981 Dutch Grand Prix 🇳🇱 | 1981-08-30T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 11 | 1981 Austrian Grand Prix 🇦🇹 | 1981-08-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 10 | 1981 German Grand Prix 🇩🇪 | 1981-08-02T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 9 | 1981 British Grand Prix 🇬🇧 | 1981-07-18T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 8 | 1981 French Grand Prix 🇫🇷 | 1981-07-05T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 7 | 1981 Spanish Grand Prix 🇪🇸 | 1981-06-21T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 6 | 1981 Monaco Grand Prix 🇲🇨 | 1981-05-31T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 5 | 1981 Belgian Grand Prix 🇧🇪 | 1981-05-17T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1981 | 4 | 1981 San Marino Grand Prix 🇮🇹 | 1981-05-03T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Toleman 🇬🇧 | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 0 | F |
| 1977 | 12 | 1977 Austrian Grand Prix 🇦🇹 | 1977-08-14T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Patrick Nève 🇧🇪](/f1/drivers/neve) | 22 | 9 |
| 1977 | 12 | 1977 Austrian Grand Prix 🇦🇹 | 1977-08-14T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Ian Scheckter 🇿🇦](/f1/drivers/ian_scheckter) | 24 | R |
| 1977 | 12 | 1977 Austrian Grand Prix 🇦🇹 | 1977-08-14T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Alex Ribeiro 🇧🇷](/f1/drivers/ribeiro) | 0 | F |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Patrick Nève 🇧🇪](/f1/drivers/neve) | 26 | 10 |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Arturo Merzario 🇮🇹](/f1/drivers/merzario) | 17 | R |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Ian Scheckter 🇿🇦](/f1/drivers/ian_scheckter) | 24 | R |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Alex Ribeiro 🇧🇷](/f1/drivers/ribeiro) | 0 | F |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Andy Sutcliffe 🇬🇧](/f1/drivers/sutcliffe) | 0 | F |
| 1977 | 10 | 1977 British Grand Prix 🇬🇧 | 1977-07-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Mikko Kozarowitzky 🇫🇮](/f1/drivers/kozarowitzky) | 0 | F |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Brett Lunger 🇺🇸](/f1/drivers/lunger) | 28 | 10 |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Ian Scheckter 🇿🇦](/f1/drivers/ian_scheckter) | 17 | 11 |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Patrick Nève 🇧🇪](/f1/drivers/neve) | 22 | 12 |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Arturo Merzario 🇮🇹](/f1/drivers/merzario) | 21 | R |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Alex Ribeiro 🇧🇷](/f1/drivers/ribeiro) | 0 | F |
| 1977 | 5 | 1977 Spanish Grand Prix 🇪🇸 | 1977-05-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | March 🇬🇧 | [Boy Lunger 🇳🇱](/f1/drivers/hayje) | 0 | F |
| 1977 | 4 | 1977 United States Grand Prix West 🇺🇸 | 1977-04-03T00:00:00.000Z | 18 | 10 | 0.0 | 77 |   | March 🇬🇧 | [Alex Ribeiro 🇧🇷](/f1/drivers/ribeiro) | 22 | R |
| 1977 | 4 | 1977 United States Grand Prix West 🇺🇸 | 1977-04-03T00:00:00.000Z | 18 | 10 | 0.0 | 77 |   | March 🇬🇧 | [Brett Lunger 🇺🇸](/f1/drivers/lunger) | 21 | R |
| 1975 | 14 | 1975 United States Grand Prix 🇺🇸 | 1975-10-05T00:00:00.000Z | 19 | N | 0.0 | 49 |   | Team Lotus 🇬🇧 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 14 | 5 |
| 1975 | 12 | 1975 Austrian Grand Prix 🇦🇹 | 1975-08-17T00:00:00.000Z | 22 | W | 0.0 | 0 |   | Team Lotus 🇬🇧 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 13 | 5 |
| 1975 | 10 | 1975 British Grand Prix 🇬🇧 | 1975-07-19T00:00:00.000Z | 21 | 16 | 0.0 | 53 |   | Team Lotus 🇬🇧 | [Jim Crawford 🇬🇧](/f1/drivers/crawford) | 25 | R |
| 1975 | 10 | 1975 British Grand Prix 🇬🇧 | 1975-07-19T00:00:00.000Z | 21 | 16 | 0.0 | 53 |   | Team Lotus 🇬🇧 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 16 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 49 |  | 49 | 49 | 12 | 49 | 49 |  |  |  | 49 | 16 |
| **Total Sum** | 430.000 |  | 15375916800.000 | 409.000 | 123.000 |  | 991.000 |  |  |  | 482.000 | 115.000 |
| **Mean μ (Average)** | 8.776 |  | 313794220.408 | 8.347 | 10.250 |  | 20.224 |  |  |  | 9.837 | 7.188 |
| **Maximum** | 16.000 |  | 401760000.000 | 26.000 | 16.000 |  | 78.000 |  |  |  | 28.000 | 12.000 |
| **75th Percentile** | 12.000 |  | 388540800.000 | 19.000 | 11.000 |  | 49.000 |  |  |  | 17.000 | 10.000 |
| **Median** | 10.000 |  | 361929600.000 |  | 10.000 |  |  |  |  |  | 9.000 | 7.000 |
| **25th Percentile** | 5.000 |  | 237859200.000 |  | 8.000 |  |  |  |  |  |  | 5.000 |
| **Minimum** | 1.000 |  | 174960000.000 |  | 7.000 |  |  |  |  |  |  | 1.000 |
| **Variance** | 14.337 |  | 6387151900506522.000 | 96.512 | 7.854 |  | 816.501 |  |  |  | 89.279 | 9.652 |
| **Standard Deviation σ** | 3.786 |  | 79919659.036 | 9.824 | 2.803 |  | 28.574 |  |  |  | 9.449 | 3.107 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
