---
title: Rank of Formula 1® Constructor Teams by Number of DNF (Did Not Finish)
layout: page
collectionName: 
collectionId: 
---



<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "EB212E",
                "FCA13B",
                "09630C",
                "274B72",
                "EAE4ED",
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
                "888888",
                "2039C3",
                "888888",
                "D33949",
                "FFFFFF",
                "273027",
                "888888",
                "FA9B27",
                "888888",
                "D70028",
                "121D32",
                "095921",
                "025839",
                "0D1773",
                "888888",
                "888888",
                "1A2446",
                "888888",
                "888888",
                "025839",
                "F6AFC1",
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
                "5E0A16",
                "888888",
                "FFA500",
                "888888",
                "888888",
                "CF0F18",
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
            ],
            "borderColor": [
                "16191A",
                "0D1D20",
                "444444",
                "444444",
                "082957",
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
                "444444"
            ],
            "borderWidth": 1,
            "data": [
                618.0,
                468.0,
                390.0,
                390.0,
                389.0,
                339.0,
                315.0,
                276.0,
                269.0,
                266.0,
                243.0,
                231.0,
                220.0,
                218.0,
                212.0,
                183.0,
                139.0,
                131.0,
                110.0,
                106.0,
                104.0,
                102.0,
                97.0,
                92.0,
                90.0,
                89.0,
                88.0,
                78.0,
                77.0,
                75.0,
                75.0,
                75.0,
                74.0,
                71.0,
                68.0,
                68.0,
                68.0,
                66.0,
                65.0,
                62.0,
                60.0,
                58.0,
                57.0,
                54.0,
                50.0,
                49.0,
                44.0,
                43.0,
                40.0,
                40.0,
                40.0,
                39.0,
                39.0,
                39.0,
                37.0,
                37.0,
                36.0,
                36.0,
                35.0,
                34.0,
                34.0,
                33.0,
                30.0,
                29.0,
                27.0,
                27.0,
                27.0,
                25.0,
                25.0,
                24.0,
                24.0,
                23.0,
                23.0,
                20.0,
                20.0,
                20.0,
                18.0,
                18.0,
                17.0,
                16.0,
                16.0,
                15.0,
                15.0,
                14.0,
                14.0,
                14.0,
                13.0,
                12.0,
                12.0,
                12.0,
                11.0,
                11.0,
                11.0,
                11.0,
                10.0,
                10.0,
                9.0,
                9.0,
                8.0,
                8.0,
                8.0,
                8.0,
                8.0,
                8.0,
                8.0,
                7.0,
                6.0,
                6.0,
                6.0,
                5.0,
                5.0,
                5.0,
                5.0,
                5.0,
                4.0,
                4.0,
                4.0,
                4.0,
                3.0,
                3.0
            ],
            "label": "Did Not Finish"
        }
    ],
    "labels": [
        "Ferrari",
        "McLaren",
        "Team Lotus",
        "Tyrrell",
        "Williams",
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
        "Larrousse",
        "Toro Rosso",
        "Surtees",
        "Kurtis Kraft",
        "BAR",
        "Cooper-Climax",
        "Footwork",
        "Shadow",
        "Lola",
        "Toyota",
        "Red Bull",
        "Jaguar",
        "Lotus-Climax",
        "Prost",
        "ATS",
        "Dallara",
        "Cooper-Maserati",
        "Ensign",
        "Toleman",
        "Lotus-Ford",
        "Force India",
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
        "Marussia",
        "Spirit",
        "Spyker",
        "Cooper-BRM",
        "Euro Brun",
        "Haas F1 Team",
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
| 1. | Ferrari 🇮🇹 | 618 | 29.40% |
| 2. | McLaren 🇬🇧 | 468 | 29.49% |
| 3. | Team Lotus 🇬🇧 | 390 | 44.78% |
| 4. | Tyrrell 🇬🇧 | 390 | 44.27% |
| 5. | Williams 🇬🇧 | 389 | 29.01% |
| 6. | Minardi 🇮🇹 | 339 | 50.45% |
| 7. | Brabham 🇬🇧 | 315 | 47.58% |
| 8. | Arrows 🇬🇧 | 276 | 46.78% |
| 9. | Ligier 🇫🇷 | 269 | 44.03% |
| 10. | BRM 🇬🇧 | 266 | 47.33% |
| 11. | March 🇬🇧 | 243 | 46.37% |
| 12. | Sauber 🇨🇭 | 231 | 32.63% |
| 13. | Renault 🇫🇷 | 220 | 34.87% |
| 14. | Jordan 🇮🇪 | 218 | 43.60% |
| 15. | Maserati 🇮🇹 | 212 | 48.62% |
| 16. | Benetton 🇮🇹 | 183 | 35.19% |
| 17. | Alfa Romeo 🇮🇹 | 139 | 56.97% |
| 18. | Osella 🇮🇹 | 131 | 51.98% |
| 19. | Larrousse 🇫🇷 | 110 | 50.93% |
| 20. | Toro Rosso 🇮🇹 | 106 | 25.60% |
| 21. | Surtees 🇬🇧 | 104 | 40.00% |
| 22. | Kurtis Kraft 🇺🇸 | 102 | 45.13% |
| 23. | BAR 🇬🇧 | 97 | 41.10% |
| 24. | Cooper-Climax 🇬🇧 | 92 | 34.33% |
| 25. | Footwork 🇬🇧 | 90 | 46.39% |
| 26. | Shadow 🇬🇧 | 89 | 42.18% |
| 27. | Lola 🇬🇧 | 88 | 53.33% |
| 28. | Toyota 🇯🇵 | 78 | 27.86% |
| 29. | Red Bull 🇦🇹 | 77 | 17.04% |
| 30. | Jaguar 🇬🇧 | 75 | 44.12% |
| 31. | Lotus-Climax 🇬🇧 | 75 | 32.47% |
| 32. | Prost 🇫🇷 | 75 | 45.45% |
| 33. | ATS 🇮🇹 | 74 | 45.68% |
| 34. | Dallara 🇮🇹 | 71 | 49.31% |
| 35. | Cooper-Maserati 🇬🇧 | 68 | 50.75% |
| 36. | Ensign 🇬🇧 | 68 | 44.16% |
| 37. | Toleman 🇬🇧 | 68 | 51.91% |
| 38. | Lotus-Ford 🇬🇧 | 66 | 51.56% |
| 39. | Force India 🇮🇳 | 65 | 18.90% |
| 40. | Gordini 🇫🇷 | 62 | 60.78% |
| 41. | Zakspeed 🇩🇪 | 60 | 45.11% |
| 42. | Stewart 🇬🇧 | 58 | 59.18% |
| 43. | Lotus-BRM 🇬🇧 | 57 | 47.11% |
| 44. | Fittipaldi 🇧🇷 | 54 | 34.84% |
| 45. | Honda 🇯🇵 | 50 | 32.89% |
| 46. | Mercedes 🇩🇪 | 49 | 15.51% |
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
| 84. | Marussia 🇷🇺 | 14 | 12.84% |
| 85. | Spirit 🇬🇧 | 14 | 56.00% |
| 86. | Spyker 🇳🇱 | 14 | 41.18% |
| 87. | Cooper-BRM 🇬🇧 | 13 | 61.90% |
| 88. | Euro Brun 🇮🇹 | 12 | 15.79% |
| 89. | Haas F1 Team 🇺🇸 | 12 | 27.27% |
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
| **Total Sum** | 8791.000 | 5414.360 |
| **Mean μ (Average)** | 73.258 | 45.120 |
| **Maximum** | 618.000 | 100.000 |
| **75th Percentile** | 75.000 | 55.560 |
| **Median** | 34.000 | 45.130 |
| **25th Percentile** | 12.000 | 34.870 |
| **Minimum** | 3.000 | 12.350 |
| **Variance** | 11462.558 | 277.189 |
| **Standard Deviation σ** | 107.063 | 16.649 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
