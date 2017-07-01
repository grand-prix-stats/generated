---
title: Rank of Formula 1® Drivers by Number of Wins at Reims-Gueux
layout: page
collectionName: circuits
collectionId: reims
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
    "Juan Fangio",
    "Jack Brabham",
    "Mike Hawthorn",
    "Giancarlo Baghetti",
    "Jim Clark",
    "Luigi Fagioli",
    "Peter Collins",
    "Tony Brooks"
  ],
  "datasets" : [
    {
      "label" : "Number Of Wins",
      "data" : [
        3,
        2,
        2,
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
| 1. | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 3 |
| 2. | [Jack Brabham 🇦🇺](/f1/drivers/jack_brabham) | 2 |
| 3. | [Mike Hawthorn 🇬🇧](/f1/drivers/hawthorn) | 2 |
| 4. | [Giancarlo Baghetti 🇮🇹](/f1/drivers/baghetti) | 1 |
| 5. | [Jim Clark 🇬🇧](/f1/drivers/clark) | 1 |
| 6. | [Luigi Fagioli 🇮🇹](/f1/drivers/fagioli) | 1 |
| 7. | [Peter Collins 🇬🇧](/f1/drivers/collins) | 1 |
| 8. | [Tony Brooks 🇬🇧](/f1/drivers/brooks) | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 8 |
| **Total Sum** | 12.000 |
| **Mean μ (Average)** | 1.500 |
| **Maximum** | 3.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.500 |
| **Standard Deviation σ** | 0.707 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
