---
title: Rank of Formula 1® Constructor Teams by Number of Races Finished
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
                "EAE4ED",
                "0736A5",
                "274B72",
                "09630C",
                "FDE139",
                "121D32",
                "73C2FB",
                "2039C3",
                "0F5DBB",
                "1B1D1D",
                "243F73",
                "F6AFC1",
                "18A19B",
                "FFA500",
                "FFFF01",
                "144D44",
                "E53524",
                "D70028",
                "C0BEC3",
                "273027",
                "FFFFFF",
                "D33949",
                "888888",
                "20359D",
                "F6CA46",
                "025839",
                "B21827",
                "FFFFFF",
                "095921",
                "FA9B27",
                "5E0A16",
                "888888",
                "0D1773",
                "124411",
                "888888",
                "BE9D56",
                "888888",
                "5E0A16",
                "888888",
                "273027",
                "1A2446",
                "025839",
                "888888",
                "DDDDDD",
                "006400",
                "AAAAAA",
                "F60002",
                "E30010",
                "243F73",
                "888888",
                "457439",
                "888888",
                "CF0F18",
                "888888",
                "888888",
                "FFFFFF",
                "243F73",
                "888888",
                "FFFFFF",
                "888888",
                "A3805E",
                "E2F833",
                "3FB2B3",
                "336667",
                "07316F",
                "2077C9",
                "888888",
                "888888",
                "C4333B",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "FFA500",
                "888888",
                "888888",
                "DBC75F",
                "888888",
                "343434",
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
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "FFA500",
                "888888",
                "888888",
                "888888",
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
                "888888"
            ],
            "borderColor": [
                "16191A",
                "0D1D20",
                "082957",
                "A17A5D",
                "444444",
                "444444",
                "424B52",
                "FDCC2F",
                "444444",
                "FC181D",
                "444444",
                "444444",
                "444444",
                "C81625",
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
                1478.0,
                1104.0,
                948.0,
                481.0,
                456.0,
                432.0,
                417.0,
                382.0,
                336.0,
                317.0,
                310.0,
                302.0,
                299.0,
                292.0,
                279.0,
                278.0,
                275.0,
                261.0,
                209.0,
                202.0,
                198.0,
                150.0,
                138.0,
                124.0,
                121.0,
                120.0,
                115.0,
                114.0,
                102.0,
                102.0,
                95.0,
                95.0,
                94.0,
                91.0,
                90.0,
                88.0,
                82.0,
                79.0,
                69.0,
                66.0,
                62.0,
                61.0,
                59.0,
                59.0,
                57.0,
                56.0,
                53.0,
                50.0,
                49.0,
                48.0,
                47.0,
                45.0,
                45.0,
                44.0,
                44.0,
                43.0,
                42.0,
                40.0,
                39.0,
                39.0,
                39.0,
                38.0,
                33.0,
                32.0,
                29.0,
                27.0,
                26.0,
                26.0,
                26.0,
                25.0,
                24.0,
                22.0,
                22.0,
                21.0,
                21.0,
                20.0,
                20.0,
                18.0,
                17.0,
                16.0,
                16.0,
                16.0,
                15.0,
                15.0,
                14.0,
                14.0,
                11.0,
                10.0,
                10.0,
                9.0,
                9.0,
                9.0,
                8.0,
                8.0,
                8.0,
                8.0,
                8.0,
                7.0,
                7.0,
                6.0,
                5.0,
                5.0,
                5.0,
                5.0,
                5.0,
                5.0,
                4.0,
                4.0,
                4.0,
                4.0,
                4.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0
            ],
            "label": "Races Finished"
        }
    ],
    "labels": [
        "Ferrari",
        "McLaren",
        "Williams",
        "Sauber",
        "Tyrrell",
        "Team Lotus",
        "Renault",
        "Red Bull",
        "Benetton",
        "Toro Rosso",
        "Ligier",
        "Minardi",
        "Brabham",
        "Force India",
        "Mercedes",
        "Arrows",
        "Jordan",
        "BRM",
        "March",
        "Toyota",
        "Maserati",
        "Cooper-Climax",
        "BAR",
        "Kurtis Kraft",
        "Surtees",
        "BMW Sauber",
        "Lotus F1",
        "Lotus-Climax",
        "Alfa Romeo",
        "Honda",
        "Jaguar",
        "Shadow",
        "Marussia",
        "Larrousse",
        "Prost",
        "Caterham",
        "Footwork",
        "HRT",
        "Fittipaldi",
        "Manor Marussia",
        "Dallara",
        "Cooper",
        "Cooper-Maserati",
        "Lotus-Ford",
        "Lola",
        "Porsche",
        "Lotus",
        "McLaren-Ford",
        "Virgin",
        "Super Aguri",
        "Brabham-Climax",
        "ATS",
        "Lotus-BRM",
        "Ensign",
        "Haas F1 Team",
        "Matra",
        "Talbot-Lago",
        "Stewart",
        "Brabham-Repco",
        "Gordini",
        "Hesketh",
        "Osella",
        "Wolf",
        "Brawn",
        "Matra-Ford",
        "Vanwall",
        "Brabham-Ford",
        "Penske",
        "Toleman",
        "Zakspeed",
        "Kuzma",
        "AGS",
        "Brabham-BRM",
        "Iso Marlboro",
        "Leyton House",
        "Brabham-Alfa Romeo",
        "Spyker",
        "HWM",
        "Connaught",
        "Epperly",
        "March-Ford",
        "MF1",
        "Forti",
        "Simtek",
        "RAM",
        "Watson",
        "Embassy Hill",
        "BRP",
        "Shadow-Ford",
        "Lesovsky",
        "Rial",
        "Spirit",
        "Cooper-BRM",
        "Euro Brun",
        "Onyx",
        "Parnelli",
        "Simca",
        "Stevens",
        "Veritas",
        "Pacific",
        "Aston Martin",
        "ERA",
        "Fondmetal",
        "McLaren-BRM",
        "Phillips",
        "Spyker MF1",
        "Coloni",
        "Lambo",
        "March-Alfa Romeo",
        "Martini",
        "Trevis",
        "BMW",
        "Cooper-Castellotti",
        "Deidt",
        "Eagle-Climax",
        "Eagle-Weslake",
        "Ewing",
        "Lancia",
        "Moore",
        "OSCA"
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

| # | Constructor | Races Finished | % Of Total Participations |
|--|--|--|--|
| 1. | Ferrari 🇮🇹 | 1478 | 69.85% |
| 2. | McLaren 🇬🇧 | 1104 | 68.96% |
| 3. | Williams 🇬🇧 | 948 | 69.96% |
| 4. | Sauber 🇨🇭 | 481 | 66.62% |
| 5. | Tyrrell 🇬🇧 | 456 | 51.76% |
| 6. | Team Lotus 🇬🇧 | 432 | 49.60% |
| 7. | Renault 🇫🇷 | 417 | 64.65% |
| 8. | Red Bull 🇦🇹 | 382 | 81.97% |
| 9. | Benetton 🇮🇹 | 336 | 64.62% |
| 10. | Toro Rosso 🇮🇹 | 317 | 74.07% |
| 11. | Ligier 🇫🇷 | 310 | 50.74% |
| 12. | Minardi 🇮🇹 | 302 | 44.94% |
| 13. | Brabham 🇬🇧 | 299 | 45.17% |
| 14. | Force India 🇮🇳 | 292 | 81.56% |
| 15. | Mercedes 🇩🇪 | 279 | 84.55% |
| 16. | Arrows 🇬🇧 | 278 | 47.12% |
| 17. | Jordan 🇮🇪 | 275 | 55.00% |
| 18. | BRM 🇬🇧 | 261 | 46.44% |
| 19. | March 🇬🇧 | 209 | 39.89% |
| 20. | Toyota 🇯🇵 | 202 | 72.14% |
| 21. | Maserati 🇮🇹 | 198 | 45.41% |
| 22. | Cooper-Climax 🇬🇧 | 150 | 55.97% |
| 23. | BAR 🇬🇧 | 138 | 58.47% |
| 24. | Kurtis Kraft 🇺🇸 | 124 | 54.87% |
| 25. | Surtees 🇬🇧 | 121 | 46.54% |
| 26. | BMW Sauber 🇩🇪 | 120 | 85.71% |
| 27. | Lotus F1 🇬🇧 | 115 | 74.68% |
| 28. | Lotus-Climax 🇬🇧 | 114 | 49.35% |
| 29. | Alfa Romeo 🇮🇹 | 102 | 41.80% |
| 30. | Honda 🇯🇵 | 102 | 67.11% |
| 31. | Jaguar 🇬🇧 | 95 | 55.88% |
| 32. | Shadow 🇬🇧 | 95 | 45.02% |
| 33. | Marussia 🇷🇺 | 94 | 86.24% |
| 34. | Larrousse 🇫🇷 | 91 | 42.13% |
| 35. | Prost 🇫🇷 | 90 | 54.55% |
| 36. | Caterham 🇲🇾 | 88 | 78.57% |
| 37. | Footwork 🇬🇧 | 82 | 42.27% |
| 38. | HRT 🇪🇸 | 79 | 69.30% |
| 39. | Fittipaldi 🇧🇷 | 69 | 44.52% |
| 40. | Manor Marussia 🇬🇧 | 66 | 84.62% |
| 41. | Dallara 🇮🇹 | 62 | 43.06% |
| 42. | Cooper 🇬🇧 | 61 | 59.22% |
| 43. | Cooper-Maserati 🇬🇧 | 59 | 44.03% |
| 44. | Lotus-Ford 🇬🇧 | 59 | 46.09% |
| 45. | Lola 🇬🇧 | 57 | 34.55% |
| 46. | Porsche 🇩🇪 | 56 | 66.67% |
| 47. | Lotus 🇲🇾 | 53 | 69.74% |
| 48. | McLaren-Ford 🇬🇧 | 50 | 57.47% |
| 49. | Virgin 🇬🇧 | 49 | 64.47% |
| 50. | Super Aguri 🇯🇵 | 48 | 61.54% |
| 51. | Brabham-Climax 🇬🇧 | 47 | 50.54% |
| 52. | ATS 🇮🇹 | 45 | 27.78% |
| 53. | Lotus-BRM 🇬🇧 | 45 | 37.19% |
| 54. | Ensign 🇬🇧 | 44 | 28.57% |
| 55. | Haas F1 Team 🇺🇸 | 44 | 75.86% |
| 56. | Matra 🇫🇷 | 43 | 60.56% |
| 57. | Talbot-Lago 🇫🇷 | 42 | 51.22% |
| 58. | Stewart 🇬🇧 | 40 | 40.82% |
| 59. | Brabham-Repco 🇬🇧 | 39 | 50.65% |
| 60. | Gordini 🇫🇷 | 39 | 38.24% |
| 61. | Hesketh 🇬🇧 | 39 | 40.21% |
| 62. | Osella 🇮🇹 | 38 | 15.08% |
| 63. | Wolf 🇨🇦 | 33 | 41.77% |
| 64. | Brawn 🇬🇧 | 32 | 94.12% |
| 65. | Matra-Ford 🇫🇷 | 29 | 72.50% |
| 66. | Vanwall 🇬🇧 | 27 | 38.03% |
| 67. | Brabham-Ford 🇬🇧 | 26 | 44.83% |
| 68. | Penske 🇺🇸 | 26 | 56.52% |
| 69. | Toleman 🇬🇧 | 26 | 19.85% |
| 70. | Zakspeed 🇩🇪 | 25 | 18.80% |
| 71. | Kuzma 🇺🇸 | 24 | 61.54% |
| 72. | AGS 🇫🇷 | 22 | 17.89% |
| 73. | Brabham-BRM 🇬🇧 | 22 | 53.66% |
| 74. | Iso Marlboro 🇬🇧 | 21 | 38.18% |
| 75. | Leyton House 🇬🇧 | 21 | 32.81% |
| 76. | Brabham-Alfa Romeo 🇬🇧 | 20 | 33.90% |
| 77. | Spyker 🇳🇱 | 20 | 58.82% |
| 78. | HWM 🇬🇧 | 18 | 38.30% |
| 79. | Connaught 🇬🇧 | 17 | 31.48% |
| 80. | Epperly 🇺🇸 | 16 | 94.12% |
| 81. | March-Ford 🇬🇧 | 16 | 37.21% |
| 82. | MF1 🇷🇺 | 16 | 57.14% |
| 83. | Forti 🇮🇹 | 15 | 27.78% |
| 84. | Simtek 🇬🇧 | 15 | 37.50% |
| 85. | RAM 🇬🇧 | 14 | 19.72% |
| 86. | Watson 🇺🇸 | 14 | 63.64% |
| 87. | Embassy Hill 🇬🇧 | 11 | 57.89% |
| 88. | BRP 🇬🇧 | 10 | 52.63% |
| 89. | Shadow-Ford 🇬🇧 | 10 | 38.46% |
| 90. | Lesovsky 🇺🇸 | 9 | 60.00% |
| 91. | Rial 🇩🇪 | 9 | 18.75% |
| 92. | Spirit 🇬🇧 | 9 | 36.00% |
| 93. | Cooper-BRM 🇬🇧 | 8 | 38.10% |
| 94. | Euro Brun 🇮🇹 | 8 | 10.53% |
| 95. | Onyx 🇬🇧 | 8 | 15.38% |
| 96. | Parnelli 🇺🇸 | 8 | 50.00% |
| 97. | Simca 🇫🇷 | 8 | 27.59% |
| 98. | Stevens 🇺🇸 | 7 | 70.00% |
| 99. | Veritas 🇩🇪 | 7 | 38.89% |
| 100. | Pacific 🇬🇧 | 6 | 9.09% |
| 101. | Aston Martin 🇬🇧 | 5 | 45.45% |
| 102. | ERA 🇬🇧 | 5 | 38.46% |
| 103. | Fondmetal 🇮🇹 | 5 | 11.90% |
| 104. | McLaren-BRM 🇬🇧 | 5 | 35.71% |
| 105. | Phillips 🇺🇸 | 5 | 71.43% |
| 106. | Spyker MF1 🇳🇱 | 5 | 62.50% |
| 107. | Coloni 🇮🇹 | 4 | 4.94% |
| 108. | Lambo 🇮🇹 | 4 | 12.50% |
| 109. | March-Alfa Romeo 🇬🇧 | 4 | 44.44% |
| 110. | Martini 🇫🇷 | 4 | 50.00% |
| 111. | Trevis 🇺🇸 | 4 | 66.67% |
| 112. | BMW 🇩🇪 | 3 | 50.00% |
| 113. | Cooper-Castellotti 🇬🇧 | 3 | 50.00% |
| 114. | Deidt 🇺🇸 | 3 | 37.50% |
| 115. | Eagle-Climax 🇺🇸 | 3 | 23.08% |
| 116. | Eagle-Weslake 🇺🇸 | 3 | 14.29% |
| 117. | Ewing 🇺🇸 | 3 | 100.00% |
| 118. | Lancia 🇮🇹 | 3 | 27.27% |
| 119. | Moore 🇺🇸 | 3 | 100.00% |
| 120. | OSCA 🇮🇹 | 3 | 37.50% |

#### Statistic Summary

| **Column** | **Races Finished** | **% Of Total Participations** |
| **Row Count** | 120 | 120 |
| **Total Sum** | 12960.000 | 5973.240 |
| **Mean μ (Average)** | 108.000 | 49.777 |
| **Maximum** | 1478.000 | 100.000 |
| **75th Percentile** | 102.000 | 64.470 |
| **Median** | 39.000 | 49.600 |
| **25th Percentile** | 9.000 | 38.030 |
| **Minimum** | 3.000 | 4.940 |
| **Variance** | 42645.383 | 413.594 |
| **Standard Deviation σ** | 206.508 | 20.337 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
