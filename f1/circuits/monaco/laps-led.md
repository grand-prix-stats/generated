---
title: Rank of Formula 1® Drivers by Number of Laps Led at Circuit de Monaco
layout: page
collectionName: circuits
collectionId: monaco
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
    "Nico Rosberg",
    "Lewis Hamilton",
    "Fernando Alonso",
    "Mark Webber",
    "Sebastian Vettel",
    "Kimi Räikkönen",
    "David Coulthard",
    "Jenson Button",
    "Mika Häkkinen",
    "Jarno Trulli",
    "Juan Pablo Montoya",
    "Damon Hill",
    "Daniel Ricciardo",
    "Felipe Massa",
    "Jean Alesi",
    "Ralf Schumacher",
    "Olivier Panis",
    "Robert Kubica",
    "Rubens Barrichello"
  ],
  "datasets" : [
    {
      "label" : "Number Of Laps Led",
      "data" : [
        282,
        170,
        167,
        153,
        140,
        121,
        118,
        101,
        93,
        78,
        74,
        40,
        38,
        24,
        23,
        21,
        20,
        16,
        10,
        5
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
| 1. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 282 |
| 2. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 170 |
| 3. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 167 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 153 |
| 5. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 140 |
| 6. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 121 |
| 7. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 118 |
| 8. | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | 101 |
| 9. | [Jenson Button 🇬🇧](/f1/drivers/button) | 93 |
| 10. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 78 |
| 11. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 74 |
| 12. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 40 |
| 13. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 38 |
| 14. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 24 |
| 15. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 23 |
| 16. | [Jean Alesi 🇫🇷](/f1/drivers/alesi) | 21 |
| 17. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 20 |
| 18. | [Olivier Panis 🇫🇷](/f1/drivers/panis) | 16 |
| 19. | [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 10 |
| 20. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 5 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 20 |
| **Total Sum** | 1694.000 |
| **Mean μ (Average)** | 84.700 |
| **Maximum** | 282.000 |
| **75th Percentile** | 140.000 |
| **Median** | 78.000 |
| **25th Percentile** | 23.000 |
| **Minimum** | 5.000 |
| **Variance** | 5009.310 |
| **Standard Deviation σ** | 70.776 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
