---
title: Rank of Formula 1® Drivers by Number of Wins at Detroit Street Circuit
layout: page
collectionName: circuits
collectionId: detroit
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
    "datasets": [
        {
            "backgroundColor": [
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D",
                "#9C8E8D"
            ],
            "borderColor": [
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Ayrton Senna",
        "John Watson",
        "Keke Rosberg",
        "Michele Alboreto",
        "Nelson Piquet"
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
| 1. | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 3 |
| 2. | [John Watson 🇬🇧](/f1/drivers/watson) | 1 |
| 3. | [Keke Rosberg 🇫🇮](/f1/drivers/keke_rosberg) | 1 |
| 4. | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 1 |
| 5. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 5 |
| **Total Sum** | 7.000 |
| **Mean μ (Average)** | 1.400 |
| **Maximum** | 3.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.640 |
| **Standard Deviation σ** | 0.800 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
