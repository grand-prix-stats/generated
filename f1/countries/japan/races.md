---
title: List of All Formula 1® Races in Japan by Year
layout: page
collectionName: countries
collectionId: japan
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

| Season | Round | Name | Circuit | Date | Laps Completed | Race Duration | Winning Driver | Winning Constructor |
|--|--|--|--|--|--|--|--|--|
| 2017 | 16 | 2017 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2017-10-08T00:00:00.000Z |   |   |   |   |
| 2016 | 17 | 2016 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2016-10-09T00:00:00.000Z | 53 | 1:26:43.333 | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | Mercedes 🇩🇪 |
| 2015 | 14 | 2015 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2015-09-27T00:00:00.000Z | 53 |   | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | Mercedes 🇩🇪 |
| 2014 | 15 | 2014 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2014-10-05T00:00:00.000Z | 44 | 1:51:43.021 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | Mercedes 🇩🇪 |
| 2013 | 15 | 2013 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2013-10-13T00:00:00.000Z | 53 | 1:26:49.301 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2012 | 15 | 2012 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2012-10-07T00:00:00.000Z | 53 | 1:28:56.242 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2011 | 15 | 2011 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2011-10-09T00:00:00.000Z | 53 | 1:30:53.427 | [Jenson Button 🇬🇧](/f1/drivers/button) | McLaren 🇬🇧 |
| 2010 | 16 | 2010 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2010-10-10T00:00:00.000Z | 53 | 1:30:27.323 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2009 | 15 | 2009 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2009-10-04T00:00:00.000Z | 53 | 1:28:20.443 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2008 | 16 | 2008 Japanese Grand Prix 🇯🇵 | [Fuji Speedway](/f1/circuits/fuji) | 2008-10-12T00:00:00.000Z | 67 | 1:30:21.892 | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | Renault 🇫🇷 |
| 2007 | 15 | 2007 Japanese Grand Prix 🇯🇵 | [Fuji Speedway](/f1/circuits/fuji) | 2007-09-30T00:00:00.000Z | 67 | 2:00:34.579 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | McLaren 🇬🇧 |
| 2006 | 17 | 2006 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2006-10-08T00:00:00.000Z | 53 | 1:23:52.413 | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | Renault 🇫🇷 |
| 2005 | 18 | 2005 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2005-10-09T00:00:00.000Z | 53 | 1:29:02.212 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | McLaren 🇬🇧 |
| 2004 | 17 | 2004 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2004-10-10T00:00:00.000Z | 53 | 1:24:26.985 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2003 | 16 | 2003 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2003-10-12T00:00:00.000Z | 53 | 1:25:11.743 | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | Ferrari 🇮🇹 |
| 2002 | 17 | 2002 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2002-10-13T00:00:00.000Z | 53 | 1:26:59.698 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2001 | 17 | 2001 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2001-10-14T00:00:00.000Z | 53 | 1:27:33.298 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2000 | 16 | 2000 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 2000-10-08T00:00:00.000Z | 53 | 1:29:53.435 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 1999 | 16 | 1999 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1999-10-31T00:00:00.000Z | 53 | 1:31:18.785 | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | McLaren 🇬🇧 |
| 1998 | 16 | 1998 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1998-11-01T00:00:00.000Z | 51 | 1:27:23.4 | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | McLaren 🇬🇧 |
| 1997 | 16 | 1997 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1997-10-12T00:00:00.000Z | 53 | 1:29:48.446 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 1996 | 16 | 1996 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1996-10-13T00:00:00.000Z | 52 | 1:32:33.791 | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | Williams 🇬🇧 |
| 1995 | 15 | 1995 Pacific Grand Prix 🇯🇵 | [Okayama International Circuit](/f1/circuits/okayama) | 1995-10-22T00:00:00.000Z | 83 | 1:48:49.972 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Benetton 🇮🇹 |
| 1995 | 16 | 1995 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1995-10-29T00:00:00.000Z | 53 | 1:36:52.930 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Benetton 🇮🇹 |
| 1994 | 2 | 1994 Pacific Grand Prix 🇯🇵 | [Okayama International Circuit](/f1/circuits/okayama) | 1994-04-17T00:00:00.000Z | 83 | 1:46:01.693 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Benetton 🇮🇹 |
| 1994 | 15 | 1994 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1994-11-06T00:00:00.000Z | 50 | 1:55:53.532 | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | Williams 🇬🇧 |
| 1993 | 15 | 1993 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1993-10-24T00:00:00.000Z | 53 | 1:40:27.912 | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | McLaren 🇬🇧 |
| 1992 | 15 | 1992 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1992-10-25T00:00:00.000Z | 53 | 1:33:09.533 | [Riccardo Patrese 🇮🇹](/f1/drivers/patrese) | Williams 🇬🇧 |
| 1991 | 15 | 1991 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1991-10-20T00:00:00.000Z | 53 | 1:32:10.695 | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | McLaren 🇬🇧 |
| 1990 | 15 | 1990 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1990-10-21T00:00:00.000Z | 53 | 1:34:36.824 | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | Benetton 🇮🇹 |
| 1989 | 15 | 1989 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1989-10-22T00:00:00.000Z | 53 | 1:35:06.277 | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | Benetton 🇮🇹 |
| 1988 | 15 | 1988 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1988-10-30T00:00:00.000Z | 51 | 1:33:26.173 | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | McLaren 🇬🇧 |
| 1987 | 15 | 1987 Japanese Grand Prix 🇯🇵 | [Suzuka Circuit](/f1/circuits/suzuka) | 1987-11-01T00:00:00.000Z | 51 | 1:32:58.072 | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | Ferrari 🇮🇹 |
| 1977 | 17 | 1977 Japanese Grand Prix 🇯🇵 | [Fuji Speedway](/f1/circuits/fuji) | 1977-10-23T00:00:00.000Z | 73 | 1:31:51.68 | [James Hunt 🇬🇧](/f1/drivers/hunt) | McLaren 🇬🇧 |
| 1976 | 16 | 1976 Japanese Grand Prix 🇯🇵 | [Fuji Speedway](/f1/circuits/fuji) | 1976-10-24T00:00:00.000Z | 73 | 1:43:58.86 | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | Team Lotus 🇬🇧 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Circuit** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 35 |  |  | 35 | 34 |  |  |  |
| **Total Sum** | 537.000 |  |  | 34117372800.000 | 1911.000 |  |  |  |
| **Mean μ (Average)** | 15.343 |  |  | 974782080.000 | 56.206 |  |  |  |
| **Maximum** | 18.000 |  |  | 1507420800.000 | 83.000 |  |  |  |
| **75th Percentile** | 16.000 |  |  | 1254614400.000 | 53.000 |  |  |  |
| **Median** | 16.000 |  |  | 970963200.000 | 53.000 |  |  |  |
| **25th Percentile** | 15.000 |  |  | 751420800.000 | 53.000 |  |  |  |
| **Minimum** | 2.000 |  |  | 214963200.000 | 44.000 |  |  |  |
| **Variance** | 5.997 |  |  | 107032334907801600.000 | 80.752 |  |  |  |
| **Standard Deviation σ** | 2.449 |  |  | 327157966.291 | 8.986 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
