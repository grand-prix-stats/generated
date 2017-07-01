---
title: Rank of Formula 1® Seasons by Number of Constructor's Championship Leaders
layout: page
collectionName: 
collectionId: 
---



<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
  "labels" : [
    "1983",
    "1958",
    "2010",
    "2008",
    "2003",
    "1962",
    "1997",
    "1964",
    "1986",
    "1966",
    "1985",
    "1982",
    "1970",
    "1975",
    "1972",
    "1973",
    "1974",
    "1971",
    "2014",
    "1977",
    "2013",
    "1979",
    "1980",
    "2012",
    "2006",
    "2005",
    "1961",
    "1967",
    "1965",
    "1987",
    "2017",
    "1989",
    "2002",
    "1991",
    "2000",
    "1993",
    "1994",
    "1995",
    "1999",
    "1963",
    "1998",
    "1996",
    "1992",
    "2001",
    "1990",
    "1984",
    "2004",
    "1968",
    "1969",
    "2007",
    "1960",
    "2009",
    "1959",
    "2011",
    "1981",
    "1978",
    "1976",
    "2015",
    "2016",
    "1988"
  ],
  "datasets" : [
    {
      "label" : "Constructors Championship Leaders",
      "data" : [
        4,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        3,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        2,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
        1,
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

| # | Year | Constructors Championship Leaders |
|--|--|--|
| 1. | 1983 | 4 |
| 2. | 1958 | 3 |
| 3. | 2010 | 3 |
| 4. | 2008 | 3 |
| 5. | 2003 | 3 |
| 6. | 1962 | 3 |
| 7. | 1997 | 3 |
| 8. | 1964 | 3 |
| 9. | 1986 | 3 |
| 10. | 1966 | 3 |
| 11. | 1985 | 3 |
| 12. | 1982 | 3 |
| 13. | 1970 | 3 |
| 14. | 1975 | 3 |
| 15. | 1972 | 3 |
| 16. | 1973 | 2 |
| 17. | 1974 | 2 |
| 18. | 1971 | 2 |
| 19. | 2014 | 2 |
| 20. | 1977 | 2 |
| 21. | 2013 | 2 |
| 22. | 1979 | 2 |
| 23. | 1980 | 2 |
| 24. | 2012 | 2 |
| 25. | 2006 | 2 |
| 26. | 2005 | 2 |
| 27. | 1961 | 2 |
| 28. | 1967 | 2 |
| 29. | 1965 | 2 |
| 30. | 1987 | 2 |
| 31. | 2017 | 2 |
| 32. | 1989 | 2 |
| 33. | 2002 | 2 |
| 34. | 1991 | 2 |
| 35. | 2000 | 2 |
| 36. | 1993 | 2 |
| 37. | 1994 | 2 |
| 38. | 1995 | 2 |
| 39. | 1999 | 2 |
| 40. | 1963 | 2 |
| 41. | 1998 | 1 |
| 42. | 1996 | 1 |
| 43. | 1992 | 1 |
| 44. | 2001 | 1 |
| 45. | 1990 | 1 |
| 46. | 1984 | 1 |
| 47. | 2004 | 1 |
| 48. | 1968 | 1 |
| 49. | 1969 | 1 |
| 50. | 2007 | 1 |
| 51. | 1960 | 1 |
| 52. | 2009 | 1 |
| 53. | 1959 | 1 |
| 54. | 2011 | 1 |
| 55. | 1981 | 1 |
| 56. | 1978 | 1 |
| 57. | 1976 | 1 |
| 58. | 2015 | 1 |
| 59. | 2016 | 1 |
| 60. | 1988 | 1 |

#### Statistic Summary

| **Column** | **Constructors Championship Leaders** |
| **Row Count** | 60 |
| **Total Sum** | 116.000 |
| **Mean μ (Average)** | 1.933 |
| **Maximum** | 4.000 |
| **75th Percentile** | 3.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.629 |
| **Standard Deviation σ** | 0.793 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})