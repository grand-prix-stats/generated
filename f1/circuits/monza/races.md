---
title: List of All Formula 1® Races at Autodromo Nazionale di Monza
layout: page
collectionName: circuits
collectionId: monza
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
| 2017 | 13 | 2017 Italian Grand Prix 🇮🇹 | 2017-09-03T00:00:00.000Z |   |   |   |   |
| 2016 | 14 | 2016 Italian Grand Prix 🇮🇹 | 2016-09-04T00:00:00.000Z | 53 | 1:17:28.089 | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | Mercedes 🇩🇪 |
| 2015 | 12 | 2015 Italian Grand Prix 🇮🇹 | 2015-09-06T00:00:00.000Z | 53 | 1:18:00.688 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | Mercedes 🇩🇪 |
| 2014 | 13 | 2014 Italian Grand Prix 🇮🇹 | 2014-09-07T00:00:00.000Z | 53 | 1:19:10.236 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | Mercedes 🇩🇪 |
| 2013 | 12 | 2013 Italian Grand Prix 🇮🇹 | 2013-09-08T00:00:00.000Z | 53 | 1:18:33.352 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2012 | 13 | 2012 Italian Grand Prix 🇮🇹 | 2012-09-09T00:00:00.000Z | 53 | 1:19:41.221 | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | McLaren 🇬🇧 |
| 2011 | 13 | 2011 Italian Grand Prix 🇮🇹 | 2011-09-11T00:00:00.000Z | 53 | 1:20:46.172 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Red Bull 🇦🇹 |
| 2010 | 14 | 2010 Italian Grand Prix 🇮🇹 | 2010-09-12T00:00:00.000Z | 53 | 1:16:24.572 | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | Ferrari 🇮🇹 |
| 2009 | 13 | 2009 Italian Grand Prix 🇮🇹 | 2009-09-13T00:00:00.000Z | 53 | 1:16:21.706 | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | Brawn 🇬🇧 |
| 2008 | 14 | 2008 Italian Grand Prix 🇮🇹 | 2008-09-14T00:00:00.000Z | 53 | 1:26:47.494 | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | Toro Rosso 🇮🇹 |
| 2007 | 13 | 2007 Italian Grand Prix 🇮🇹 | 2007-09-09T00:00:00.000Z | 53 | 1:18:37.806 | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | McLaren 🇬🇧 |
| 2006 | 15 | 2006 Italian Grand Prix 🇮🇹 | 2006-09-10T00:00:00.000Z | 53 | 1:14:51.975 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2005 | 15 | 2005 Italian Grand Prix 🇮🇹 | 2005-09-04T00:00:00.000Z | 53 | 1:14:28.659 | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | McLaren 🇬🇧 |
| 2004 | 15 | 2004 Italian Grand Prix 🇮🇹 | 2004-09-12T00:00:00.000Z | 53 | 1:15:18.448 | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | Ferrari 🇮🇹 |
| 2003 | 14 | 2003 Italian Grand Prix 🇮🇹 | 2003-09-14T00:00:00.000Z | 53 | 1:14:19.838 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 2002 | 15 | 2002 Italian Grand Prix 🇮🇹 | 2002-09-15T00:00:00.000Z | 53 | 1:16:19.982 | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | Ferrari 🇮🇹 |
| 2001 | 15 | 2001 Italian Grand Prix 🇮🇹 | 2001-09-16T00:00:00.000Z | 53 | 1:16:58.493 | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | Williams 🇬🇧 |
| 2000 | 14 | 2000 Italian Grand Prix 🇮🇹 | 2000-09-10T00:00:00.000Z | 53 | 1:27:31.638 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 1999 | 13 | 1999 Italian Grand Prix 🇮🇹 | 1999-09-12T00:00:00.000Z | 53 | 1:17:02.923 | [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | Jordan 🇮🇪 |
| 1998 | 14 | 1998 Italian Grand Prix 🇮🇹 | 1998-09-13T00:00:00.000Z | 53 | 1:17:10.3 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 1997 | 13 | 1997 Italian Grand Prix 🇮🇹 | 1997-09-07T00:00:00.000Z | 53 | 1:17:04.609 | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | McLaren 🇬🇧 |
| 1996 | 14 | 1996 Italian Grand Prix 🇮🇹 | 1996-09-08T00:00:00.000Z | 53 | 1:17:43.632 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | Ferrari 🇮🇹 |
| 1995 | 12 | 1995 Italian Grand Prix 🇮🇹 | 1995-09-10T00:00:00.000Z | 53 | 1:18:27.916 | [Johnny Herbert 🇬🇧](/f1/drivers/herbert) | Benetton 🇮🇹 |
| 1994 | 12 | 1994 Italian Grand Prix 🇮🇹 | 1994-09-11T00:00:00.000Z | 53 | 1:18:03.2 | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | Williams 🇬🇧 |
| 1993 | 13 | 1993 Italian Grand Prix 🇮🇹 | 1993-09-12T00:00:00.000Z | 53 | 1:17:07.509 | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | Williams 🇬🇧 |
| 1992 | 13 | 1992 Italian Grand Prix 🇮🇹 | 1992-09-13T00:00:00.000Z | 53 | 1:18:15.349 | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | McLaren 🇬🇧 |
| 1991 | 12 | 1991 Italian Grand Prix 🇮🇹 | 1991-09-08T00:00:00.000Z | 53 | 1:17:54.319 | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | Williams 🇬🇧 |
| 1990 | 12 | 1990 Italian Grand Prix 🇮🇹 | 1990-09-09T00:00:00.000Z | 53 | 1:17:57.878 | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | McLaren 🇬🇧 |
| 1989 | 12 | 1989 Italian Grand Prix 🇮🇹 | 1989-09-10T00:00:00.000Z | 53 | 1:19:27.550 | [Alain Prost 🇫🇷](/f1/drivers/prost) | McLaren 🇬🇧 |
| 1988 | 12 | 1988 Italian Grand Prix 🇮🇹 | 1988-09-11T00:00:00.000Z | 51 | 1:17:39.744 | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | Ferrari 🇮🇹 |
| 1987 | 11 | 1987 Italian Grand Prix 🇮🇹 | 1987-09-06T00:00:00.000Z | 50 | 1:14:47.707 | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | Williams 🇬🇧 |
| 1986 | 13 | 1986 Italian Grand Prix 🇮🇹 | 1986-09-07T00:00:00.000Z | 51 | 1:17:42.889 | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | Williams 🇬🇧 |
| 1985 | 12 | 1985 Italian Grand Prix 🇮🇹 | 1985-09-08T00:00:00.000Z | 51 | 1:17:59.451 | [Alain Prost 🇫🇷](/f1/drivers/prost) | McLaren 🇬🇧 |
| 1984 | 14 | 1984 Italian Grand Prix 🇮🇹 | 1984-09-09T00:00:00.000Z | 51 | 1:20:29.065 | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | McLaren 🇬🇧 |
| 1983 | 13 | 1983 Italian Grand Prix 🇮🇹 | 1983-09-11T00:00:00.000Z | 52 | 1:23:10.880 | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | Brabham 🇬🇧 |
| 1982 | 15 | 1982 Italian Grand Prix 🇮🇹 | 1982-09-12T00:00:00.000Z | 52 | 1:22:25.734 | [René Arnoux 🇫🇷](/f1/drivers/arnoux) | Renault 🇫🇷 |
| 1981 | 13 | 1981 Italian Grand Prix 🇮🇹 | 1981-09-13T00:00:00.000Z | 52 | 1:26:36.897 | [Alain Prost 🇫🇷](/f1/drivers/prost) | Renault 🇫🇷 |
| 1979 | 13 | 1979 Italian Grand Prix 🇮🇹 | 1979-09-09T00:00:00.000Z | 50 | 1:22:00.22 | [Jody Scheckter 🇿🇦](/f1/drivers/scheckter) | Ferrari 🇮🇹 |
| 1978 | 14 | 1978 Italian Grand Prix 🇮🇹 | 1978-09-10T00:00:00.000Z | 40 | 1:07:04.54 | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | Brabham 🇬🇧 |
| 1977 | 14 | 1977 Italian Grand Prix 🇮🇹 | 1977-09-11T00:00:00.000Z | 52 | 1:27:50.30 | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | Team Lotus 🇬🇧 |
| 1976 | 13 | 1976 Italian Grand Prix 🇮🇹 | 1976-09-12T00:00:00.000Z | 52 | 1:30:35.6 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | March 🇬🇧 |
| 1975 | 13 | 1975 Italian Grand Prix 🇮🇹 | 1975-09-07T00:00:00.000Z | 52 | 1:22:42.6 | [Clay Regazzoni 🇨🇭](/f1/drivers/regazzoni) | Ferrari 🇮🇹 |
| 1974 | 13 | 1974 Italian Grand Prix 🇮🇹 | 1974-09-08T00:00:00.000Z | 52 | 1:22:56.6 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | Team Lotus 🇬🇧 |
| 1973 | 13 | 1973 Italian Grand Prix 🇮🇹 | 1973-09-09T00:00:00.000Z | 55 | 1:29:17.0 | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | Team Lotus 🇬🇧 |
| 1972 | 10 | 1972 Italian Grand Prix 🇮🇹 | 1972-09-10T00:00:00.000Z | 55 | 1:29:58.4 | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | Team Lotus 🇬🇧 |
| 1971 | 9 | 1971 Italian Grand Prix 🇮🇹 | 1971-09-05T00:00:00.000Z | 55 | 1:18:12.60 | [Peter Gethin 🇬🇧](/f1/drivers/gethin) | BRM 🇬🇧 |
| 1970 | 10 | 1970 Italian Grand Prix 🇮🇹 | 1970-09-06T00:00:00.000Z | 68 | 1:39:07.1 | [Clay Regazzoni 🇨🇭](/f1/drivers/regazzoni) | Ferrari 🇮🇹 |
| 1969 | 8 | 1969 Italian Grand Prix 🇮🇹 | 1969-09-07T00:00:00.000Z | 68 | 1:39:11.26 | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | Matra-Ford 🇫🇷 |
| 1968 | 9 | 1968 Italian Grand Prix 🇮🇹 | 1968-09-08T00:00:00.000Z | 68 | 1:40:14.8 | [Denny Hulme 🇳🇿](/f1/drivers/hulme) | McLaren-Ford 🇬🇧 |
| 1967 | 9 | 1967 Italian Grand Prix 🇮🇹 | 1967-09-10T00:00:00.000Z | 68 | 1:43:45.0 | [John Surtees 🇬🇧](/f1/drivers/surtees) | Honda 🇯🇵 |
| 1966 | 7 | 1966 Italian Grand Prix 🇮🇹 | 1966-09-04T00:00:00.000Z | 68 | 1:47:14.8 | [Ludovico Scarfiotti 🇮🇹](/f1/drivers/scarfiotti) | Ferrari 🇮🇹 |
| 1965 | 8 | 1965 Italian Grand Prix 🇮🇹 | 1965-09-12T00:00:00.000Z | 76 | 2:04:52.8 | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | BRM 🇬🇧 |
| 1964 | 8 | 1964 Italian Grand Prix 🇮🇹 | 1964-09-06T00:00:00.000Z | 78 | 2:10:51.8 | [John Surtees 🇬🇧](/f1/drivers/surtees) | Ferrari 🇮🇹 |
| 1963 | 7 | 1963 Italian Grand Prix 🇮🇹 | 1963-09-08T00:00:00.000Z | 86 | 2:24:19.6 | [Jim Clark 🇬🇧](/f1/drivers/clark) | Lotus-Climax 🇬🇧 |
| 1962 | 7 | 1962 Italian Grand Prix 🇮🇹 | 1962-09-16T00:00:00.000Z | 86 | 2:29:08.4 | [Graham Hill 🇬🇧](/f1/drivers/hill) | BRM 🇬🇧 |
| 1961 | 7 | 1961 Italian Grand Prix 🇮🇹 | 1961-09-10T00:00:00.000Z | 43 | 2:03:13.0 | [Phil Hill 🇺🇸](/f1/drivers/phil_hill) | Ferrari 🇮🇹 |
| 1960 | 9 | 1960 Italian Grand Prix 🇮🇹 | 1960-09-04T00:00:00.000Z | 50 | 2:21:09.2 | [Phil Hill 🇺🇸](/f1/drivers/phil_hill) | Ferrari 🇮🇹 |
| 1959 | 8 | 1959 Italian Grand Prix 🇮🇹 | 1959-09-13T00:00:00.000Z | 72 | 2:04:05.4 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | Cooper-Climax 🇬🇧 |
| 1958 | 10 | 1958 Italian Grand Prix 🇮🇹 | 1958-09-07T00:00:00.000Z | 70 | 2:03:47.8 | [Tony Brooks 🇬🇧](/f1/drivers/brooks) | Vanwall 🇬🇧 |
| 1957 | 8 | 1957 Italian Grand Prix 🇮🇹 | 1957-09-08T00:00:00.000Z | 87 | 2:35:03.9 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | Vanwall 🇬🇧 |
| 1956 | 8 | 1956 Italian Grand Prix 🇮🇹 | 1956-09-02T00:00:00.000Z | 50 | 2:23:41.3 | [Stirling Moss 🇬🇧](/f1/drivers/moss) | Maserati 🇮🇹 |
| 1955 | 7 | 1955 Italian Grand Prix 🇮🇹 | 1955-09-11T00:00:00.000Z | 50 | 2:25:04.4 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Mercedes 🇩🇪 |
| 1954 | 8 | 1954 Italian Grand Prix 🇮🇹 | 1954-09-05T00:00:00.000Z | 80 | 2:47:47.9 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Mercedes 🇩🇪 |
| 1953 | 9 | 1953 Italian Grand Prix 🇮🇹 | 1953-09-13T00:00:00.000Z | 80 | 2:49:45.9 | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | Maserati 🇮🇹 |
| 1952 | 8 | 1952 Italian Grand Prix 🇮🇹 | 1952-09-07T00:00:00.000Z | 80 | 2:50:45.6 | [Alberto Ascari 🇮🇹](/f1/drivers/ascari) | Ferrari 🇮🇹 |
| 1951 | 7 | 1951 Italian Grand Prix 🇮🇹 | 1951-09-16T00:00:00.000Z | 80 | 2:42:39.3 | [Alberto Ascari 🇮🇹](/f1/drivers/ascari) | Ferrari 🇮🇹 |
| 1950 | 7 | 1950 Italian Grand Prix 🇮🇹 | 1950-09-03T00:00:00.000Z | 80 | 2:51:17.4 | [Nino Farina 🇮🇹](/f1/drivers/farina) | Alfa Romeo 🇮🇹 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Laps Completed** | **Race Duration** | **Winning Driver** | **Winning Constructor** |
| **Row Count** | 67 |  | 67 | 66 |  |  |  |
| **Total Sum** | 771.000 |  | 30109795200.000 | 3845.000 |  |  |  |
| **Mean μ (Average)** | 11.507 |  | 449399928.358 | 58.258 |  |  |  |
| **Maximum** | 15.000 |  | 1504396800.000 | 87.000 |  |  |  |
| **75th Percentile** | 13.000 |  | 1000598400.000 | 68.000 |  |  |  |
| **Median** | 13.000 |  | 463536000.000 | 53.000 |  |  |  |
| **25th Percentile** | 9.000 |  | -104976000.000 | 52.000 |  |  |  |
| **Minimum** | 7.000 |  | -609984000.000 | 40.000 |  |  |  |
| **Variance** | 6.817 |  | 389252191241891136.000 | 127.767 |  |  |  |
| **Standard Deviation σ** | 2.611 |  | 623900786.377 | 11.303 |  |  |  |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
