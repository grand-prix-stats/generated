---
title: Rank of Formula 1® Drivers by Number of Wins at Circuit Paul Ricard
layout: page
collectionName: circuits
collectionId: ricard
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
    "Alain Prost",
    "Nigel Mansell",
    "Alan Jones",
    "Jackie Stewart",
    "James Hunt",
    "Mario Andretti",
    "Nelson Piquet",
    "Niki Lauda",
    "René Arnoux",
    "Ronnie Peterson"
  ],
  "datasets" : [
    {
      "label" : "Number Of Wins",
      "data" : [
        4,
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
| 1. | [Alain Prost 🇫🇷](/f1/drivers/prost) | 4 |
| 2. | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 2 |
| 3. | [Alan Jones 🇦🇺](/f1/drivers/jones) | 1 |
| 4. | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | 1 |
| 5. | [James Hunt 🇬🇧](/f1/drivers/hunt) | 1 |
| 6. | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | 1 |
| 7. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 1 |
| 8. | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | 1 |
| 9. | [René Arnoux 🇫🇷](/f1/drivers/arnoux) | 1 |
| 10. | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 10 |
| **Total Sum** | 14.000 |
| **Mean μ (Average)** | 1.400 |
| **Maximum** | 4.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.840 |
| **Standard Deviation σ** | 0.917 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
