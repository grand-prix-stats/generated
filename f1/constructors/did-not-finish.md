---
title: Rank of Formula 1® Constructor Teams by Number of DNF (Did Not Finish)
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
    "Williams",
    "Team Lotus",
    "Tyrrell",
    "Minardi",
    "Brabham",
    "Arrows",
    "Ligier",
    "BRM",
    "March",
    "Sauber",
    "Renault",
    "Jordan",
    "Maserati",
    "Benetton",
    "Alfa Romeo",
    "Osella",
    "Toro Rosso",
    "Larrousse",
    "Surtees",
    "Kurtis Kraft",
    "BAR",
    "Cooper-Climax",
    "Footwork",
    "Shadow",
    "Lola",
    "Red Bull",
    "Toyota",
    "Jaguar",
    "Lotus-Climax",
    "Prost",
    "ATS",
    "Dallara",
    "Cooper-Maserati",
    "Ensign",
    "Toleman",
    "Force India",
    "Lotus-Ford",
    "Gordini",
    "Zakspeed",
    "Stewart",
    "Lotus-BRM",
    "Fittipaldi",
    "Honda",
    "Mercedes",
    "Brabham-Climax",
    "Vanwall",
    "Cooper",
    "RAM",
    "Talbot-Lago",
    "Brabham-Alfa Romeo",
    "Forti",
    "Lotus F1",
    "Leyton House",
    "Wolf",
    "McLaren-Ford",
    "Pacific",
    "Brabham-Repco",
    "Connaught",
    "Hesketh",
    "HRT",
    "Super Aguri",
    "Iso Marlboro",
    "AGS",
    "Matra",
    "Virgin",
    "HWM",
    "March-Ford",
    "Brabham-Ford",
    "Caterham",
    "Lotus",
    "Simtek",
    "BMW Sauber",
    "Fondmetal",
    "Simca",
    "Eagle-Weslake",
    "Penske",
    "Onyx",
    "Brabham-BRM",
    "Shadow-Ford",
    "Kuzma",
    "Porsche",
    "Haas F1 Team",
    "Marussia",
    "Spirit",
    "Spyker",
    "Cooper-BRM",
    "Euro Brun",
    "MF1",
    "Manor Marussia",
    "Matra-Ford",
    "Rial",
    "Veritas",
    "Coloni",
    "Merzario",
    "De Tomaso",
    "Tecno",
    "BRP",
    "Eagle-Climax",
    "ERA",
    "Lancia",
    "McLaren-BRM",
    "Parnelli",
    "Watson",
    "Embassy Hill",
    "Lesovsky",
    "Schroeder",
    "Scirocco",
    "AFM",
    "Aston Martin",
    "Bromme",
    "Deidt",
    "March-Alfa Romeo",
    "Alta",
    "Boro",
    "Pawl",
    "Scarab",
    "BMW",
    "Emeryson"
  ],
  "datasets" : [
    {
      "label" : "Did Not Finish",
      "data" : [
        619,
        475,
        393,
        390,
        390,
        339,
        315,
        276,
        269,
        266,
        243,
        235,
        224,
        218,
        212,
        183,
        139,
        131,
        111,
        110,
        104,
        102,
        97,
        92,
        90,
        89,
        88,
        82,
        78,
        75,
        75,
        75,
        74,
        71,
        68,
        68,
        68,
        66,
        66,
        62,
        60,
        58,
        57,
        54,
        50,
        50,
        44,
        43,
        40,
        40,
        40,
        39,
        39,
        39,
        37,
        37,
        36,
        36,
        35,
        34,
        34,
        33,
        30,
        29,
        27,
        27,
        27,
        25,
        25,
        24,
        24,
        23,
        23,
        20,
        20,
        20,
        18,
        18,
        17,
        16,
        16,
        15,
        15,
        14,
        14,
        14,
        14,
        13,
        12,
        12,
        11,
        11,
        11,
        11,
        10,
        10,
        9,
        9,
        8,
        8,
        8,
        8,
        8,
        8,
        8,
        7,
        6,
        6,
        6,
        5,
        5,
        5,
        5,
        5,
        4,
        4,
        4,
        4,
        3,
        3
      ],
      "borderColor" : [
        "16191A",
        "0D1D20",
        "082957",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "A17A5D",
        "424B52",
        "444444",
        "444444",
        "444444",
        "444444",
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
        "FDCC2F",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "C81625",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "444444",
        "D7D7D5",
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
        "444444"
      ],
      "borderWidth" : 1,
      "backgroundColor" : [
        "EB212E",
        "FCA13B",
        "EAE4ED",
        "09630C",
        "274B72",
        "1B1D1D",
        "243F73",
        "FFA500",
        "0F5DBB",
        "144D44",
        "E53524",
        "0736A5",
        "FDE139",
        "FFFF01",
        "C0BEC3",
        "73C2FB",
        "B21827",
        "888888",
        "2039C3",
        "888888",
        "888888",
        "D33949",
        "FFFFFF",
        "273027",
        "888888",
        "FA9B27",
        "888888",
        "121D32",
        "D70028",
        "095921",
        "025839",
        "0D1773",
        "888888",
        "888888",
        "1A2446",
        "888888",
        "888888",
        "F6AFC1",
        "025839",
        "888888",
        "888888",
        "FFFFFF",
        "457439",
        "888888",
        "FFFFFF",
        "18A19B",
        "243F73",
        "336667",
        "273027",
        "888888",
        "888888",
        "888888",
        "888888",
        "F6CA46",
        "888888",
        "A3805E",
        "AAAAAA",
        "888888",
        "243F73",
        "888888",
        "FFFFFF",
        "BE9D56",
        "E30010",
        "888888",
        "888888",
        "888888",
        "F60002",
        "888888",
        "888888",
        "07316F",
        "124411",
        "006400",
        "888888",
        "20359D",
        "888888",
        "888888",
        "1A284B",
        "2077C9",
        "888888",
        "888888",
        "888888",
        "C4333B",
        "DDDDDD",
        "CF0F18",
        "5E0A16",
        "888888",
        "FFA500",
        "888888",
        "888888",
        "343434",
        "5E0A16",
        "3FB2B3",
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
        "FC8881",
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

| # | Constructor | Did Not Finish | % Of Total Participations |
|--|--|--|--|
| 1. | Ferrari 🇮🇹 | 619 | 29.25% |
| 2. | McLaren 🇬🇧 | 475 | 29.67% |
| 3. | Williams 🇬🇧 | 393 | 29.00% |
| 4. | Team Lotus 🇬🇧 | 390 | 44.78% |
| 5. | Tyrrell 🇬🇧 | 390 | 44.27% |
| 6. | Minardi 🇮🇹 | 339 | 50.45% |
| 7. | Brabham 🇬🇧 | 315 | 47.58% |
| 8. | Arrows 🇬🇧 | 276 | 46.78% |
| 9. | Ligier 🇫🇷 | 269 | 44.03% |
| 10. | BRM 🇬🇧 | 266 | 47.33% |
| 11. | March 🇬🇧 | 243 | 46.37% |
| 12. | Sauber 🇨🇭 | 235 | 32.55% |
| 13. | Renault 🇫🇷 | 224 | 34.73% |
| 14. | Jordan 🇮🇪 | 218 | 43.60% |
| 15. | Maserati 🇮🇹 | 212 | 48.62% |
| 16. | Benetton 🇮🇹 | 183 | 35.19% |
| 17. | Alfa Romeo 🇮🇹 | 139 | 56.97% |
| 18. | Osella 🇮🇹 | 131 | 51.98% |
| 19. | Toro Rosso 🇮🇹 | 111 | 25.93% |
| 20. | Larrousse 🇫🇷 | 110 | 50.93% |
| 21. | Surtees 🇬🇧 | 104 | 40.00% |
| 22. | Kurtis Kraft 🇺🇸 | 102 | 45.13% |
| 23. | BAR 🇬🇧 | 97 | 41.10% |
| 24. | Cooper-Climax 🇬🇧 | 92 | 34.33% |
| 25. | Footwork 🇬🇧 | 90 | 46.39% |
| 26. | Shadow 🇬🇧 | 89 | 42.18% |
| 27. | Lola 🇬🇧 | 88 | 53.33% |
| 28. | Red Bull 🇦🇹 | 82 | 17.60% |
| 29. | Toyota 🇯🇵 | 78 | 27.86% |
| 30. | Jaguar 🇬🇧 | 75 | 44.12% |
| 31. | Lotus-Climax 🇬🇧 | 75 | 32.47% |
| 32. | Prost 🇫🇷 | 75 | 45.45% |
| 33. | ATS 🇮🇹 | 74 | 45.68% |
| 34. | Dallara 🇮🇹 | 71 | 49.31% |
| 35. | Cooper-Maserati 🇬🇧 | 68 | 50.75% |
| 36. | Ensign 🇬🇧 | 68 | 44.16% |
| 37. | Toleman 🇬🇧 | 68 | 51.91% |
| 38. | Force India 🇮🇳 | 66 | 18.44% |
| 39. | Lotus-Ford 🇬🇧 | 66 | 51.56% |
| 40. | Gordini 🇫🇷 | 62 | 60.78% |
| 41. | Zakspeed 🇩🇪 | 60 | 45.11% |
| 42. | Stewart 🇬🇧 | 58 | 59.18% |
| 43. | Lotus-BRM 🇬🇧 | 57 | 47.11% |
| 44. | Fittipaldi 🇧🇷 | 54 | 34.84% |
| 45. | Honda 🇯🇵 | 50 | 32.89% |
| 46. | Mercedes 🇩🇪 | 50 | 15.15% |
| 47. | Brabham-Climax 🇬🇧 | 44 | 47.31% |
| 48. | Vanwall 🇬🇧 | 43 | 60.56% |
| 49. | Cooper 🇬🇧 | 40 | 38.83% |
| 50. | RAM 🇬🇧 | 40 | 56.34% |
| 51. | Talbot-Lago 🇫🇷 | 40 | 48.78% |
| 52. | Brabham-Alfa Romeo 🇬🇧 | 39 | 66.10% |
| 53. | Forti 🇮🇹 | 39 | 72.22% |
| 54. | Lotus F1 🇬🇧 | 39 | 25.32% |
| 55. | Leyton House 🇬🇧 | 37 | 57.81% |
| 56. | Wolf 🇨🇦 | 37 | 46.84% |
| 57. | McLaren-Ford 🇬🇧 | 36 | 41.38% |
| 58. | Pacific 🇬🇧 | 36 | 54.55% |
| 59. | Brabham-Repco 🇬🇧 | 35 | 45.45% |
| 60. | Connaught 🇬🇧 | 34 | 62.96% |
| 61. | Hesketh 🇬🇧 | 34 | 35.05% |
| 62. | HRT 🇪🇸 | 33 | 28.95% |
| 63. | Super Aguri 🇯🇵 | 30 | 38.46% |
| 64. | Iso Marlboro 🇬🇧 | 29 | 52.73% |
| 65. | AGS 🇫🇷 | 27 | 21.95% |
| 66. | Matra 🇫🇷 | 27 | 38.03% |
| 67. | Virgin 🇬🇧 | 27 | 35.53% |
| 68. | HWM 🇬🇧 | 25 | 53.19% |
| 69. | March-Ford 🇬🇧 | 25 | 58.14% |
| 70. | Brabham-Ford 🇬🇧 | 24 | 41.38% |
| 71. | Caterham 🇲🇾 | 24 | 21.43% |
| 72. | Lotus 🇲🇾 | 23 | 30.26% |
| 73. | Simtek 🇬🇧 | 23 | 57.50% |
| 74. | BMW Sauber 🇩🇪 | 20 | 14.29% |
| 75. | Fondmetal 🇮🇹 | 20 | 47.62% |
| 76. | Simca 🇫🇷 | 20 | 68.97% |
| 77. | Eagle-Weslake 🇺🇸 | 18 | 85.71% |
| 78. | Penske 🇺🇸 | 18 | 39.13% |
| 79. | Onyx 🇬🇧 | 17 | 32.69% |
| 80. | Brabham-BRM 🇬🇧 | 16 | 39.02% |
| 81. | Shadow-Ford 🇬🇧 | 16 | 61.54% |
| 82. | Kuzma 🇺🇸 | 15 | 38.46% |
| 83. | Porsche 🇩🇪 | 15 | 17.86% |
| 84. | Haas F1 Team 🇺🇸 | 14 | 24.14% |
| 85. | Marussia 🇷🇺 | 14 | 12.84% |
| 86. | Spirit 🇬🇧 | 14 | 56.00% |
| 87. | Spyker 🇳🇱 | 14 | 41.18% |
| 88. | Cooper-BRM 🇬🇧 | 13 | 61.90% |
| 89. | Euro Brun 🇮🇹 | 12 | 15.79% |
| 90. | MF1 🇷🇺 | 12 | 42.86% |
| 91. | Manor Marussia 🇬🇧 | 11 | 14.10% |
| 92. | Matra-Ford 🇫🇷 | 11 | 27.50% |
| 93. | Rial 🇩🇪 | 11 | 22.92% |
| 94. | Veritas 🇩🇪 | 11 | 61.11% |
| 95. | Coloni 🇮🇹 | 10 | 12.35% |
| 96. | Merzario 🇮🇹 | 10 | 31.25% |
| 97. | De Tomaso 🇮🇹 | 9 | 64.29% |
| 98. | Tecno 🇮🇹 | 9 | 81.82% |
| 99. | BRP 🇬🇧 | 8 | 42.11% |
| 100. | Eagle-Climax 🇺🇸 | 8 | 61.54% |
| 101. | ERA 🇬🇧 | 8 | 61.54% |
| 102. | Lancia 🇮🇹 | 8 | 72.73% |
| 103. | McLaren-BRM 🇬🇧 | 8 | 57.14% |
| 104. | Parnelli 🇺🇸 | 8 | 50.00% |
| 105. | Watson 🇺🇸 | 8 | 36.36% |
| 106. | Embassy Hill 🇬🇧 | 7 | 36.84% |
| 107. | Lesovsky 🇺🇸 | 6 | 40.00% |
| 108. | Schroeder 🇺🇸 | 6 | 75.00% |
| 109. | Scirocco 🇬🇧 | 6 | 35.29% |
| 110. | AFM 🇩🇪 | 5 | 71.43% |
| 111. | Aston Martin 🇬🇧 | 5 | 45.45% |
| 112. | Bromme 🇺🇸 | 5 | 100.00% |
| 113. | Deidt 🇺🇸 | 5 | 62.50% |
| 114. | March-Alfa Romeo 🇬🇧 | 5 | 55.56% |
| 115. | Alta 🇬🇧 | 4 | 66.67% |
| 116. | Boro 🇳🇱 | 4 | 50.00% |
| 117. | Pawl 🇺🇸 | 4 | 100.00% |
| 118. | Scarab 🇺🇸 | 4 | 44.44% |
| 119. | BMW 🇩🇪 | 3 | 50.00% |
| 120. | Emeryson 🇬🇧 | 3 | 27.27% |

#### Statistic Summary

| **Column** | **Did Not Finish** | **% Of Total Participations** |
| **Row Count** | 120 | 120 |
| **Total Sum** | 8825.000 | 5411.100 |
| **Mean μ (Average)** | 73.542 | 45.093 |
| **Maximum** | 619.000 | 100.000 |
| **75th Percentile** | 75.000 | 55.560 |
| **Median** | 34.000 | 45.130 |
| **25th Percentile** | 12.000 | 34.840 |
| **Minimum** | 3.000 | 12.350 |
| **Variance** | 11560.698 | 278.253 |
| **Standard Deviation σ** | 107.521 | 16.681 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
