---
title: Rank of Grid Position by Number of Wins at Albert Park Grand Prix Circuit
layout: page
collectionName: circuits
collectionId: albert_park
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
    "1",
    "2",
    "3",
    "4",
    "6",
    "7",
    "11",
    "5",
    "8",
    "9",
    "10",
    "12",
    "13",
    "14",
    "15",
    "16",
    "17",
    "18",
    "19",
    "20",
    "21",
    "22",
    "23",
    "24"
  ],
  "datasets" : [
    {
      "label" : "Number Of Wins",
      "data" : [
        9,
        5,
        3,
        2,
        1,
        1,
        1,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0,
        0
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

| # | Grid Position | Number Of Wins |
|--|--|--|
| 1. | 1 | 9 |
| 2. | 2 | 5 |
| 3. | 3 | 3 |
| 4. | 4 | 2 |
| 5. | 6 | 1 |
| 6. | 7 | 1 |
| 7. | 11 | 1 |
| 8. | 5 | 0 |
| 9. | 8 | 0 |
| 10. | 9 | 0 |
| 11. | 10 | 0 |
| 12. | 12 | 0 |
| 13. | 13 | 0 |
| 14. | 14 | 0 |
| 15. | 15 | 0 |
| 16. | 16 | 0 |
| 17. | 17 | 0 |
| 18. | 18 | 0 |
| 19. | 19 | 0 |
| 20. | 20 | 0 |
| 21. | 21 | 0 |
| 22. | 22 | 0 |
| 23. | 23 | 0 |
| 24. | 24 | 0 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 24 |
| **Total Sum** | 22.000 |
| **Mean μ (Average)** | 0.917 |
| **Maximum** | 9.000 |
| **75th Percentile** | 1.000 |
| **Median** |  |
| **25th Percentile** |  |
| **Minimum** |  |
| **Variance** | 4.243 |
| **Standard Deviation σ** | 2.060 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
