---
title: Rank of Formula 1® Drivers by Number of Laps Led at Bahrain International Circuit
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
  "labels" : [
    "Sebastian Vettel",
    "Lewis Hamilton",
    "Felipe Massa",
    "Fernando Alonso",
    "Michael Schumacher",
    "Nico Rosberg",
    "Jenson Button",
    "Valtteri Bottas",
    "Kimi Räikkönen",
    "Timo Glock",
    "Rubens Barrichello",
    "Jarno Trulli",
    "Juan Pablo Montoya",
    "Nick Heidfeld",
    "Paul di Resta",
    "Robert Kubica",
    "Romain Grosjean"
  ],
  "datasets" : [
    {
      "label" : "Number Of Laps Led",
      "data" : [
        182,
        116,
        102,
        96,
        77,
        62,
        38,
        13,
        12,
        10,
        6,
        4,
        4,
        4,
        4,
        2,
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
| 1. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 182 |
| 2. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 116 |
| 3. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 102 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 96 |
| 5. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 77 |
| 6. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 62 |
| 7. | [Jenson Button 🇬🇧](/f1/drivers/button) | 38 |
| 8. | [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 13 |
| 9. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 12 |
| 10. | [Timo Glock 🇩🇪](/f1/drivers/glock) | 10 |
| 11. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 6 |
| 12. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 4 |
| 13. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 4 |
| 14. | [Nick Heidfeld 🇩🇪](/f1/drivers/heidfeld) | 4 |
| 15. | [Paul di Resta 🇬🇧](/f1/drivers/resta) | 4 |
| 16. | [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 2 |
| 17. | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 1 |

#### Statistic Summary

| **Column** | **Number Of Laps Led** |
| **Row Count** | 17 |
| **Total Sum** | 733.000 |
| **Mean μ (Average)** | 43.118 |
| **Maximum** | 182.000 |
| **75th Percentile** | 77.000 |
| **Median** | 12.000 |
| **25th Percentile** | 4.000 |
| **Minimum** | 1.000 |
| **Variance** | 2725.280 |
| **Standard Deviation σ** | 52.204 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
