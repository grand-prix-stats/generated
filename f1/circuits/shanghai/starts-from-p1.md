---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Shanghai International Circuit
layout: page
collectionName: circuits
collectionId: shanghai
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
    "Sebastian Vettel",
    "Fernando Alonso",
    "Nico Rosberg",
    "Rubens Barrichello"
  ],
  "datasets" : [
    {
      "label" : "Number Of Starts From P1",
      "data" : [
        6,
        3,
        2,
        2,
        1
      ],
      "borderColor" : [
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

| # | Driver | Number Of Starts From P1 |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 6 |
| 2. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 3 |
| 3. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 2 |
| 4. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 2 |
| 5. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 1 |

#### Statistic Summary

| **Column** | **Number Of Starts From P1** |
| **Row Count** | 5 |
| **Total Sum** | 14.000 |
| **Mean μ (Average)** | 2.800 |
| **Maximum** | 6.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 2.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.960 |
| **Standard Deviation σ** | 1.720 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})