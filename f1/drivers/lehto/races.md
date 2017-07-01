---
title: List of Formula 1® Races by Jyrki Järvilehto
layout: page
collectionName: drivers
collectionId: lehto
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
| 1994 | 16 | 1994 Australian Grand Prix 🇦🇺 | 1994-11-13T00:00:00.000Z | 17 | 10 | 0.0 | 79 |   | Sauber 🇨🇭 | [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | 10 | 7 |
| 1994 | 15 | 1994 Japanese Grand Prix 🇯🇵 | 1994-11-06T00:00:00.000Z | 15 | R | 0.0 | 0 |   | Sauber 🇨🇭 | [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | 3 | 6 |
| 1994 | 13 | 1994 Portuguese Grand Prix 🇵🇹 | 1994-09-25T00:00:00.000Z | 14 | R | 0.0 | 60 |   | Benetton 🇮🇹 | [Jos Verstappen 🇳🇱](/f1/drivers/verstappen) | 10 | 5 |
| 1994 | 12 | 1994 Italian Grand Prix 🇮🇹 | 1994-09-11T00:00:00.000Z | 20 | 9 | 0.0 | 52 |   | Benetton 🇮🇹 | [Jos Verstappen 🇳🇱](/f1/drivers/verstappen) | 10 | R |
| 1994 | 6 | 1994 Canadian Grand Prix 🇨🇦 | 1994-06-12T00:00:00.000Z | 20 | 6 | 1.0 | 68 |   | Benetton 🇮🇹 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 | 1 |
| 1994 | 5 | 1994 Spanish Grand Prix 🇪🇸 | 1994-05-29T00:00:00.000Z | 4 | R | 0.0 | 53 |   | Benetton 🇮🇹 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 | 2 |
| 1994 | 4 | 1994 Monaco Grand Prix 🇲🇨 | 1994-05-15T00:00:00.000Z | 17 | 7 | 0.0 | 77 |   | Benetton 🇮🇹 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 | 1 |
| 1994 | 3 | 1994 San Marino Grand Prix 🇮🇹 | 1994-05-01T00:00:00.000Z | 5 | R | 0.0 | 0 |   | Benetton 🇮🇹 | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 2 | 1 |
| 1993 | 16 | 1993 Australian Grand Prix 🇦🇺 | 1993-11-07T00:00:00.000Z | 12 | R | 0.0 | 56 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 11 | 15 |
| 1993 | 15 | 1993 Japanese Grand Prix 🇯🇵 | 1993-10-24T00:00:00.000Z | 11 | 8 | 0.0 | 52 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 16 | R |
| 1993 | 14 | 1993 Portuguese Grand Prix 🇵🇹 | 1993-09-26T00:00:00.000Z | 12 | 7 | 0.0 | 69 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 13 | 5 |
| 1993 | 13 | 1993 Italian Grand Prix 🇮🇹 | 1993-09-12T00:00:00.000Z | 13 | R | 0.0 | 0 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 15 | 4 |
| 1993 | 12 | 1993 Belgian Grand Prix 🇧🇪 | 1993-08-29T00:00:00.000Z | 9 | 9 | 0.0 | 43 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 12 | R |
| 1993 | 11 | 1993 Hungarian Grand Prix 🇭🇺 | 1993-08-15T00:00:00.000Z | 15 | R | 0.0 | 18 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 17 | 6 |
| 1993 | 10 | 1993 German Grand Prix 🇩🇪 | 1993-07-25T00:00:00.000Z | 18 | R | 0.0 | 22 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 14 | 9 |
| 1993 | 9 | 1993 British Grand Prix 🇬🇧 | 1993-07-11T00:00:00.000Z | 16 | 8 | 0.0 | 58 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 18 | R |
| 1993 | 8 | 1993 French Grand Prix 🇫🇷 | 1993-07-04T00:00:00.000Z | 18 | R | 0.0 | 22 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 11 | R |
| 1993 | 7 | 1993 Canadian Grand Prix 🇨🇦 | 1993-06-13T00:00:00.000Z | 11 | 7 | 0.0 | 68 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 9 | 6 |
| 1993 | 6 | 1993 Monaco Grand Prix 🇲🇨 | 1993-05-23T00:00:00.000Z | 11 | R | 0.0 | 23 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 8 | 13 |
| 1993 | 5 | 1993 Spanish Grand Prix 🇪🇸 | 1993-05-09T00:00:00.000Z | 9 | R | 0.0 | 53 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 6 | R |
| 1993 | 4 | 1993 San Marino Grand Prix 🇮🇹 | 1993-04-25T00:00:00.000Z | 16 | 4 | 3.0 | 59 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 5 | R |
| 1993 | 3 | 1993 European Grand Prix 🇬🇧 | 1993-04-11T00:00:00.000Z | 7 | R | 0.0 | 13 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 5 | R |
| 1993 | 2 | 1993 Brazilian Grand Prix 🇧🇷 | 1993-03-28T00:00:00.000Z | 7 | R | 0.0 | 52 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 8 | R |
| 1993 | 1 | 1993 South African Grand Prix 🇿🇦 | 1993-03-14T00:00:00.000Z | 6 | 5 | 2.0 | 70 |   | Sauber 🇨🇭 | [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 10 | R |
| 1992 | 16 | 1992 Australian Grand Prix 🇦🇺 | 1992-11-08T00:00:00.000Z | 24 | R | 0.0 | 70 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 14 | R |
| 1992 | 15 | 1992 Japanese Grand Prix 🇯🇵 | 1992-10-25T00:00:00.000Z | 22 | 9 | 0.0 | 52 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 19 | 10 |
| 1992 | 14 | 1992 Portuguese Grand Prix 🇵🇹 | 1992-09-27T00:00:00.000Z | 19 | R | 0.0 | 51 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 21 | R |
| 1992 | 13 | 1992 Italian Grand Prix 🇮🇹 | 1992-09-13T00:00:00.000Z | 14 | 11 | 0.0 | 47 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 22 | 8 |
| 1992 | 12 | 1992 Belgian Grand Prix 🇧🇪 | 1992-08-30T00:00:00.000Z | 16 | 7 | 0.0 | 44 | +1:38.237 | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 19 | R |
| 1992 | 11 | 1992 Hungarian Grand Prix 🇭🇺 | 1992-08-16T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 26 | R |
| 1992 | 10 | 1992 German Grand Prix 🇩🇪 | 1992-07-26T00:00:00.000Z | 21 | 10 | 0.0 | 44 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 18 | 11 |
| 1992 | 9 | 1992 British Grand Prix 🇬🇧 | 1992-07-12T00:00:00.000Z | 19 | 13 | 0.0 | 57 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 22 | 15 |
| 1992 | 8 | 1992 French Grand Prix 🇫🇷 | 1992-07-05T00:00:00.000Z | 17 | 9 | 0.0 | 67 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 25 | 10 |
| 1992 | 7 | 1992 Canadian Grand Prix 🇨🇦 | 1992-06-14T00:00:00.000Z | 23 | 9 | 0.0 | 68 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 15 | 8 |
| 1992 | 6 | 1992 Monaco Grand Prix 🇲🇨 | 1992-05-31T00:00:00.000Z | 20 | 9 | 0.0 | 76 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 18 | R |
| 1992 | 5 | 1992 San Marino Grand Prix 🇮🇹 | 1992-05-17T00:00:00.000Z | 16 | 11 | 0.0 | 57 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 15 | 6 |
| 1992 | 4 | 1992 Spanish Grand Prix 🇪🇸 | 1992-05-03T00:00:00.000Z | 12 | R | 0.0 | 56 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 13 | 6 |
| 1992 | 3 | 1992 Brazilian Grand Prix 🇧🇷 | 1992-04-05T00:00:00.000Z | 16 | 8 | 0.0 | 69 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 8 | R |
| 1992 | 2 | 1992 Mexican Grand Prix 🇲🇽 | 1992-03-22T00:00:00.000Z | 7 | 8 | 0.0 | 68 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 9 | R |
| 1992 | 1 | 1992 South African Grand Prix 🇿🇦 | 1992-03-01T00:00:00.000Z | 24 | R | 0.0 | 44 |   | Dallara 🇮🇹 | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 25 | R |
| 1991 | 16 | 1991 Australian Grand Prix 🇦🇺 | 1991-11-03T00:00:00.000Z | 11 | 12 | 0.0 | 14 | +1:38.519 | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 13 | 7 |
| 1991 | 15 | 1991 Japanese Grand Prix 🇯🇵 | 1991-10-20T00:00:00.000Z | 12 | R | 0.0 | 1 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 16 | R |
| 1991 | 14 | 1991 Spanish Grand Prix 🇪🇸 | 1991-09-29T00:00:00.000Z | 15 | 8 | 0.0 | 64 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 9 | 15 |
| 1991 | 13 | 1991 Portuguese Grand Prix 🇵🇹 | 1991-09-22T00:00:00.000Z | 18 | R | 0.0 | 21 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 16 | R |
| 1991 | 12 | 1991 Italian Grand Prix 🇮🇹 | 1991-09-08T00:00:00.000Z | 20 | R | 0.0 | 35 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 16 | 10 |
| 1991 | 11 | 1991 Belgian Grand Prix 🇧🇪 | 1991-08-25T00:00:00.000Z | 14 | R | 0.0 | 33 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 25 | 8 |
| 1991 | 10 | 1991 Hungarian Grand Prix 🇭🇺 | 1991-08-11T00:00:00.000Z | 12 | R | 0.0 | 49 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 7 | R |
| 1991 | 9 | 1991 German Grand Prix 🇩🇪 | 1991-07-28T00:00:00.000Z | 20 | R | 0.0 | 35 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 18 | 10 |
| 1991 | 8 | 1991 British Grand Prix 🇬🇧 | 1991-07-14T00:00:00.000Z | 11 | 13 | 0.0 | 56 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 18 | 10 |
| 1991 | 7 | 1991 French Grand Prix 🇫🇷 | 1991-07-07T00:00:00.000Z | 26 | R | 0.0 | 39 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 0 | F |
| 1991 | 6 | 1991 Mexican Grand Prix 🇲🇽 | 1991-06-16T00:00:00.000Z | 16 | R | 0.0 | 30 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 0 | F |
| 1991 | 5 | 1991 Canadian Grand Prix 🇨🇦 | 1991-06-02T00:00:00.000Z | 17 | R | 0.0 | 50 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 10 | 9 |
| 1991 | 4 | 1991 Monaco Grand Prix 🇲🇨 | 1991-05-12T00:00:00.000Z | 21 | 11 | 0.0 | 75 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 12 | 6 |
| 1991 | 3 | 1991 San Marino Grand Prix 🇮🇹 | 1991-04-28T00:00:00.000Z | 16 | 3 | 4.0 | 60 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 0 | F |
| 1991 | 2 | 1991 Brazilian Grand Prix 🇧🇷 | 1991-03-24T00:00:00.000Z | 19 | R | 0.0 | 22 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 12 | 11 |
| 1991 | 1 | 1991 United States Grand Prix 🇺🇸 | 1991-03-10T00:00:00.000Z | 10 | R | 0.0 | 12 |   | Dallara 🇮🇹 | [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 9 | R |
| 1990 | 10 | 1990 Hungarian Grand Prix 🇭🇺 | 1990-08-12T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 0 | F |
| 1990 | 9 | 1990 German Grand Prix 🇩🇪 | 1990-07-29T00:00:00.000Z | 25 | N | 0.0 | 39 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 26 | R |
| 1990 | 8 | 1990 British Grand Prix 🇬🇧 | 1990-07-15T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 0 | F |
| 1990 | 7 | 1990 French Grand Prix 🇫🇷 | 1990-07-08T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 0 | F |
| 1990 | 6 | 1990 Mexican Grand Prix 🇲🇽 | 1990-06-24T00:00:00.000Z | 26 | R | 0.0 | 26 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 23 | 15 |
| 1990 | 5 | 1990 Canadian Grand Prix 🇨🇦 | 1990-06-10T00:00:00.000Z | 22 | R | 0.0 | 46 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 21 | R |
| 1990 | 4 | 1990 Monaco Grand Prix 🇲🇨 | 1990-05-27T00:00:00.000Z | 26 | R | 0.0 | 52 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 20 | 7 |
| 1990 | 3 | 1990 San Marino Grand Prix 🇮🇹 | 1990-05-13T00:00:00.000Z | 25 | 12 | 0.0 | 59 |   | Onyx 🇬🇧 | [Gregor Foitek 🇨🇭](/f1/drivers/foitek) | 23 | R |
| 1990 | 2 | 1990 Brazilian Grand Prix 🇧🇷 | 1990-03-25T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 0 | F |
| 1990 | 1 | 1990 United States Grand Prix 🇺🇸 | 1990-03-11T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 0 | F |
| 1989 | 16 | 1989 Australian Grand Prix 🇦🇺 | 1989-11-05T00:00:00.000Z | 17 | R | 0.0 | 27 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 0 | F |
| 1989 | 15 | 1989 Japanese Grand Prix 🇯🇵 | 1989-10-22T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 0 | F |
| 1989 | 14 | 1989 Spanish Grand Prix 🇪🇸 | 1989-10-01T00:00:00.000Z | 17 | R | 0.0 | 20 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 0 | F |
| 1989 | 13 | 1989 Portuguese Grand Prix 🇵🇹 | 1989-09-24T00:00:00.000Z | 0 | F | 0.0 | 0 |   | Onyx 🇬🇧 | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 12 | 3 |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 70 |  | 70 | 70 | 28 | 70 | 70 |  |  |  | 70 | 34 |
| **Total Sum** | 595.000 |  | 49264588800.000 | 989.000 | 243.000 | 10.000 | 2802.000 |  |  |  | 811.000 | 266.000 |
| **Mean μ (Average)** | 8.500 |  | 703779840.000 | 14.129 | 8.679 | 0.143 | 40.029 |  |  |  | 11.586 | 7.824 |
| **Maximum** | 16.000 |  | 784684800.000 | 26.000 | 13.000 | 4.000 | 79.000 |  |  |  | 26.000 | 15.000 |
| **75th Percentile** | 13.000 |  | 739929600.000 | 19.000 | 11.000 |  | 59.000 |  |  |  | 18.000 | 10.000 |
| **Median** | 8.000 |  | 707270400.000 | 16.000 | 9.000 |  | 47.000 |  |  |  | 12.000 | 8.000 |
| **25th Percentile** | 4.000 |  | 674006400.000 | 11.000 | 7.000 |  | 21.000 |  |  |  | 5.000 | 6.000 |
| **Minimum** | 1.000 |  | 622598400.000 |  | 3.000 |  |  |  |  |  |  | 1.000 |
| **Variance** | 22.021 |  | 1962093370982400.000 | 52.283 | 6.004 | 0.408 | 605.856 |  |  |  | 62.186 | 15.557 |
| **Standard Deviation σ** | 4.693 |  | 44295523.148 | 7.231 | 2.450 | 0.639 | 24.614 |  |  |  | 7.886 | 3.944 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
