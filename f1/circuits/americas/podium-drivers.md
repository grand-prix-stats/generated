---
title: Rank of Formula 1® Drivers by Number of Podiums at Circuit of the Americas
layout: page
collectionName: circuits
collectionId: americas
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
    "Nico Rosberg",
    "Sebastian Vettel",
    "Daniel Ricciardo",
    "Fernando Alonso",
    "Mark Webber",
    "Romain Grosjean"
  ],
  "datasets" : [
    {
      "label" : "Number Of Podiums",
      "data" : [
        4,
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
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 |
| 2. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 3 |
| 3. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 3 |
| 4. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 2 |
| 5. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1 |
| 6. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 1 |
| 7. | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 1 |

#### Statistic Summary

| **Column** | **Number Of Podiums** |
| **Row Count** | 7 |
| **Total Sum** | 15.000 |
| **Mean μ (Average)** | 2.143 |
| **Maximum** | 4.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.265 |
| **Standard Deviation σ** | 1.125 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
