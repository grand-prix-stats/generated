---
title: Rank of Formula 1® Drivers by Number of Podiums at Sochi Autodrom
layout: page
collectionName: circuits
collectionId: sochi
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
    "Kimi Räikkönen",
    "Nico Rosberg",
    "Sebastian Vettel",
    "Valtteri Bottas",
    "Sergio Pérez"
  ],
  "datasets" : [
    {
      "label" : "Number Of Podiums",
      "data" : [
        3,
        2,
        2,
        2,
        2,
        1
      ],
      "borderColor" : [
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

| # | Driver | Number Of Podiums |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 |
| 2. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 |
| 3. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 2 |
| 4. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 2 |
| 5. | [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 2 |
| 6. | [Sergio Pérez 🇲🇽](/f1/drivers/perez) | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 6 |
| **Total Sum** | 12.000 |
| **Mean μ (Average)** | 2.000 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 2.000 |
| **25th Percentile** | 2.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.333 |
| **Standard Deviation σ** | 0.577 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
