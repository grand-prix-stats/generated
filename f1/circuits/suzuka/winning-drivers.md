---
title: Rank of Formula 1® Drivers by Number of Wins at Suzuka Circuit
layout: page
collectionName: circuits
collectionId: suzuka
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
    "Michael Schumacher",
    "Sebastian Vettel",
    "Ayrton Senna",
    "Damon Hill",
    "Gerhard Berger",
    "Lewis Hamilton",
    "Mika Häkkinen",
    "Alessandro Nannini",
    "Fernando Alonso",
    "Jenson Button",
    "Kimi Räikkönen",
    "Nelson Piquet",
    "Nico Rosberg",
    "Riccardo Patrese",
    "Rubens Barrichello"
  ],
  "datasets" : [
    {
      "label" : "Number Of Wins",
      "data" : [
        6,
        4,
        2,
        2,
        2,
        2,
        2,
        1,
        1,
        1,
        1,
        1,
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

| # | Driver | Number Of Wins |
|--|--|--|
| 1. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 6 |
| 2. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 4 |
| 3. | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 2 |
| 4. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 2 |
| 5. | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 2 |
| 6. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2 |
| 7. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 2 |
| 8. | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 1 |
| 9. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1 |
| 10. | [Jenson Button 🇬🇧](/f1/drivers/button) | 1 |
| 11. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 |
| 12. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 1 |
| 13. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 1 |
| 14. | [Riccardo Patrese 🇮🇹](/f1/drivers/patrese) | 1 |
| 15. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 15 |
| **Total Sum** | 28.000 |
| **Mean μ (Average)** | 1.867 |
| **Maximum** | 6.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.849 |
| **Standard Deviation σ** | 1.360 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
