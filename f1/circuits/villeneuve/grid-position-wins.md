---
title: Rank of Grid Position by Number of Wins at Circuit Gilles Villeneuve
layout: page
collectionName: circuits
collectionId: villeneuve
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
    "6",
    "4",
    "7",
    "5",
    "8",
    "10",
    "9",
    "11",
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
    "24",
    "25",
    "26"
  ],
  "datasets" : [
    {
      "label" : "Number Of Wins",
      "data" : [
        18,
        6,
        4,
        3,
        2,
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
| 1. | 1 | 18 |
| 2. | 2 | 6 |
| 3. | 3 | 4 |
| 4. | 6 | 3 |
| 5. | 4 | 2 |
| 6. | 7 | 2 |
| 7. | 5 | 1 |
| 8. | 8 | 1 |
| 9. | 10 | 1 |
| 10. | 9 | 0 |
| 11. | 11 | 0 |
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
| 25. | 25 | 0 |
| 26. | 26 | 0 |

#### Statistic Summary

| **Column** | **Number Of Wins** |
| **Row Count** | 26 |
| **Total Sum** | 38.000 |
| **Mean μ (Average)** | 1.462 |
| **Maximum** | 18.000 |
| **75th Percentile** | 1.000 |
| **Median** |  |
| **25th Percentile** |  |
| **Minimum** |  |
| **Variance** | 13.095 |
| **Standard Deviation σ** | 3.619 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})