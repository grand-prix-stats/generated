---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Yas Marina Circuit
layout: page
collectionName: circuits
collectionId: yas_marina
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
    "Sebastian Vettel",
    "Lewis Hamilton",
    "Daniel Ricciardo",
    "Fernando Alonso",
    "Mark Webber"
  ],
  "datasets" : [
    {
      "label" : "Number Of Fastest Laps",
      "data" : [
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

| # | Driver | Number Of Fastest Laps |
|--|--|--|
| 1. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 3 |
| 2. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2 |
| 3. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 1 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1 |
| 5. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 1 |

#### Statistic Summary

| **Column** | **Number Of Fastest Laps** |
| **Row Count** | 5 |
| **Total Sum** | 8.000 |
| **Mean μ (Average)** | 1.600 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.640 |
| **Standard Deviation σ** | 0.800 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})