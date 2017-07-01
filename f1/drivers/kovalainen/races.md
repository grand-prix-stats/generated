---
title: List of Formula 1® Races by Heikki Kovalainen
layout: page
collectionName: drivers
collectionId: kovalainen
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
| 2013 | 19 | 2013 Brazilian Grand Prix 🇧🇷 | 2013-11-24T00:00:00.000Z | 11 | 14 | 0.0 | 70 |   | Lotus F1 🇬🇧 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 6 | R |
| 2013 | 18 | 2013 United States Grand Prix 🇺🇸 | 2013-11-17T00:00:00.000Z | 8 | 15 | 0.0 | 56 | +1:35.063 | Lotus F1 🇬🇧 | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 3 | 2 |
| 2012 | 20 | 2012 Brazilian Grand Prix 🇧🇷 | 2012-11-25T00:00:00.000Z | 20 | 14 | 0.0 | 70 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | 11 |
| 2012 | 19 | 2012 United States Grand Prix 🇺🇸 | 2012-11-18T00:00:00.000Z | 22 | 18 | 0.0 | 55 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 21 | 17 |
| 2012 | 18 | 2012 Abu Dhabi Grand Prix 🇦🇪 | 2012-11-04T00:00:00.000Z | 18 | 13 | 0.0 | 55 | +47.764 | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 20 | 16 |
| 2012 | 17 | 2012 Indian Grand Prix 🇮🇳 | 2012-10-28T00:00:00.000Z | 20 | 18 | 0.0 | 59 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | 17 |
| 2012 | 16 | 2012 Korean Grand Prix 🇰🇷 | 2012-10-14T00:00:00.000Z | 19 | 17 | 0.0 | 54 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 16 |
| 2012 | 15 | 2012 Japanese Grand Prix 🇯🇵 | 2012-10-07T00:00:00.000Z | 17 | 15 | 0.0 | 52 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 22 | 17 |
| 2012 | 14 | 2012 Singapore Grand Prix 🇸🇬 | 2012-09-23T00:00:00.000Z | 19 | 15 | 0.0 | 59 | +107.967 | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 19 |
| 2012 | 13 | 2012 Italian Grand Prix 🇮🇹 | 2012-09-09T00:00:00.000Z | 17 | 14 | 0.0 | 52 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 15 |
| 2012 | 12 | 2012 Belgian Grand Prix 🇧🇪 | 2012-09-02T00:00:00.000Z | 18 | 17 | 0.0 | 43 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | 14 |
| 2012 | 11 | 2012 Hungarian Grand Prix 🇭🇺 | 2012-07-29T00:00:00.000Z | 19 | 17 | 0.0 | 68 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 20 | 19 |
| 2012 | 10 | 2012 German Grand Prix 🇩🇪 | 2012-07-22T00:00:00.000Z | 16 | 19 | 0.0 | 65 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 16 |
| 2012 | 9 | 2012 British Grand Prix 🇬🇧 | 2012-07-08T00:00:00.000Z | 19 | 17 | 0.0 | 51 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | W |
| 2012 | 8 | 2012 European Grand Prix 🇪🇸 | 2012-06-24T00:00:00.000Z | 16 | 14 | 0.0 | 57 | +1:34.654 | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 20 | 13 |
| 2012 | 7 | 2012 Canadian Grand Prix 🇨🇦 | 2012-06-10T00:00:00.000Z | 17 | 18 | 0.0 | 69 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 19 |
| 2012 | 6 | 2012 Monaco Grand Prix 🇲🇨 | 2012-05-27T00:00:00.000Z | 17 | 13 | 0.0 | 77 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | R |
| 2012 | 5 | 2012 Spanish Grand Prix 🇪🇸 | 2012-05-13T00:00:00.000Z | 19 | 16 | 0.0 | 65 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 17 |
| 2012 | 4 | 2012 Bahrain Grand Prix 🇧🇭 | 2012-04-22T00:00:00.000Z | 16 | 17 | 0.0 | 56 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 18 | 16 |
| 2012 | 3 | 2012 Chinese Grand Prix 🇨🇳 | 2012-04-15T00:00:00.000Z | 18 | 23 | 0.0 | 53 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | 18 |
| 2012 | 2 | 2012 Malaysian Grand Prix 🇲🇾 | 2012-03-25T00:00:00.000Z | 24 | 18 | 0.0 | 55 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | 16 |
| 2012 | 1 | 2012 Australian Grand Prix 🇦🇺 | 2012-03-18T00:00:00.000Z | 18 | R | 0.0 | 38 |   | Caterham 🇲🇾 | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 19 | R |
| 2011 | 19 | 2011 Brazilian Grand Prix 🇧🇷 | 2011-11-27T00:00:00.000Z | 19 | 16 | 0.0 | 69 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 18 |
| 2011 | 18 | 2011 Abu Dhabi Grand Prix 🇦🇪 | 2011-11-13T00:00:00.000Z | 17 | 17 | 0.0 | 54 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 18 |
| 2011 | 17 | 2011 Indian Grand Prix 🇮🇳 | 2011-10-30T00:00:00.000Z | 18 | 14 | 0.0 | 58 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 19 |
| 2011 | 16 | 2011 Korean Grand Prix 🇰🇷 | 2011-10-16T00:00:00.000Z | 19 | 14 | 0.0 | 54 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 17 |
| 2011 | 15 | 2011 Japanese Grand Prix 🇯🇵 | 2011-10-09T00:00:00.000Z | 18 | 18 | 0.0 | 53 | +1:27.824 | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 19 |
| 2011 | 14 | 2011 Singapore Grand Prix 🇸🇬 | 2011-09-25T00:00:00.000Z | 19 | 16 | 0.0 | 59 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | R |
| 2011 | 13 | 2011 Italian Grand Prix 🇮🇹 | 2011-09-11T00:00:00.000Z | 20 | 13 | 0.0 | 51 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 14 |
| 2011 | 12 | 2011 Belgian Grand Prix 🇧🇪 | 2011-08-28T00:00:00.000Z | 16 | 15 | 0.0 | 43 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 14 |
| 2011 | 11 | 2011 Hungarian Grand Prix 🇭🇺 | 2011-07-31T00:00:00.000Z | 18 | R | 0.0 | 55 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | R |
| 2011 | 10 | 2011 German Grand Prix 🇩🇪 | 2011-07-24T00:00:00.000Z | 18 | 16 | 0.0 | 58 |   | Lotus 🇲🇾 | [Karun Chandhok 🇮🇳](/f1/drivers/chandhok) | 20 | 20 |
| 2011 | 9 | 2011 British Grand Prix 🇬🇧 | 2011-07-10T00:00:00.000Z | 17 | R | 0.0 | 2 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 21 | R |
| 2011 | 8 | 2011 European Grand Prix 🇪🇸 | 2011-06-26T00:00:00.000Z | 19 | 19 | 0.0 | 55 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 20 |
| 2011 | 7 | 2011 Canadian Grand Prix 🇨🇦 | 2011-06-12T00:00:00.000Z | 19 | R | 0.0 | 28 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 17 |
| 2011 | 6 | 2011 Monaco Grand Prix 🇲🇨 | 2011-05-29T00:00:00.000Z | 17 | 14 | 0.0 | 76 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 13 |
| 2011 | 5 | 2011 Spanish Grand Prix 🇪🇸 | 2011-05-22T00:00:00.000Z | 15 | R | 0.0 | 48 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 18 |
| 2011 | 4 | 2011 Turkish Grand Prix 🇹🇷 | 2011-05-08T00:00:00.000Z | 18 | 19 | 0.0 | 56 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 18 |
| 2011 | 3 | 2011 Chinese Grand Prix 🇨🇳 | 2011-04-17T00:00:00.000Z | 19 | 16 | 0.0 | 55 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 19 |
| 2011 | 2 | 2011 Malaysian Grand Prix 🇲🇾 | 2011-04-10T00:00:00.000Z | 19 | 15 | 0.0 | 55 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | R |
| 2011 | 1 | 2011 Australian Grand Prix 🇦🇺 | 2011-03-27T00:00:00.000Z | 19 | R | 0.0 | 19 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 13 |
| 2010 | 19 | 2010 Abu Dhabi Grand Prix 🇦🇪 | 2010-11-14T00:00:00.000Z | 20 | 17 | 0.0 | 54 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 21 |
| 2010 | 18 | 2010 Brazilian Grand Prix 🇧🇷 | 2010-11-07T00:00:00.000Z | 20 | 18 | 0.0 | 69 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 19 |
| 2010 | 17 | 2010 Korean Grand Prix 🇰🇷 | 2010-10-24T00:00:00.000Z | 21 | 13 | 0.0 | 54 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | R |
| 2010 | 16 | 2010 Japanese Grand Prix 🇯🇵 | 2010-10-10T00:00:00.000Z | 20 | 12 | 0.0 | 52 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 13 |
| 2010 | 15 | 2010 Singapore Grand Prix 🇸🇬 | 2010-09-26T00:00:00.000Z | 19 | 16 | 0.0 | 58 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 21 | R |
| 2010 | 14 | 2010 Italian Grand Prix 🇮🇹 | 2010-09-12T00:00:00.000Z | 18 | 18 | 0.0 | 51 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 17 | R |
| 2010 | 13 | 2010 Belgian Grand Prix 🇧🇪 | 2010-08-29T00:00:00.000Z | 13 | 16 | 0.0 | 43 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 15 | 19 |
| 2010 | 12 | 2010 Hungarian Grand Prix 🇭🇺 | 2010-08-01T00:00:00.000Z | 19 | 14 | 0.0 | 67 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 15 |
| 2010 | 11 | 2010 German Grand Prix 🇩🇪 | 2010-07-25T00:00:00.000Z | 18 | R | 0.0 | 56 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 17 | R |
| 2010 | 10 | 2010 British Grand Prix 🇬🇧 | 2010-07-11T00:00:00.000Z | 18 | 17 | 0.0 | 51 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 21 | 16 |
| 2010 | 9 | 2010 European Grand Prix 🇪🇸 | 2010-06-27T00:00:00.000Z | 20 | R | 0.0 | 8 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 21 |
| 2010 | 8 | 2010 Canadian Grand Prix 🇨🇦 | 2010-06-13T00:00:00.000Z | 19 | 16 | 0.0 | 68 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | R |
| 2010 | 7 | 2010 Turkish Grand Prix 🇹🇷 | 2010-05-30T00:00:00.000Z | 20 | R | 0.0 | 33 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | R |
| 2010 | 6 | 2010 Monaco Grand Prix 🇲🇨 | 2010-05-16T00:00:00.000Z | 18 | R | 0.0 | 58 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 19 | 15 |
| 2010 | 5 | 2010 Spanish Grand Prix 🇪🇸 | 2010-05-09T00:00:00.000Z | 20 | W | 0.0 | 0 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 17 |
| 2010 | 4 | 2010 Chinese Grand Prix 🇨🇳 | 2010-04-18T00:00:00.000Z | 21 | 14 | 0.0 | 55 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | R |
| 2010 | 3 | 2010 Malaysian Grand Prix 🇲🇾 | 2010-04-04T00:00:00.000Z | 15 | N | 0.0 | 46 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 18 | 17 |
| 2010 | 2 | 2010 Australian Grand Prix 🇦🇺 | 2010-03-28T00:00:00.000Z | 19 | 13 | 0.0 | 56 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | W |
| 2010 | 1 | 2010 Bahrain Grand Prix 🇧🇭 | 2010-03-14T00:00:00.000Z | 21 | 15 | 0.0 | 47 |   | Lotus 🇲🇾 | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 20 | 17 |
| 2009 | 17 | 2009 Abu Dhabi Grand Prix 🇦🇪 | 2009-11-01T00:00:00.000Z | 18 | 11 | 0.0 | 55 | +52.798 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | R |
| 2009 | 16 | 2009 Brazilian Grand Prix 🇧🇷 | 2009-10-18T00:00:00.000Z | 16 | 9 | 0.0 | 71 | +48.499 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 17 | 3 |
| 2009 | 15 | 2009 Japanese Grand Prix 🇯🇵 | 2009-10-04T00:00:00.000Z | 11 | 11 | 0.0 | 53 | +13.735 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 | 3 |
| 2009 | 14 | 2009 Singapore Grand Prix 🇸🇬 | 2009-09-27T00:00:00.000Z | 8 | 7 | 2.0 | 61 | +36.157 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 1 |
| 2009 | 13 | 2009 Italian Grand Prix 🇮🇹 | 2009-09-13T00:00:00.000Z | 4 | 6 | 3.0 | 53 | +1:00.693 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 12 |
| 2009 | 12 | 2009 Belgian Grand Prix 🇧🇪 | 2009-08-30T00:00:00.000Z | 15 | 6 | 3.0 | 44 | +32.763 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 12 | R |
| 2009 | 11 | 2009 European Grand Prix 🇪🇸 | 2009-08-23T00:00:00.000Z | 2 | 4 | 5.0 | 57 | +20.032 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 2 |
| 2009 | 10 | 2009 Hungarian Grand Prix 🇭🇺 | 2009-07-26T00:00:00.000Z | 6 | 5 | 4.0 | 70 | +34.392 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 | 1 |
| 2009 | 9 | 2009 German Grand Prix 🇩🇪 | 2009-07-12T00:00:00.000Z | 6 | 8 | 1.0 | 60 | +58.692 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 5 | 18 |
| 2009 | 8 | 2009 British Grand Prix 🇬🇧 | 2009-06-21T00:00:00.000Z | 13 | R | 0.0 | 36 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 18 | 16 |
| 2009 | 7 | 2009 Turkish Grand Prix 🇹🇷 | 2009-06-07T00:00:00.000Z | 14 | 14 | 0.0 | 57 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 16 | 13 |
| 2009 | 6 | 2009 Monaco Grand Prix 🇲🇨 | 2009-05-24T00:00:00.000Z | 7 | R | 0.0 | 51 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 19 | 12 |
| 2009 | 5 | 2009 Spanish Grand Prix 🇪🇸 | 2009-05-10T00:00:00.000Z | 18 | R | 0.0 | 7 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 14 | 9 |
| 2009 | 4 | 2009 Bahrain Grand Prix 🇧🇭 | 2009-04-26T00:00:00.000Z | 11 | 12 | 0.0 | 57 | +1:17.824 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 5 | 4 |
| 2009 | 3 | 2009 Chinese Grand Prix 🇨🇳 | 2009-04-19T00:00:00.000Z | 12 | 5 | 4.0 | 56 | +1:05.102 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 9 | 6 |
| 2009 | 2 | 2009 Malaysian Grand Prix 🇲🇾 | 2009-04-05T00:00:00.000Z | 14 | R | 0.0 | 0 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 12 | 7 |
| 2009 | 1 | 2009 Australian Grand Prix 🇦🇺 | 2009-03-29T00:00:00.000Z | 12 | R | 0.0 | 0 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 18 | D |
| 2008 | 18 | 2008 Brazilian Grand Prix 🇧🇷 | 2008-11-02T00:00:00.000Z | 5 | 7 | 2.0 | 71 | +55.074 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 | 5 |
| 2008 | 17 | 2008 Chinese Grand Prix 🇨🇳 | 2008-10-19T00:00:00.000Z | 5 | R | 0.0 | 49 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 1 |
| 2008 | 16 | 2008 Japanese Grand Prix 🇯🇵 | 2008-10-12T00:00:00.000Z | 3 | R | 0.0 | 16 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 12 |
| 2008 | 15 | 2008 Singapore Grand Prix 🇸🇬 | 2008-09-28T00:00:00.000Z | 5 | 10 | 0.0 | 61 | +26.902 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2 | 3 |
| 2008 | 14 | 2008 Italian Grand Prix 🇮🇹 | 2008-09-14T00:00:00.000Z | 2 | 2 | 8.0 | 53 | +12.512 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 15 | 7 |
| 2008 | 13 | 2008 Belgian Grand Prix 🇧🇪 | 2008-09-07T00:00:00.000Z | 3 | 10 | 0.0 | 43 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 3 |
| 2008 | 12 | 2008 European Grand Prix 🇪🇸 | 2008-08-24T00:00:00.000Z | 5 | 4 | 5.0 | 57 | +39.703 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2 | 2 |
| 2008 | 11 | 2008 Hungarian Grand Prix 🇭🇺 | 2008-08-03T00:00:00.000Z | 2 | 1 | 10.0 | 70 | 1:37:27.067 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 5 |
| 2008 | 10 | 2008 German Grand Prix 🇩🇪 | 2008-07-20T00:00:00.000Z | 3 | 5 | 4.0 | 67 | +12.411 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 1 |
| 2008 | 9 | 2008 British Grand Prix 🇬🇧 | 2008-07-06T00:00:00.000Z | 1 | 5 | 4.0 | 59 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 | 1 |
| 2008 | 8 | 2008 French Grand Prix 🇫🇷 | 2008-06-22T00:00:00.000Z | 10 | 4 | 5.0 | 70 | +28.929 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 13 | 10 |
| 2008 | 7 | 2008 Canadian Grand Prix 🇨🇦 | 2008-06-08T00:00:00.000Z | 7 | 9 | 0.0 | 70 | +54.433 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | R |
| 2008 | 6 | 2008 Monaco Grand Prix 🇲🇨 | 2008-05-25T00:00:00.000Z | 4 | 8 | 1.0 | 76 | +33.191 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 | 1 |
| 2008 | 5 | 2008 Turkish Grand Prix 🇹🇷 | 2008-05-11T00:00:00.000Z | 2 | 12 | 0.0 | 57 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 | 2 |
| 2008 | 4 | 2008 Spanish Grand Prix 🇪🇸 | 2008-04-27T00:00:00.000Z | 6 | R | 0.0 | 21 |   | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 5 | 3 |
| 2008 | 3 | 2008 Bahrain Grand Prix 🇧🇭 | 2008-04-06T00:00:00.000Z | 5 | 5 | 4.0 | 57 | +26.789 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 | 13 |
| 2008 | 2 | 2008 Malaysian Grand Prix 🇲🇾 | 2008-03-23T00:00:00.000Z | 8 | 3 | 6.0 | 56 | +38.450 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 9 | 5 |
| 2008 | 1 | 2008 Australian Grand Prix 🇦🇺 | 2008-03-16T00:00:00.000Z | 3 | 5 | 4.0 | 58 | +18.014 | McLaren 🇬🇧 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 1 | 1 |
| 2007 | 17 | 2007 Brazilian Grand Prix 🇧🇷 | 2007-10-21T00:00:00.000Z | 17 | R | 0.0 | 35 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 12 | R |
| 2007 | 16 | 2007 Chinese Grand Prix 🇨🇳 | 2007-10-07T00:00:00.000Z | 13 | 9 | 0.0 | 56 | +1:21.186 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 18 | 11 |
| 2007 | 15 | 2007 Japanese Grand Prix 🇯🇵 | 2007-09-30T00:00:00.000Z | 11 | 2 | 8.0 | 67 | +8.377 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 10 | 5 |
| 2007 | 14 | 2007 Belgian Grand Prix 🇧🇪 | 2007-09-16T00:00:00.000Z | 9 | 8 | 1.0 | 44 | +1:25.106 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 22 | R |
| 2007 | 13 | 2007 Italian Grand Prix 🇮🇹 | 2007-09-09T00:00:00.000Z | 7 | 7 | 2.0 | 53 | +1:06.751 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 15 | 12 |
| 2007 | 12 | 2007 Turkish Grand Prix 🇹🇷 | 2007-08-26T00:00:00.000Z | 7 | 6 | 3.0 | 58 | +46.169 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 10 | 9 |
| 2007 | 11 | 2007 Hungarian Grand Prix 🇭🇺 | 2007-08-05T00:00:00.000Z | 11 | 8 | 1.0 | 70 | +1:08.104 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 13 | 12 |
| 2007 | 10 | 2007 European Grand Prix 🇩🇪 | 2007-07-22T00:00:00.000Z | 7 | 8 | 1.0 | 59 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 13 | 10 |
| 2007 | 9 | 2007 British Grand Prix 🇬🇧 | 2007-07-08T00:00:00.000Z | 7 | 7 | 2.0 | 58 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 8 | 8 |
| 2007 | 8 | 2007 French Grand Prix 🇫🇷 | 2007-07-01T00:00:00.000Z | 6 | 15 | 0.0 | 69 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 5 | 6 |
| 2007 | 7 | 2007 United States Grand Prix 🇺🇸 | 2007-06-17T00:00:00.000Z | 6 | 5 | 4.0 | 73 | +41.4 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 10 | 9 |
| 2007 | 6 | 2007 Canadian Grand Prix 🇨🇦 | 2007-06-10T00:00:00.000Z | 22 | 4 | 5.0 | 70 | +6.729 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 9 | D |
| 2007 | 5 | 2007 Monaco Grand Prix 🇲🇨 | 2007-05-27T00:00:00.000Z | 15 | 13 | 0.0 | 76 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 4 | 4 |
| 2007 | 4 | 2007 Spanish Grand Prix 🇪🇸 | 2007-05-13T00:00:00.000Z | 8 | 7 | 2.0 | 65 | +1:02.128 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 10 | 9 |
| 2007 | 3 | 2007 Bahrain Grand Prix 🇧🇭 | 2007-04-15T00:00:00.000Z | 12 | 9 | 0.0 | 57 | +1:29.411 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 7 | 8 |
| 2007 | 2 | 2007 Malaysian Grand Prix 🇲🇾 | 2007-04-08T00:00:00.000Z | 11 | 8 | 1.0 | 56 | +1:12.015 | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 12 | 6 |
| 2007 | 1 | 2007 Australian Grand Prix 🇦🇺 | 2007-03-18T00:00:00.000Z | 13 | 10 | 0.0 | 57 |   | Renault 🇫🇷 | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 6 | 5 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 112 |  | 112 | 112 | 91 | 112 | 112 | 25 |  |  | 112 | 89 |
| **Total Sum** | 1104.000 |  | 142085059200.000 | 1539.000 | 1077.000 | 105.000 | 5975.000 | 901.882 |  |  | 1522.000 | 1021.000 |
| **Mean μ (Average)** | 9.857 |  | 1268616600.000 | 13.741 | 11.835 | 0.938 | 53.348 | 36.075 |  |  | 13.589 | 11.472 |
| **Maximum** | 20.000 |  | 1385251200.000 | 24.000 | 23.000 | 10.000 | 77.000 | 107.967 |  |  | 22.000 | 21.000 |
| **75th Percentile** | 15.000 |  | 1316908800.000 | 19.000 | 16.000 | 1.000 | 61.000 | 47.764 |  |  | 19.000 | 17.000 |
| **Median** | 10.000 |  | 1273363200.000 | 16.000 | 13.000 |  | 56.000 | 34.392 |  |  | 18.000 | 13.000 |
| **25th Percentile** | 5.000 |  | 1219536000.000 | 8.000 | 7.000 |  | 51.000 | 20.032 |  |  | 7.000 | 5.000 |
| **Minimum** | 1.000 |  | 1174176000.000 | 1.000 | 1.000 |  |  | 6.729 |  |  | 1.000 | 1.000 |
| **Variance** | 29.390 |  | 3213921392280000.000 | 37.103 | 25.654 | 3.844 | 268.691 | 446.698 |  |  | 49.313 | 39.508 |
| **Standard Deviation σ** | 5.421 |  | 56691457.842 | 6.091 | 5.065 | 1.961 | 16.392 | 21.135 |  |  | 7.022 | 6.286 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
