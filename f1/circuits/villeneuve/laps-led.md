---
title: Rank of Formula 1® Drivers by Number of Laps Led at Circuit Gilles Villeneuve
layout: page
collectionName: circuits
collectionId: villeneuve
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

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
  "labels" : [
    "Lewis Hamilton",
    "Michael Schumacher",
    "Sebastian Vettel",
    "Fernando Alonso",
    "Ralf Schumacher",
    "Nico Rosberg",
    "Damon Hill",
    "Giancarlo Fisichella",
    "Mika Häkkinen",
    "Rubens Barrichello",
    "David Coulthard",
    "Robert Kubica",
    "Kimi Räikkönen",
    "Juan Pablo Montoya",
    "Mark Webber",
    "Nick Heidfeld",
    "Jacques Villeneuve",
    "Felipe Massa",
    "Daniel Ricciardo",
    "Timo Glock",
    "Jarno Trulli",
    "Jenson Button",
    "Romain Grosjean",
    "Sébastien Buemi"
  ],
  "datasets" : [
    {
      "label" : "Number Of Laps Led",
      "data" : [
        352,
        307,
        180,
        103,
        72,
        63,
        61,
        56,
        40,
        40,
        39,
        29,
        27,
        23,
        22,
        10,
        8,
        6,
        3,
        3,
        2,
        1,
        1,
        1
      ],
      "borderColor" : [
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E",
        "#1D181E"
      ],
      "borderWidth" : 1,
      "backgroundColor" : [
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D",
        "#9C8E8D"
      ]
    }
  ]
};
var options = {
  legend: {
    display: false
  },
  scales: {
    xAxes: [{
      ticks: {
        beginAtZero: true,
        maxRotation: 180,
        display: window.innerWidth > 800
      }
    }],
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  },
  onResize: function(chart, size) {
    chart.options.scales.xAxes[0].ticks.display = size.width > 800;
  }
};
var chart = new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>



### Data Table

| # | Driver | Number Of Laps Led |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 352 |
| 2. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 307 |
| 3. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 180 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 103 |
| 5. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 72 |
| 6. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 63 |
| 7. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 61 |
| 8. | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 56 |
| 9. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 40 |
| 10. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 40 |
| 11. | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | 39 |
| 12. | [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 29 |
| 13. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 27 |
| 14. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 23 |
| 15. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 22 |
| 16. | [Nick Heidfeld 🇩🇪](/f1/drivers/heidfeld) | 10 |
| 17. | [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | 8 |
| 18. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 6 |
| 19. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 3 |
| 20. | [Timo Glock 🇩🇪](/f1/drivers/glock) | 3 |
| 21. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 2 |
| 22. | [Jenson Button 🇬🇧](/f1/drivers/button) | 1 |
| 23. | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 1 |
| 24. | [Sébastien Buemi 🇨🇭](/f1/drivers/buemi) | 1 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 24 |
| **Total Sum** | 1449.000 |
| **Mean μ (Average)** | 60.375 |
| **Maximum** | 352.000 |
| **75th Percentile** | 63.000 |
| **Median** | 29.000 |
| **25th Percentile** | 6.000 |
| **Minimum** | 1.000 |
| **Variance** | 8217.401 |
| **Standard Deviation σ** | 90.650 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
