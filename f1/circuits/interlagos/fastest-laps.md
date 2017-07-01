---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Autódromo José Carlos Pace
layout: page
collectionName: circuits
collectionId: interlagos
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
    "Mark Webber",
    "Kimi Räikkönen",
    "Felipe Massa",
    "Juan Pablo Montoya",
    "Max Verstappen",
    "Michael Schumacher"
  ],
  "datasets" : [
    {
      "label" : "Number Of Fastest Laps",
      "data" : [
        4,
        3,
        2,
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

| # | Driver | Number Of Fastest Laps |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 4 |
| 2. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 3 |
| 3. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 |
| 4. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 1 |
| 5. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 1 |
| 6. | [Max Verstappen 🇳🇱](/f1/drivers/max_verstappen) | 1 |
| 7. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 |

#### Statistic Summary

| **Column** | **Number Of Fastest Laps** |
| **Row Count** | 7 |
| **Total Sum** | 13.000 |
| **Mean μ (Average)** | 1.857 |
| **Maximum** | 4.000 |
| **75th Percentile** | 3.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 1.265 |
| **Standard Deviation σ** | 1.125 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
