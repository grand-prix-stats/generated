---
title: Rank of Formula 1® Drivers by Number of Wins at Hockenheimring
layout: page
collectionName: circuits
collectionId: hockenheimring
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
            "borderWidth": 1,
            "data": [
                4.0,
                3.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                2.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Wins"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Ayrton Senna",
        "Fernando Alonso",
        "Nelson Piquet",
        "Alain Prost",
        "Gerhard Berger",
        "Lewis Hamilton",
        "Nigel Mansell",
        "Alan Jones",
        "Damon Hill",
        "Eddie Irvine",
        "Jacques Laffite",
        "Jochen Rindt",
        "Juan Pablo Montoya",
        "Mario Andretti",
        "Mika Häkkinen",
        "Nico Rosberg",
        "Niki Lauda",
        "Patrick Tambay",
        "Ralf Schumacher",
        "René Arnoux",
        "Rubens Barrichello"
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
| 1. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 4 |
| 2. | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 3 |
| 3. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 3 |
| 4. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 3 |
| 5. | [Alain Prost 🇫🇷](/f1/drivers/prost) | 2 |
| 6. | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 2 |
| 7. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2 |
| 8. | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 2 |
| 9. | [Alan Jones 🇦🇺](/f1/drivers/jones) | 1 |
| 10. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 1 |
| 11. | [Eddie Irvine 🇬🇧](/f1/drivers/irvine) | 1 |
| 12. | [Jacques Laffite 🇫🇷](/f1/drivers/laffite) | 1 |
| 13. | [Jochen Rindt 🇦🇹](/f1/drivers/rindt) | 1 |
| 14. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 1 |
| 15. | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | 1 |
| 16. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 1 |
| 17. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 1 |
| 18. | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | 1 |
| 19. | [Patrick Tambay 🇫🇷](/f1/drivers/tambay) | 1 |
| 20. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 |
| 21. | [René Arnoux 🇫🇷](/f1/drivers/arnoux) | 1 |
| 22. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 1 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 22 |
| **Total Sum** | 35.000 |
| **Mean μ (Average)** | 1.591 |
| **Maximum** | 4.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.787 |
| **Standard Deviation σ** | 0.887 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
