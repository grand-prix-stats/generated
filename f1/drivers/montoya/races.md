---
title: List of Formula 1® Races by Juan Pablo Montoya
layout: page
collectionName: drivers
collectionId: montoya
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
| 2006 | 10 | 2006 United States Grand Prix 🇺🇸 | 2006-07-02T00:00:00.000Z | 11 | R | 0.0 | 0 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 9 | R |
| 2006 | 9 | 2006 Canadian Grand Prix 🇨🇦 | 2006-06-25T00:00:00.000Z | 7 | R | 0.0 | 13 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 3 | 3 |
| 2006 | 8 | 2006 British Grand Prix 🇬🇧 | 2006-06-11T00:00:00.000Z | 8 | 6 | 3.0 | 60 | +1:04.769 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 | 3 |
| 2006 | 7 | 2006 Monaco Grand Prix 🇲🇨 | 2006-05-28T00:00:00.000Z | 4 | 2 | 8.0 | 78 | +14.567 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 3 | R |
| 2006 | 6 | 2006 Spanish Grand Prix 🇪🇸 | 2006-05-14T00:00:00.000Z | 12 | R | 0.0 | 17 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 9 | 5 |
| 2006 | 5 | 2006 European Grand Prix 🇩🇪 | 2006-05-07T00:00:00.000Z | 8 | R | 0.0 | 52 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 5 | 4 |
| 2006 | 4 | 2006 San Marino Grand Prix 🇮🇹 | 2006-04-23T00:00:00.000Z | 7 | 3 | 6.0 | 62 | +15.868 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 8 | 5 |
| 2006 | 3 | 2006 Australian Grand Prix 🇦🇺 | 2006-04-02T00:00:00.000Z | 5 | R | 0.0 | 46 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 4 | 2 |
| 2006 | 2 | 2006 Malaysian Grand Prix 🇲🇾 | 2006-03-19T00:00:00.000Z | 5 | 4 | 5.0 | 56 | +39.351 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 6 | R |
| 2006 | 1 | 2006 Bahrain Grand Prix 🇧🇭 | 2006-03-12T00:00:00.000Z | 5 | 5 | 4.0 | 57 | +37.048 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 22 | 3 |
| 2005 | 19 | 2005 Chinese Grand Prix 🇨🇳 | 2005-10-16T00:00:00.000Z | 5 | R | 0.0 | 24 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 3 | 2 |
| 2005 | 18 | 2005 Japanese Grand Prix 🇯🇵 | 2005-10-09T00:00:00.000Z | 18 | R | 0.0 | 0 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 17 | 1 |
| 2005 | 17 | 2005 Brazilian Grand Prix 🇧🇷 | 2005-09-25T00:00:00.000Z | 2 | 1 | 10.0 | 71 | 1:29:20.574 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 5 | 2 |
| 2005 | 16 | 2005 Belgian Grand Prix 🇧🇪 | 2005-09-11T00:00:00.000Z | 1 | 14 | 0.0 | 40 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 | 1 |
| 2005 | 15 | 2005 Italian Grand Prix 🇮🇹 | 2005-09-04T00:00:00.000Z | 1 | 1 | 10.0 | 53 | 1:14:28.659 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 11 | 4 |
| 2005 | 14 | 2005 Turkish Grand Prix 🇹🇷 | 2005-08-21T00:00:00.000Z | 4 | 3 | 6.0 | 58 | +19.635 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 | 1 |
| 2005 | 13 | 2005 Hungarian Grand Prix 🇭🇺 | 2005-07-31T00:00:00.000Z | 2 | R | 0.0 | 41 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 4 | 1 |
| 2005 | 12 | 2005 German Grand Prix 🇩🇪 | 2005-07-24T00:00:00.000Z | 20 | 2 | 8.0 | 67 | +22.569 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 | R |
| 2005 | 11 | 2005 British Grand Prix 🇬🇧 | 2005-07-10T00:00:00.000Z | 3 | 1 | 10.0 | 60 | 1:24:29.588 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 12 | 3 |
| 2005 | 10 | 2005 French Grand Prix 🇫🇷 | 2005-07-03T00:00:00.000Z | 8 | R | 0.0 | 46 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 13 | 2 |
| 2005 | 9 | 2005 United States Grand Prix 🇺🇸 | 2005-06-19T00:00:00.000Z | 11 | W | 0.0 | 0 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 | W |
| 2005 | 8 | 2005 Canadian Grand Prix 🇨🇦 | 2005-06-12T00:00:00.000Z | 5 | D | 0.0 | 52 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 7 | 1 |
| 2005 | 7 | 2005 European Grand Prix 🇩🇪 | 2005-05-29T00:00:00.000Z | 5 | 7 | 2.0 | 59 | +58.173 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 | 11 |
| 2005 | 6 | 2005 Monaco Grand Prix 🇲🇨 | 2005-05-22T00:00:00.000Z | 16 | 5 | 4.0 | 78 | +36.647 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 | 1 |
| 2005 | 5 | 2005 Spanish Grand Prix 🇪🇸 | 2005-05-08T00:00:00.000Z | 7 | 7 | 2.0 | 65 |   | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 | 1 |
| 2005 | 2 | 2005 Malaysian Grand Prix 🇲🇾 | 2005-03-20T00:00:00.000Z | 11 | 4 | 5.0 | 56 | +41.631 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 6 | 9 |
| 2005 | 1 | 2005 Australian Grand Prix 🇦🇺 | 2005-03-06T00:00:00.000Z | 9 | 6 | 3.0 | 57 | +35.033 | McLaren 🇬🇧 | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 10 | 8 |
| 2004 | 18 | 2004 Brazilian Grand Prix 🇧🇷 | 2004-10-24T00:00:00.000Z | 2 | 1 | 10.0 | 71 | 1:28:01.451 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 7 | 5 |
| 2004 | 17 | 2004 Japanese Grand Prix 🇯🇵 | 2004-10-10T00:00:00.000Z | 13 | 7 | 2.0 | 53 | +55.347 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 2 |
| 2004 | 16 | 2004 Chinese Grand Prix 🇨🇳 | 2004-09-26T00:00:00.000Z | 10 | 5 | 4.0 | 56 | +45.193 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | R |
| 2004 | 15 | 2004 Italian Grand Prix 🇮🇹 | 2004-09-12T00:00:00.000Z | 2 | 5 | 4.0 | 53 | +32.352 | Williams 🇬🇧 | [Antônio Pizzonia 🇧🇷](/f1/drivers/pizzonia) | 8 | 7 |
| 2004 | 14 | 2004 Belgian Grand Prix 🇧🇪 | 2004-08-29T00:00:00.000Z | 11 | R | 0.0 | 37 |   | Williams 🇬🇧 | [Antônio Pizzonia 🇧🇷](/f1/drivers/pizzonia) | 14 | R |
| 2004 | 13 | 2004 Hungarian Grand Prix 🇭🇺 | 2004-08-15T00:00:00.000Z | 7 | 4 | 5.0 | 70 | +1:02.613 | Williams 🇬🇧 | [Antônio Pizzonia 🇧🇷](/f1/drivers/pizzonia) | 6 | 7 |
| 2004 | 12 | 2004 German Grand Prix 🇩🇪 | 2004-07-25T00:00:00.000Z | 2 | 5 | 4.0 | 66 | +23.055 | Williams 🇬🇧 | [Antônio Pizzonia 🇧🇷](/f1/drivers/pizzonia) | 10 | 7 |
| 2004 | 11 | 2004 British Grand Prix 🇬🇧 | 2004-07-11T00:00:00.000Z | 7 | 5 | 4.0 | 60 | +12.173 | Williams 🇬🇧 | [Marc Gené 🇪🇸](/f1/drivers/gene) | 11 | 12 |
| 2004 | 10 | 2004 French Grand Prix 🇫🇷 | 2004-07-04T00:00:00.000Z | 6 | 8 | 1.0 | 70 | +43.419 | Williams 🇬🇧 | [Marc Gené 🇪🇸](/f1/drivers/gene) | 8 | 10 |
| 2004 | 9 | 2004 United States Grand Prix 🇺🇸 | 2004-06-20T00:00:00.000Z | 5 | D | 0.0 | 57 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 6 | R |
| 2004 | 8 | 2004 Canadian Grand Prix 🇨🇦 | 2004-06-13T00:00:00.000Z | 4 | D | 0.0 | 70 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 | D |
| 2004 | 7 | 2004 European Grand Prix 🇩🇪 | 2004-05-30T00:00:00.000Z | 8 | 8 | 1.0 | 59 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 9 | R |
| 2004 | 6 | 2004 Monaco Grand Prix 🇲🇨 | 2004-05-23T00:00:00.000Z | 9 | 4 | 5.0 | 76 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 12 | 10 |
| 2004 | 5 | 2004 Spanish Grand Prix 🇪🇸 | 2004-05-09T00:00:00.000Z | 2 | R | 0.0 | 46 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 6 | 6 |
| 2004 | 4 | 2004 San Marino Grand Prix 🇮🇹 | 2004-04-25T00:00:00.000Z | 3 | 3 | 6.0 | 62 | +21.617 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | 7 |
| 2004 | 3 | 2004 Bahrain Grand Prix 🇧🇭 | 2004-04-04T00:00:00.000Z | 3 | 13 | 0.0 | 56 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 7 |
| 2004 | 2 | 2004 Malaysian Grand Prix 🇲🇾 | 2004-03-21T00:00:00.000Z | 4 | 2 | 8.0 | 56 | +5.022 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 7 | R |
| 2004 | 1 | 2004 Australian Grand Prix 🇦🇺 | 2004-03-07T00:00:00.000Z | 3 | 5 | 4.0 | 58 | +1:08.536 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 8 | 4 |
| 2003 | 16 | 2003 Japanese Grand Prix 🇯🇵 | 2003-10-12T00:00:00.000Z | 2 | R | 0.0 | 9 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 19 | 12 |
| 2003 | 15 | 2003 United States Grand Prix 🇺🇸 | 2003-09-28T00:00:00.000Z | 4 | 6 | 3.0 | 72 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | R |
| 2003 | 14 | 2003 Italian Grand Prix 🇮🇹 | 2003-09-14T00:00:00.000Z | 2 | 2 | 8.0 | 53 | +5.294 | Williams 🇬🇧 | [Marc Gené 🇪🇸](/f1/drivers/gene) | 5 | 5 |
| 2003 | 13 | 2003 Hungarian Grand Prix 🇭🇺 | 2003-08-24T00:00:00.000Z | 4 | 3 | 6.0 | 70 | +34.537 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 4 |
| 2003 | 12 | 2003 German Grand Prix 🇩🇪 | 2003-08-03T00:00:00.000Z | 1 | 1 | 10.0 | 67 | 1:28:48.769 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | R |
| 2003 | 11 | 2003 British Grand Prix 🇬🇧 | 2003-07-20T00:00:00.000Z | 7 | 2 | 8.0 | 60 | +5.462 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 9 |
| 2003 | 10 | 2003 French Grand Prix 🇫🇷 | 2003-07-06T00:00:00.000Z | 2 | 2 | 8.0 | 70 | +13.813 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 | 1 |
| 2003 | 9 | 2003 European Grand Prix 🇩🇪 | 2003-06-29T00:00:00.000Z | 4 | 2 | 8.0 | 60 | +16.821 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 1 |
| 2003 | 8 | 2003 Canadian Grand Prix 🇨🇦 | 2003-06-15T00:00:00.000Z | 2 | 3 | 6.0 | 70 | +1.355 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 | 2 |
| 2003 | 7 | 2003 Monaco Grand Prix 🇲🇨 | 2003-06-01T00:00:00.000Z | 3 | 1 | 10.0 | 78 | 1:42:19.010 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 | 4 |
| 2003 | 6 | 2003 Austrian Grand Prix 🇦🇹 | 2003-05-18T00:00:00.000Z | 3 | R | 0.0 | 32 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 10 | 6 |
| 2003 | 5 | 2003 Spanish Grand Prix 🇪🇸 | 2003-05-04T00:00:00.000Z | 9 | 4 | 5.0 | 65 | +1:02.0 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 7 | 5 |
| 2003 | 4 | 2003 San Marino Grand Prix 🇮🇹 | 2003-04-20T00:00:00.000Z | 4 | 7 | 2.0 | 62 | +45.271 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 4 |
| 2003 | 3 | 2003 Brazilian Grand Prix 🇧🇷 | 2003-04-06T00:00:00.000Z | 9 | R | 0.0 | 25 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 6 | 7 |
| 2003 | 2 | 2003 Malaysian Grand Prix 🇲🇾 | 2003-03-23T00:00:00.000Z | 8 | 12 | 0.0 | 53 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 17 | 4 |
| 2003 | 1 | 2003 Australian Grand Prix 🇦🇺 | 2003-03-09T00:00:00.000Z | 3 | 2 | 8.0 | 58 | +8.675 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 9 | 8 |
| 2002 | 17 | 2002 Japanese Grand Prix 🇯🇵 | 2002-10-13T00:00:00.000Z | 6 | 4 | 3.0 | 53 | +36.275 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | 11 |
| 2002 | 16 | 2002 United States Grand Prix 🇺🇸 | 2002-09-29T00:00:00.000Z | 4 | 4 | 3.0 | 73 | +9.911 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | 16 |
| 2002 | 15 | 2002 Italian Grand Prix 🇮🇹 | 2002-09-15T00:00:00.000Z | 1 | R | 0.0 | 33 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | R |
| 2002 | 14 | 2002 Belgian Grand Prix 🇧🇪 | 2002-09-01T00:00:00.000Z | 5 | 3 | 4.0 | 44 | +18.445 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 5 |
| 2002 | 13 | 2002 Hungarian Grand Prix 🇭🇺 | 2002-08-18T00:00:00.000Z | 4 | 11 | 0.0 | 76 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 3 |
| 2002 | 12 | 2002 German Grand Prix 🇩🇪 | 2002-07-28T00:00:00.000Z | 4 | 2 | 6.0 | 67 | +10.503 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 3 |
| 2002 | 11 | 2002 French Grand Prix 🇫🇷 | 2002-07-21T00:00:00.000Z | 1 | 4 | 3.0 | 72 | +40.675 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | 5 |
| 2002 | 10 | 2002 British Grand Prix 🇬🇧 | 2002-07-07T00:00:00.000Z | 1 | 3 | 4.0 | 60 | +31.661 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 8 |
| 2002 | 9 | 2002 European Grand Prix 🇩🇪 | 2002-06-23T00:00:00.000Z | 1 | R | 0.0 | 27 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 4 |
| 2002 | 8 | 2002 Canadian Grand Prix 🇨🇦 | 2002-06-09T00:00:00.000Z | 1 | R | 0.0 | 56 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 7 |
| 2002 | 7 | 2002 Monaco Grand Prix 🇲🇨 | 2002-05-26T00:00:00.000Z | 1 | R | 0.0 | 46 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 3 |
| 2002 | 6 | 2002 Austrian Grand Prix 🇦🇹 | 2002-05-12T00:00:00.000Z | 4 | 3 | 4.0 | 71 | +17.730 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 4 |
| 2002 | 5 | 2002 Spanish Grand Prix 🇪🇸 | 2002-04-28T00:00:00.000Z | 4 | 2 | 6.0 | 65 | +35.630 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 11 |
| 2002 | 4 | 2002 San Marino Grand Prix 🇮🇹 | 2002-04-14T00:00:00.000Z | 4 | 4 | 3.0 | 62 | +44.725 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 3 |
| 2002 | 3 | 2002 Brazilian Grand Prix 🇧🇷 | 2002-03-31T00:00:00.000Z | 1 | 5 | 2.0 | 71 | +1:07.563 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 2 |
| 2002 | 2 | 2002 Malaysian Grand Prix 🇲🇾 | 2002-03-17T00:00:00.000Z | 2 | 2 | 6.0 | 56 | +39.700 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 1 |
| 2002 | 1 | 2002 Australian Grand Prix 🇦🇺 | 2002-03-03T00:00:00.000Z | 6 | 2 | 6.0 | 58 | +18.628 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | R |
| 2001 | 17 | 2001 Japanese Grand Prix 🇯🇵 | 2001-10-14T00:00:00.000Z | 2 | 2 | 6.0 | 53 | +3.154 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 6 |
| 2001 | 16 | 2001 United States Grand Prix 🇺🇸 | 2001-09-30T00:00:00.000Z | 3 | R | 0.0 | 38 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | R |
| 2001 | 15 | 2001 Italian Grand Prix 🇮🇹 | 2001-09-16T00:00:00.000Z | 1 | 1 | 10.0 | 53 | 1:16:58.493 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 3 |
| 2001 | 14 | 2001 Belgian Grand Prix 🇧🇪 | 2001-09-02T00:00:00.000Z | 1 | R | 0.0 | 1 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 7 |
| 2001 | 13 | 2001 Hungarian Grand Prix 🇭🇺 | 2001-08-19T00:00:00.000Z | 8 | 8 | 0.0 | 76 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 4 | 4 |
| 2001 | 12 | 2001 German Grand Prix 🇩🇪 | 2001-07-29T00:00:00.000Z | 1 | R | 0.0 | 24 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 1 |
| 2001 | 11 | 2001 British Grand Prix 🇬🇧 | 2001-07-15T00:00:00.000Z | 8 | 4 | 3.0 | 60 | +1:08.772 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 10 | R |
| 2001 | 10 | 2001 French Grand Prix 🇫🇷 | 2001-07-01T00:00:00.000Z | 6 | R | 0.0 | 52 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 | 2 |
| 2001 | 9 | 2001 European Grand Prix 🇩🇪 | 2001-06-24T00:00:00.000Z | 3 | 2 | 6.0 | 67 | +4.127 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 4 |
| 2001 | 8 | 2001 Canadian Grand Prix 🇨🇦 | 2001-06-10T00:00:00.000Z | 10 | R | 0.0 | 19 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | 1 |
| 2001 | 7 | 2001 Monaco Grand Prix 🇲🇨 | 2001-05-27T00:00:00.000Z | 7 | R | 0.0 | 2 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | R |
| 2001 | 6 | 2001 Austrian Grand Prix 🇦🇹 | 2001-05-13T00:00:00.000Z | 2 | R | 0.0 | 41 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | R |
| 2001 | 5 | 2001 Spanish Grand Prix 🇪🇸 | 2001-04-29T00:00:00.000Z | 12 | 2 | 6.0 | 65 | +40.738 | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | R |
| 2001 | 4 | 2001 San Marino Grand Prix 🇮🇹 | 2001-04-15T00:00:00.000Z | 7 | R | 0.0 | 48 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 1 |
| 2001 | 3 | 2001 Brazilian Grand Prix 🇧🇷 | 2001-04-01T00:00:00.000Z | 4 | R | 0.0 | 38 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 2 | R |
| 2001 | 2 | 2001 Malaysian Grand Prix 🇲🇾 | 2001-03-18T00:00:00.000Z | 6 | R | 0.0 | 3 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 3 | 5 |
| 2001 | 1 | 2001 Australian Grand Prix 🇦🇺 | 2001-03-04T00:00:00.000Z | 11 | R | 0.0 | 40 |   | Williams 🇬🇧 | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 5 | R |

#### Statistic Summary

| **Column** | **Round** | **Name** | **Date** | **Grid** | **Final Position** | **Points** | **Laps Completed** | **Time** | **Constructor** | **Teammate** | **Teammate Grid** | **Teammate Final Position** |
| **Row Count** | 95 |  | 95 | 95 | 62 | 95 | 95 | 40 |  |  | 95 | 73 |
| **Total Sum** | 851.000 |  | 101328624000.000 | 510.000 | 261.000 | 307.000 | 4918.000 | 1041.830 |  |  | 509.000 | 349.000 |
| **Mean μ (Average)** | 8.958 |  | 1066617094.737 | 5.368 | 4.210 | 3.232 | 51.768 | 26.046 |  |  | 5.358 | 4.781 |
| **Maximum** | 19.000 |  | 1151798400.000 | 20.000 | 14.000 | 10.000 | 78.000 | 58.173 |  |  | 22.000 | 16.000 |
| **75th Percentile** | 13.000 |  | 1116720000.000 | 8.000 | 5.000 | 6.000 | 66.000 | 39.700 |  |  | 7.000 | 7.000 |
| **Median** | 9.000 |  | 1063497600.000 | 4.000 | 4.000 | 3.000 | 57.000 | 23.055 |  |  | 4.000 | 4.000 |
| **25th Percentile** | 5.000 |  | 1022371200.000 | 2.000 | 2.000 |  | 44.000 | 13.813 |  |  | 2.000 | 2.000 |
| **Minimum** | 1.000 |  | 983664000.000 | 1.000 | 1.000 |  |  | 1.355 |  |  | 1.000 | 1.000 |
| **Variance** | 25.072 |  | 2629374134447867.500 | 15.096 | 8.488 | 10.852 | 397.778 | 240.209 |  |  | 17.493 | 10.883 |
| **Standard Deviation σ** | 5.007 |  | 51277423.243 | 3.885 | 2.913 | 3.294 | 19.944 | 15.499 |  |  | 4.182 | 3.299 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
