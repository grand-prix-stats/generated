---
title: List of All Formula 1® Races in Austria by Year
layout: page
collectionName: countries
collectionId: austria
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
| 2017 | 9 | 2017 Austrian Grand Prix 🇦🇹 | [Red Bull Ring](/f1/circuits/red_bull_ring) | 2017-07-09T00:00:00.000Z |   |   |   |   |
| 2016 | 9 | 2016 Austrian Grand Prix 🇦🇹 | [Red Bull Ring](/f1/circuits/red_bull_ring) | 2016-07-03T00:00:00.000Z | 71 | 1:27:38.107 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | Mercedes 🇩🇪 |
| 2015 | 8 | 2015 Austrian Grand Prix 🇦🇹 | [Red Bull Ring](/f1/circuits/red_bull_ring) | 2015-06-21T00:00:00.000Z | 71 | 1:30:16.930 | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | Mercedes 🇩🇪 |
| 2014 | 8 | 2014 Austrian Grand Prix 🇦🇹 | [Red Bull Ring](/f1/circuits/red_bull_ring) | 2014-06-22T00:00:00.000Z | 71 | 1:27:54.976 | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | Mercedes 🇩🇪 |
| 2003 | 6 | 2003 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 2003-05-18T00:00:00.000Z | 69 | 1:24:04.888 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2002 | 6 | 2002 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 2002-05-12T00:00:00.000Z | 71 | 1:33:51.562 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2001 | 6 | 2001 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 2001-05-13T00:00:00.000Z | 71 | 1:27:45.927 | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | McLaren 🇬🇧 |
| 2000 | 10 | 2000 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 2000-07-16T00:00:00.000Z | 71 | 1:28:15.818 | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | McLaren 🇬🇧 |
| 1999 | 9 | 1999 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1999-07-25T00:00:00.000Z | 71 | 1:28:12.438 | [Eddie Irvine 🇬🇧](/f1/drivers/irvine) | Ferrari 🇮🇹 |
| 1998 | 10 | 1998 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1998-07-26T00:00:00.000Z | 71 | 1:30:44.0 | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | McLaren 🇬🇧 |
| 1997 | 14 | 1997 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1997-09-21T00:00:00.000Z | 71 | 1:27:35.999 | [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | Williams 🇬🇧 |
| 1987 | 10 | 1987 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1987-08-16T00:00:00.000Z | 52 | 1:18:44.898 | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | Williams 🇬🇧 |
| 1986 | 12 | 1986 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1986-08-17T00:00:00.000Z | 52 | 1:21:22.531 | [Alain Prost 🇫🇷](/f1/drivers/prost) | McLaren 🇬🇧 |
| 1985 | 10 | 1985 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1985-08-18T00:00:00.000Z | 52 | 1:20:12.583 | [Alain Prost 🇫🇷](/f1/drivers/prost) | McLaren 🇬🇧 |
| 1984 | 12 | 1984 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1984-08-19T00:00:00.000Z | 51 | 1:21:12.851 | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | McLaren 🇬🇧 |
| 1983 | 11 | 1983 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1983-08-14T00:00:00.000Z | 53 | 1:24:32.745 | [Alain Prost 🇫🇷](/f1/drivers/prost) | Renault 🇫🇷 |
| 1982 | 13 | 1982 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1982-08-15T00:00:00.000Z | 53 | 1:25:02.212 | [Elio de Angelis 🇮🇹](/f1/drivers/angelis) | Team Lotus 🇬🇧 |
| 1981 | 11 | 1981 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1981-08-16T00:00:00.000Z | 53 | 1:27:36.47 | [Jacques Laffite 🇫🇷](/f1/drivers/laffite) | Ligier 🇫🇷 |
| 1980 | 10 | 1980 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1980-08-17T00:00:00.000Z | 54 | 1:26:15.73 | [Jean-Pierre Jabouille 🇫🇷](/f1/drivers/jabouille) | Renault 🇫🇷 |
| 1979 | 11 | 1979 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1979-08-12T00:00:00.000Z | 54 | 1:27:38.01 | [Alan Jones 🇦🇺](/f1/drivers/jones) | Williams 🇬🇧 |
| 1978 | 12 | 1978 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1978-08-13T00:00:00.000Z | 54 | 1:41:21.57 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | Team Lotus 🇬🇧 |
| 1977 | 12 | 1977 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1977-08-14T00:00:00.000Z | 54 | 1:37:16.49 | [Alan Jones 🇦🇺](/f1/drivers/jones) | Shadow 🇬🇧 |
| 1976 | 11 | 1976 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1976-08-15T00:00:00.000Z | 54 | 1:30:07.86 | [John Watson 🇬🇧](/f1/drivers/watson) | Penske 🇺🇸 |
| 1975 | 12 | 1975 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1975-08-17T00:00:00.000Z | 29 | 0:57:56.69 | [Vittorio Brambilla 🇮🇹](/f1/drivers/brambilla) | March 🇬🇧 |
| 1974 | 12 | 1974 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1974-08-18T00:00:00.000Z | 54 | 1:28:44.72 | [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | Brabham 🇬🇧 |
| 1973 | 12 | 1973 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1973-08-19T00:00:00.000Z | 54 | 1:28:48.78 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | Team Lotus 🇬🇧 |
| 1972 | 9 | 1972 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1972-08-13T00:00:00.000Z | 54 | 1:29:16.660 | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | Team Lotus 🇬🇧 |
| 1971 | 8 | 1971 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1971-08-15T00:00:00.000Z | 54 | 1:30:23.91 | [Jo Siffert 🇨🇭](/f1/drivers/siffert) | BRM 🇬🇧 |
| 1970 | 9 | 1970 Austrian Grand Prix 🇦🇹 | [A1-Ring](/f1/circuits/osterreichring) | 1970-08-16T00:00:00.000Z | 60 | 1:42:17.3 | [Jacky Ickx 🇧🇪](/f1/drivers/ickx) | Ferrari 🇮🇹 |
| 1964 | 7 | 1964 Austrian Grand Prix 🇦🇹 | [Zeltweg](/f1/circuits/zeltweg) | 1964-08-23T00:00:00.000Z | 105 | 2:06:18.23 | [Lorenzo Bandini 🇮🇹](/f1/drivers/bandini) | Ferrari 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Circuit** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 30 |  |  | 30 | 29 |  |  |  |
| **Total Sum** | 299.000 |  |  | 17554233600.000 | 1754.000 |  |  |  |
| **Mean μ (Average)** | 9.967 |  |  | 585141120.000 | 60.483 |  |  |  |
| **Maximum** | 14.000 |  |  | 1499558400.000 | 105.000 |  |  |  |
| **75th Percentile** | 12.000 |  |  | 963705600.000 | 71.000 |  |  |  |
| **Median** | 10.000 |  |  | 461721600.000 | 54.000 |  |  |  |
| **25th Percentile** | 9.000 |  |  | 208915200.000 | 53.000 |  |  |  |
| **Minimum** | 6.000 |  |  | -169084800.000 | 29.000 |  |  |  |
| **Variance** | 4.366 |  |  | 222325807579545600.000 | 168.732 |  |  |  |
| **Standard Deviation σ** | 2.089 |  |  | 471514376.854 | 12.990 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
