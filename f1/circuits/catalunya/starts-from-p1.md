---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Circuit de Barcelona-Catalunya
layout: page
collectionName: circuits
collectionId: catalunya
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
                "#1D181E"
            ],
            "borderWidth": 1,
            "data": [
                7.0,
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
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "Michael Schumacher",
        "Lewis Hamilton",
        "Kimi Räikkönen",
        "Mark Webber",
        "Mika Häkkinen",
        "Nico Rosberg",
        "Alain Prost",
        "Damon Hill",
        "Felipe Massa",
        "Fernando Alonso",
        "Gerhard Berger",
        "Jacques Villeneuve",
        "Jenson Button",
        "Nigel Mansell",
        "Pastor Maldonado"
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

| # | Driver | Number Of Starts From P1 |
|--|--|--|
| 1. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 7 |
| 2. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 3 |
| 3. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 2 |
| 4. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 2 |
| 5. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 2 |
| 6. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 2 |
| 7. | [Alain Prost 🇫🇷](/f1/drivers/prost) | 1 |
| 8. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 1 |
| 9. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 1 |
| 10. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1 |
| 11. | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 1 |
| 12. | [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | 1 |
| 13. | [Jenson Button 🇬🇧](/f1/drivers/button) | 1 |
| 14. | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 1 |
| 15. | [Pastor Maldonado 🇻🇪](/f1/drivers/maldonado) | 1 |

#### Statistic Summary

| **Column** | **Number Of Starts From P1** |
| **Row Count** | 15 |
| **Total Sum** | 27.000 |
| **Mean μ (Average)** | 1.800 |
| **Maximum** | 7.000 |
| **75th Percentile** | 2.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 2.293 |
| **Standard Deviation σ** | 1.514 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
