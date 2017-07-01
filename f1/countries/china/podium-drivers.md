---
title: List of All Formula 1® Drivers that Have Been in the Podium in China by Number of Times
layout: page
collectionName: countries
collectionId: china
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
    "Fernando Alonso",
    "Kimi Räikkönen",
    "Nico Rosberg",
    "Sebastian Vettel",
    "Jenson Button",
    "Felipe Massa",
    "Mark Webber",
    "Daniil Kvyat",
    "Giancarlo Fisichella",
    "Max Verstappen",
    "Michael Schumacher",
    "Ralf Schumacher",
    "Rubens Barrichello"
  ],
  "datasets" : [
    {
      "label" : "Times",
      "data" : [
        8,
        5,
        5,
        5,
        5,
        4,
        2,
        2,
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

| # | Driver | Times |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 8 |
| 2. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 5 |
| 3. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 5 |
| 4. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 5 |
| 5. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 5 |
| 6. | [Jenson Button 🇬🇧](/f1/drivers/button) | 4 |
| 7. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 2 |
| 8. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 2 |
| 9. | [Daniil Kvyat 🇷🇺](/f1/drivers/kvyat) | 1 |
| 10. | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 1 |
| 11. | [Max Verstappen 🇳🇱](/f1/drivers/max_verstappen) | 1 |
| 12. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1 |
| 13. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 1 |
| 14. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 14 |
| **Total Sum** | 42.000 |
| **Mean μ (Average)** | 3.000 |
| **Maximum** | 8.000 |
| **75th Percentile** | 5.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 4.857 |
| **Standard Deviation σ** | 2.204 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
