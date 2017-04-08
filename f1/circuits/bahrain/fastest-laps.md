---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Bahrain International Circuit
layout: page
collectionName: circuits
collectionId: bahrain
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
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E",
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                3.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Fastest Laps"
        }
    ],
    "labels": [
        "Nico Rosberg",
        "Sebastian Vettel",
        "Felipe Massa",
        "Fernando Alonso",
        "Heikki Kovalainen",
        "Jarno Trulli",
        "Kimi Räikkönen",
        "Michael Schumacher",
        "Pedro de la Rosa"
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

| # | Driver | Number Of Fastest Laps |
|--|--|--|
| 1. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 3 |
| 2. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 2 |
| 3. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 1 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1 |
| 5. | [Heikki Kovalainen 🇫🇮](/f1/drivers/kovalainen) | 1 |
| 6. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 1 |
| 7. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1 |
| 8. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 |
| 9. | [Pedro de la Rosa 🇪🇸](/f1/drivers/rosa) | 1 |

#### Statistic Summary

| **Column** | **Number Of Fastest Laps** |
| **Row Count** | 9 |
| **Total Sum** | 12.000 |
| **Mean μ (Average)** | 1.333 |
| **Maximum** | 3.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.444 |
| **Standard Deviation σ** | 0.667 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
