---
title: Rank of Formula 1® Constructor Teams by Number of Points
layout: page
collectionName: 
collectionId: 
---



<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
  "labels" : [
    "Ferrari",
    "McLaren",
    "Red Bull",
    "Williams",
    "Mercedes",
    "Renault",
    "Team Lotus",
    "Force India",
    "Benetton",
    "Tyrrell",
    "Lotus F1",
    "Brabham",
    "BRM",
    "Sauber",
    "Ligier",
    "Toro Rosso",
    "Cooper-Climax",
    "Maserati",
    "BMW Sauber",
    "Jordan",
    "Lotus-Climax",
    "Toyota",
    "BAR",
    "Alfa Romeo",
    "Lotus-Ford",
    "Brabham-Repco",
    "Brawn",
    "Honda",
    "March",
    "McLaren-Ford",
    "Arrows",
    "Kurtis Kraft",
    "Matra-Ford",
    "Vanwall",
    "Cooper-Maserati",
    "Wolf",
    "Brabham-Climax",
    "Brabham-Ford",
    "Shadow",
    "Matra",
    "Surtees",
    "Cooper",
    "Haas F1 Team",
    "Porsche",
    "Jaguar",
    "Hesketh",
    "Stewart",
    "Epperly",
    "Fittipaldi",
    "Minardi",
    "March-Ford",
    "Watson",
    "Prost",
    "Lotus-BRM",
    "Lola",
    "Toleman",
    "Footwork",
    "Gordini",
    "Talbot-Lago",
    "Penske",
    "Larrousse",
    "Kuzma",
    "Cooper-BRM",
    "Ensign",
    "Brabham-Alfa Romeo",
    "Connaught",
    "Dallara",
    "Brabham-BRM",
    "Eagle-Weslake",
    "BRP",
    "Deidt",
    "Lesovsky",
    "Shadow-Ford",
    "Lancia",
    "Leyton House",
    "ATS",
    "Phillips",
    "Iso Marlboro",
    "McLaren-BRM",
    "Onyx",
    "Parnelli",
    "Rial",
    "Osella",
    "Simca",
    "Eagle-Climax",
    "Super Aguri",
    "Cooper-Castellotti",
    "Embassy Hill",
    "Frazer Nash",
    "Sherman",
    "AGS",
    "HWM",
    "Marussia",
    "Schroeder",
    "Zakspeed",
    "Manor Marussia",
    "McLaren-Serenissima",
    "Spyker",
    "Tecno",
    "Trevis"
  ],
  "datasets" : [
    {
      "label" : "Points",
      "data" : [
        7787.77,
        5286.5,
        3657.5,
        3513,
        3439.14,
        1344,
        995,
        879,
        861.5,
        711,
        706,
        631,
        537.5,
        509,
        388,
        362,
        336.5,
        313.14,
        308,
        291,
        281,
        278.5,
        227,
        217,
        209,
        175,
        172,
        156,
        148,
        143,
        142,
        130,
        130,
        108,
        83,
        79,
        78,
        68,
        59,
        54,
        54,
        52,
        50,
        50,
        49,
        48,
        47,
        44,
        44,
        38,
        37,
        36,
        35,
        29,
        27,
        26,
        25,
        25,
        25,
        23,
        22,
        21,
        20,
        19,
        18,
        17,
        15,
        13,
        13,
        11,
        10,
        10,
        9.5,
        9,
        8,
        7,
        7,
        6,
        6,
        6,
        6,
        6,
        5,
        5,
        4,
        4,
        3,
        3,
        3,
        3,
        2,
        2,
        2,
        2,
        2,
        1,
        1,
        1,
        1,
        1
      ],
      "borderColor" : [
        "16191A",
        "0D1D20",
        "FDCC2F",
        "082957",
        "D7D7D5",
        "424B52",
        "444444",
        "C81625",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "A17A5D",
        "444444",
        "FC181D",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "4D4E52",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444"
      ],
      "borderWidth" : 1,
      "backgroundColor" : [
        "EB212E",
        "FCA13B",
        "121D32",
        "EAE4ED",
        "18A19B",
        "FDE139",
        "09630C",
        "F6AFC1",
        "73C2FB",
        "274B72",
        "F6CA46",
        "243F73",
        "144D44",
        "0736A5",
        "0F5DBB",
        "2039C3",
        "273027",
        "C0BEC3",
        "20359D",
        "FFFF01",
        "025839",
        "D70028",
        "FFFFFF",
        "B21827",
        "025839",
        "243F73",
        "E2F833",
        "FFFFFF",
        "E53524",
        "AAAAAA",
        "FFA500",
        "D33949",
        "3FB2B3",
        "336667",
        "1A2446",
        "A3805E",
        "243F73",
        "07316F",
        "FA9B27",
        "888888",
        "888888",
        "273027",
        "CF0F18",
        "DDDDDD",
        "095921",
        "FFFFFF",
        "FFFFFF",
        "DBC75F",
        "888888",
        "1B1D1D",
        "888888",
        "FC8881",
        "0D1773",
        "457439",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "2077C9",
        "888888",
        "C4333B",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "1A284B",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "E30010",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "888888",
        "5E0A16",
        "888888",
        "888888",
        "5E0A16",
        "888888",
        "FFA500",
        "888888",
        "888888"
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

| # | Constructor | Points |
|--|--|--|
| 1. | Ferrari 🇮🇹 | 7787.77 |
| 2. | McLaren 🇬🇧 | 5286.5 |
| 3. | Red Bull 🇦🇹 | 3657.5 |
| 4. | Williams 🇬🇧 | 3513.0 |
| 5. | Mercedes 🇩🇪 | 3439.14 |
| 6. | Renault 🇫🇷 | 1344.0 |
| 7. | Team Lotus 🇬🇧 | 995.0 |
| 8. | Force India 🇮🇳 | 879.0 |
| 9. | Benetton 🇮🇹 | 861.5 |
| 10. | Tyrrell 🇬🇧 | 711.0 |
| 11. | Lotus F1 🇬🇧 | 706.0 |
| 12. | Brabham 🇬🇧 | 631.0 |
| 13. | BRM 🇬🇧 | 537.5 |
| 14. | Sauber 🇨🇭 | 509.0 |
| 15. | Ligier 🇫🇷 | 388.0 |
| 16. | Toro Rosso 🇮🇹 | 362.0 |
| 17. | Cooper-Climax 🇬🇧 | 336.5 |
| 18. | Maserati 🇮🇹 | 313.14 |
| 19. | BMW Sauber 🇩🇪 | 308.0 |
| 20. | Jordan 🇮🇪 | 291.0 |
| 21. | Lotus-Climax 🇬🇧 | 281.0 |
| 22. | Toyota 🇯🇵 | 278.5 |
| 23. | BAR 🇬🇧 | 227.0 |
| 24. | Alfa Romeo 🇮🇹 | 217.0 |
| 25. | Lotus-Ford 🇬🇧 | 209.0 |
| 26. | Brabham-Repco 🇬🇧 | 175.0 |
| 27. | Brawn 🇬🇧 | 172.0 |
| 28. | Honda 🇯🇵 | 156.0 |
| 29. | March 🇬🇧 | 148.0 |
| 30. | McLaren-Ford 🇬🇧 | 143.0 |
| 31. | Arrows 🇬🇧 | 142.0 |
| 32. | Kurtis Kraft 🇺🇸 | 130.0 |
| 33. | Matra-Ford 🇫🇷 | 130.0 |
| 34. | Vanwall 🇬🇧 | 108.0 |
| 35. | Cooper-Maserati 🇬🇧 | 83.0 |
| 36. | Wolf 🇨🇦 | 79.0 |
| 37. | Brabham-Climax 🇬🇧 | 78.0 |
| 38. | Brabham-Ford 🇬🇧 | 68.0 |
| 39. | Shadow 🇬🇧 | 59.0 |
| 40. | Matra 🇫🇷 | 54.0 |
| 41. | Surtees 🇬🇧 | 54.0 |
| 42. | Cooper 🇬🇧 | 52.0 |
| 43. | Haas F1 Team 🇺🇸 | 50.0 |
| 44. | Porsche 🇩🇪 | 50.0 |
| 45. | Jaguar 🇬🇧 | 49.0 |
| 46. | Hesketh 🇬🇧 | 48.0 |
| 47. | Stewart 🇬🇧 | 47.0 |
| 48. | Epperly 🇺🇸 | 44.0 |
| 49. | Fittipaldi 🇧🇷 | 44.0 |
| 50. | Minardi 🇮🇹 | 38.0 |
| 51. | March-Ford 🇬🇧 | 37.0 |
| 52. | Watson 🇺🇸 | 36.0 |
| 53. | Prost 🇫🇷 | 35.0 |
| 54. | Lotus-BRM 🇬🇧 | 29.0 |
| 55. | Lola 🇬🇧 | 27.0 |
| 56. | Toleman 🇬🇧 | 26.0 |
| 57. | Footwork 🇬🇧 | 25.0 |
| 58. | Gordini 🇫🇷 | 25.0 |
| 59. | Talbot-Lago 🇫🇷 | 25.0 |
| 60. | Penske 🇺🇸 | 23.0 |
| 61. | Larrousse 🇫🇷 | 22.0 |
| 62. | Kuzma 🇺🇸 | 21.0 |
| 63. | Cooper-BRM 🇬🇧 | 20.0 |
| 64. | Ensign 🇬🇧 | 19.0 |
| 65. | Brabham-Alfa Romeo 🇬🇧 | 18.0 |
| 66. | Connaught 🇬🇧 | 17.0 |
| 67. | Dallara 🇮🇹 | 15.0 |
| 68. | Brabham-BRM 🇬🇧 | 13.0 |
| 69. | Eagle-Weslake 🇺🇸 | 13.0 |
| 70. | BRP 🇬🇧 | 11.0 |
| 71. | Deidt 🇺🇸 | 10.0 |
| 72. | Lesovsky 🇺🇸 | 10.0 |
| 73. | Shadow-Ford 🇬🇧 | 9.5 |
| 74. | Lancia 🇮🇹 | 9.0 |
| 75. | Leyton House 🇬🇧 | 8.0 |
| 76. | ATS 🇮🇹 | 7.0 |
| 77. | Phillips 🇺🇸 | 7.0 |
| 78. | Iso Marlboro 🇬🇧 | 6.0 |
| 79. | McLaren-BRM 🇬🇧 | 6.0 |
| 80. | Onyx 🇬🇧 | 6.0 |
| 81. | Parnelli 🇺🇸 | 6.0 |
| 82. | Rial 🇩🇪 | 6.0 |
| 83. | Osella 🇮🇹 | 5.0 |
| 84. | Simca 🇫🇷 | 5.0 |
| 85. | Eagle-Climax 🇺🇸 | 4.0 |
| 86. | Super Aguri 🇯🇵 | 4.0 |
| 87. | Cooper-Castellotti 🇬🇧 | 3.0 |
| 88. | Embassy Hill 🇬🇧 | 3.0 |
| 89. | Frazer Nash 🇬🇧 | 3.0 |
| 90. | Sherman 🇺🇸 | 3.0 |
| 91. | AGS 🇫🇷 | 2.0 |
| 92. | HWM 🇬🇧 | 2.0 |
| 93. | Marussia 🇷🇺 | 2.0 |
| 94. | Schroeder 🇺🇸 | 2.0 |
| 95. | Zakspeed 🇩🇪 | 2.0 |
| 96. | Manor Marussia 🇬🇧 | 1.0 |
| 97. | McLaren-Serenissima 🇬🇧 | 1.0 |
| 98. | Spyker 🇳🇱 | 1.0 |
| 99. | Tecno 🇮🇹 | 1.0 |
| 100. | Trevis 🇺🇸 | 1.0 |

#### Statistic Summary

| **Column** | **Points** |
| **Row Count** | 100 |
| **Total Sum** | 36862.550 |
| **Mean μ (Average)** | 368.626 |
| **Maximum** | 7787.770 |
| **75th Percentile** | 209.000 |
| **Median** | 38.000 |
| **25th Percentile** | 8.000 |
| **Minimum** | 1.000 |
| **Variance** | 1200446.510 |
| **Standard Deviation σ** | 1095.649 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
