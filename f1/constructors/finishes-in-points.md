---
title: Rank of Formula 1® Constructor Teams by Number of Finishes in Points
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
                "121D32",
                "FDE139",
                "18A19B",
                "09630C",
                "73C2FB",
                "274B72",
                "F6AFC1",
                "0736A5",
                "243F73",
                "144D44",
                "0F5DBB",
                "2039C3",
                "FFFF01",
                "273027",
                "C0BEC3",
                "D70028",
                "20359D",
                "F6CA46",
                "FFA500",
                "FFFFFF",
                "B21827",
                "025839",
                "E53524",
                "FFFFFF",
                "025839",
                "D33949",
                "AAAAAA",
                "243F73",
                "E2F833",
                "3FB2B3",
                "1A2446",
                "888888",
                "888888",
                "243F73",
                "095921",
                "1B1D1D",
                "FA9B27",
                "336667",
                "888888",
                "DDDDDD",
                "07316F",
                "888888",
                "0D1773",
                "A3805E",
                "FFFFFF",
                "273027",
                "888888",
                "888888",
                "CF0F18",
                "FFFFFF",
                "457439",
                "888888",
                "888888",
                "888888",
                "888888",
                "DBC75F",
                "888888",
                "888888",
                "888888",
                "888888",
                "2077C9",
                "888888",
                "888888",
                "888888",
                "888888",
                "FC8881",
                "888888",
                "888888",
                "C4333B",
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
                "888888",
                "888888",
                "888888",
                "E30010",
                "888888",
                "888888",
                "888888",
                "5E0A16",
                "5E0A16",
                "888888",
                "888888",
                "888888",
                "FFA500",
                "888888",
                "888888",
                "888888"
            ],
            "borderColor": [
                "16191A",
                "0D1D20",
                "082957",
                "FDCC2F",
                "424B52",
                "D7D7D5",
                "444444",
                "444444",
                "444444",
                "C81625",
                "A17A5D",
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
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
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
                "444444"
            ],
            "borderWidth": 1,
            "data": [
                1187.0,
                839.0,
                640.0,
                300.0,
                259.0,
                252.0,
                241.0,
                212.0,
                190.0,
                162.0,
                159.0,
                154.0,
                135.0,
                115.0,
                114.0,
                110.0,
                87.0,
                87.0,
                87.0,
                77.0,
                75.0,
                70.0,
                65.0,
                50.0,
                50.0,
                49.0,
                42.0,
                42.0,
                38.0,
                38.0,
                33.0,
                31.0,
                26.0,
                25.0,
                23.0,
                23.0,
                22.0,
                22.0,
                21.0,
                21.0,
                20.0,
                19.0,
                18.0,
                16.0,
                16.0,
                16.0,
                15.0,
                14.0,
                13.0,
                13.0,
                12.0,
                12.0,
                12.0,
                12.0,
                11.0,
                10.0,
                10.0,
                10.0,
                9.0,
                9.0,
                8.0,
                7.0,
                7.0,
                7.0,
                6.0,
                6.0,
                6.0,
                5.0,
                5.0,
                4.0,
                4.0,
                4.0,
                3.0,
                3.0,
                3.0,
                3.0,
                3.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
                2.0,
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
                1.0
            ],
            "label": "Finished In Points"
        }
    ],
    "labels": [
        "Ferrari",
        "McLaren",
        "Williams",
        "Red Bull",
        "Renault",
        "Mercedes",
        "Team Lotus",
        "Benetton",
        "Tyrrell",
        "Force India",
        "Sauber",
        "Brabham",
        "BRM",
        "Ligier",
        "Toro Rosso",
        "Jordan",
        "Cooper-Climax",
        "Maserati",
        "Toyota",
        "BMW Sauber",
        "Lotus F1",
        "Arrows",
        "BAR",
        "Alfa Romeo",
        "Lotus-Climax",
        "March",
        "Honda",
        "Lotus-Ford",
        "Kurtis Kraft",
        "McLaren-Ford",
        "Brabham-Repco",
        "Brawn",
        "Matra-Ford",
        "Cooper-Maserati",
        "Matra",
        "Surtees",
        "Brabham-Climax",
        "Jaguar",
        "Minardi",
        "Shadow",
        "Vanwall",
        "Fittipaldi",
        "Porsche",
        "Brabham-Ford",
        "Larrousse",
        "Prost",
        "Wolf",
        "Stewart",
        "Cooper",
        "Footwork",
        "Ensign",
        "Haas F1 Team",
        "Hesketh",
        "Lotus-BRM",
        "Toleman",
        "Gordini",
        "Lola",
        "Talbot-Lago",
        "Epperly",
        "March-Ford",
        "Brabham-Alfa Romeo",
        "Cooper-BRM",
        "Dallara",
        "Penske",
        "Brabham-BRM",
        "Connaught",
        "Shadow-Ford",
        "BRP",
        "Watson",
        "ATS",
        "Iso Marlboro",
        "Kuzma",
        "Lancia",
        "Lesovsky",
        "Leyton House",
        "McLaren-BRM",
        "Parnelli",
        "AGS",
        "Deidt",
        "Eagle-Climax",
        "Eagle-Weslake",
        "Embassy Hill",
        "Onyx",
        "Osella",
        "Phillips",
        "Rial",
        "Simca",
        "Super Aguri",
        "Cooper-Castellotti",
        "Frazer Nash",
        "HWM",
        "Manor Marussia",
        "Marussia",
        "McLaren-Serenissima",
        "Schroeder",
        "Sherman",
        "Spyker",
        "Tecno",
        "Trevis",
        "Zakspeed"
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

| # | Constructor | Finished In Points | % Of Total Participations |
|--|--|--|--|
| 1. | Ferrari 🇮🇹 | 1187 | 56.10% |
| 2. | McLaren 🇬🇧 | 839 | 52.40% |
| 3. | Williams 🇬🇧 | 640 | 47.23% |
| 4. | Red Bull 🇦🇹 | 300 | 64.38% |
| 5. | Renault 🇫🇷 | 259 | 40.16% |
| 6. | Mercedes 🇩🇪 | 252 | 76.36% |
| 7. | Team Lotus 🇬🇧 | 241 | 27.67% |
| 8. | Benetton 🇮🇹 | 212 | 40.77% |
| 9. | Tyrrell 🇬🇧 | 190 | 21.57% |
| 10. | Force India 🇮🇳 | 162 | 45.25% |
| 11. | Sauber 🇨🇭 | 159 | 22.02% |
| 12. | Brabham 🇬🇧 | 154 | 23.26% |
| 13. | BRM 🇬🇧 | 135 | 24.02% |
| 14. | Ligier 🇫🇷 | 115 | 18.82% |
| 15. | Toro Rosso 🇮🇹 | 114 | 26.64% |
| 16. | Jordan 🇮🇪 | 110 | 22.00% |
| 17. | Cooper-Climax 🇬🇧 | 87 | 32.46% |
| 18. | Maserati 🇮🇹 | 87 | 19.95% |
| 19. | Toyota 🇯🇵 | 87 | 31.07% |
| 20. | BMW Sauber 🇩🇪 | 77 | 55.00% |
| 21. | Lotus F1 🇬🇧 | 75 | 48.70% |
| 22. | Arrows 🇬🇧 | 70 | 11.86% |
| 23. | BAR 🇬🇧 | 65 | 27.54% |
| 24. | Alfa Romeo 🇮🇹 | 50 | 20.49% |
| 25. | Lotus-Climax 🇬🇧 | 50 | 21.65% |
| 26. | March 🇬🇧 | 49 | 9.35% |
| 27. | Honda 🇯🇵 | 42 | 27.63% |
| 28. | Lotus-Ford 🇬🇧 | 42 | 32.81% |
| 29. | Kurtis Kraft 🇺🇸 | 38 | 16.81% |
| 30. | McLaren-Ford 🇬🇧 | 38 | 43.68% |
| 31. | Brabham-Repco 🇬🇧 | 33 | 42.86% |
| 32. | Brawn 🇬🇧 | 31 | 91.18% |
| 33. | Matra-Ford 🇫🇷 | 26 | 65.00% |
| 34. | Cooper-Maserati 🇬🇧 | 25 | 18.66% |
| 35. | Matra 🇫🇷 | 23 | 32.39% |
| 36. | Surtees 🇬🇧 | 23 | 8.85% |
| 37. | Brabham-Climax 🇬🇧 | 22 | 23.66% |
| 38. | Jaguar 🇬🇧 | 22 | 12.94% |
| 39. | Minardi 🇮🇹 | 21 | 3.12% |
| 40. | Shadow 🇬🇧 | 21 | 9.95% |
| 41. | Vanwall 🇬🇧 | 20 | 28.17% |
| 42. | Fittipaldi 🇧🇷 | 19 | 12.26% |
| 43. | Porsche 🇩🇪 | 18 | 21.43% |
| 44. | Brabham-Ford 🇬🇧 | 16 | 27.59% |
| 45. | Larrousse 🇫🇷 | 16 | 7.41% |
| 46. | Prost 🇫🇷 | 16 | 9.70% |
| 47. | Wolf 🇨🇦 | 15 | 18.99% |
| 48. | Stewart 🇬🇧 | 14 | 14.29% |
| 49. | Cooper 🇬🇧 | 13 | 12.62% |
| 50. | Footwork 🇬🇧 | 13 | 6.70% |
| 51. | Ensign 🇬🇧 | 12 | 7.79% |
| 52. | Haas F1 Team 🇺🇸 | 12 | 20.69% |
| 53. | Hesketh 🇬🇧 | 12 | 12.37% |
| 54. | Lotus-BRM 🇬🇧 | 12 | 9.92% |
| 55. | Toleman 🇬🇧 | 11 | 8.40% |
| 56. | Gordini 🇫🇷 | 10 | 9.80% |
| 57. | Lola 🇬🇧 | 10 | 6.06% |
| 58. | Talbot-Lago 🇫🇷 | 10 | 12.20% |
| 59. | Epperly 🇺🇸 | 9 | 52.94% |
| 60. | March-Ford 🇬🇧 | 9 | 20.93% |
| 61. | Brabham-Alfa Romeo 🇬🇧 | 8 | 13.56% |
| 62. | Cooper-BRM 🇬🇧 | 7 | 33.33% |
| 63. | Dallara 🇮🇹 | 7 | 4.86% |
| 64. | Penske 🇺🇸 | 7 | 15.22% |
| 65. | Brabham-BRM 🇬🇧 | 6 | 14.63% |
| 66. | Connaught 🇬🇧 | 6 | 11.11% |
| 67. | Shadow-Ford 🇬🇧 | 6 | 23.08% |
| 68. | BRP 🇬🇧 | 5 | 26.32% |
| 69. | Watson 🇺🇸 | 5 | 22.73% |
| 70. | ATS 🇮🇹 | 4 | 2.47% |
| 71. | Iso Marlboro 🇬🇧 | 4 | 7.27% |
| 72. | Kuzma 🇺🇸 | 4 | 10.26% |
| 73. | Lancia 🇮🇹 | 3 | 27.27% |
| 74. | Lesovsky 🇺🇸 | 3 | 20.00% |
| 75. | Leyton House 🇬🇧 | 3 | 4.69% |
| 76. | McLaren-BRM 🇬🇧 | 3 | 21.43% |
| 77. | Parnelli 🇺🇸 | 3 | 18.75% |
| 78. | AGS 🇫🇷 | 2 | 1.63% |
| 79. | Deidt 🇺🇸 | 2 | 25.00% |
| 80. | Eagle-Climax 🇺🇸 | 2 | 15.38% |
| 81. | Eagle-Weslake 🇺🇸 | 2 | 9.52% |
| 82. | Embassy Hill 🇬🇧 | 2 | 10.53% |
| 83. | Onyx 🇬🇧 | 2 | 3.85% |
| 84. | Osella 🇮🇹 | 2 | 0.79% |
| 85. | Phillips 🇺🇸 | 2 | 28.57% |
| 86. | Rial 🇩🇪 | 2 | 4.17% |
| 87. | Simca 🇫🇷 | 2 | 6.90% |
| 88. | Super Aguri 🇯🇵 | 2 | 2.56% |
| 89. | Cooper-Castellotti 🇬🇧 | 1 | 16.67% |
| 90. | Frazer Nash 🇬🇧 | 1 | 25.00% |
| 91. | HWM 🇬🇧 | 1 | 2.13% |
| 92. | Manor Marussia 🇬🇧 | 1 | 1.28% |
| 93. | Marussia 🇷🇺 | 1 | 0.92% |
| 94. | McLaren-Serenissima 🇬🇧 | 1 | 50.00% |
| 95. | Schroeder 🇺🇸 | 1 | 12.50% |
| 96. | Sherman 🇺🇸 | 1 | 50.00% |
| 97. | Spyker 🇳🇱 | 1 | 2.94% |
| 98. | Tecno 🇮🇹 | 1 | 9.09% |
| 99. | Trevis 🇺🇸 | 1 | 16.67% |
| 100. | Zakspeed 🇩🇪 | 1 | 0.75% |

#### Statistic Summary

| **Column** | **Finished In Points** | **% Of Total Participations** |
| **Row Count** | 100 | 100 |
| **Total Sum** | 6558.000 | 2210.350 |
| **Mean μ (Average)** | 65.580 | 22.104 |
| **Maximum** | 1187.000 | 91.180 |
| **75th Percentile** | 50.000 | 27.670 |
| **Median** | 13.000 | 18.990 |
| **25th Percentile** | 3.000 | 9.700 |
| **Minimum** | 1.000 | 0.750 |
| **Variance** | 26516.644 | 309.441 |
| **Standard Deviation σ** | 162.839 | 17.591 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
