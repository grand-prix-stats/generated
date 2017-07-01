---
title: Rank of Formula 1® Drivers by Number of Points
layout: page
collectionName: 
collectionId: 
---



<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
  "labels" : [
    "Lewis Hamilton",
    "Sebastian Vettel",
    "Fernando Alonso",
    "Nico Rosberg",
    "Michael Schumacher",
    "Kimi Räikkönen",
    "Jenson Button",
    "Felipe Massa",
    "Mark Webber",
    "Alain Prost",
    "Daniel Ricciardo",
    "Rubens Barrichello",
    "Ayrton Senna",
    "David Coulthard",
    "Valtteri Bottas",
    "Nelson Piquet",
    "Nigel Mansell",
    "Niki Lauda",
    "Mika Häkkinen",
    "Sergio Pérez",
    "Gerhard Berger",
    "Nico Hülkenberg",
    "Damon Hill",
    "Jackie Stewart",
    "Ralf Schumacher",
    "Romain Grosjean",
    "Carlos Reutemann",
    "Juan Pablo Montoya",
    "Max Verstappen",
    "Graham Hill",
    "Emerson Fittipaldi",
    "Riccardo Patrese",
    "Juan Fangio",
    "Giancarlo Fisichella",
    "Jim Clark",
    "Robert Kubica",
    "Jack Brabham",
    "Nick Heidfeld",
    "Jody Scheckter",
    "Denny Hulme",
    "Jarno Trulli",
    "Jean Alesi",
    "Jacques Villeneuve",
    "Jacques Laffite",
    "Clay Regazzoni",
    "Alan Jones",
    "Ronnie Peterson",
    "Bruce McLaren",
    "Eddie Irvine",
    "Michele Alboreto",
    "Stirling Moss",
    "Jacky Ickx",
    "René Arnoux",
    "John Surtees",
    "Mario Andretti",
    "James Hunt",
    "Heinz-Harald Frentzen",
    "John Watson",
    "Keke Rosberg",
    "Patrick Depailler",
    "Alberto Ascari",
    "Dan Gurney",
    "Daniil Kvyat",
    "Thierry Boutsen",
    "Mike Hawthorn",
    "Nino Farina",
    "Kamui Kobayashi",
    "Adrian Sutil",
    "Elio de Angelis",
    "Paul di Resta",
    "Jochen Rindt",
    "Gilles Villeneuve",
    "Richie Ginther",
    "Heikki Kovalainen",
    "Patrick Tambay",
    "Didier Pironi",
    "Johnny Herbert",
    "Martin Brundle",
    "Phil Hill",
    "Carlos Sainz",
    "François Cevert",
    "Stefan Johansson",
    "Chris Amon",
    "José Froilán González",
    "Jean-Pierre Beltoise",
    "Olivier Panis",
    "Pastor Maldonado",
    "Tony Brooks",
    "Kevin Magnussen",
    "Maurice Trintignant",
    "Derek Warwick",
    "Jochen Mass",
    "Pedro Rodríguez",
    "Eddie Cheever",
    "Jo Siffert",
    "Alessandro Nannini",
    "Vitaly Petrov",
    "Peter Revson",
    "Andrea de Cesaris",
    "Carlos Pace",
    "Lorenzo Bandini",
    "Wolfgang von Trips",
    "Jean Behra",
    "Jean-Éric Vergne",
    "Timo Glock",
    "Luigi Villoresi",
    "Innes Ireland",
    "Peter Collins",
    "Alexander Wurz",
    "Luigi Musso",
    "Takuma Sato",
    "Piero Taruffi",
    "Jo Bonnier",
    "Esteban Ocon",
    "Pedro de la Rosa",
    "Bruno Senna",
    "Mika Salo",
    "Harry Schell",
    "Luigi Fagioli",
    "Mark Blundell"
  ],
  "datasets" : [
    {
      "label" : "Points",
      "data" : [
        2386,
        2261,
        1834,
        1594.5,
        1566,
        1433,
        1235,
        1144,
        1047.5,
        798.5,
        708,
        658,
        614,
        535,
        522,
        485.5,
        482,
        420.5,
        420,
        411,
        385,
        380,
        360,
        360,
        329,
        326,
        310,
        307,
        298,
        289,
        281,
        281,
        279.14,
        275,
        274,
        273,
        261,
        259,
        255,
        248,
        246.5,
        241,
        235,
        228,
        212,
        206,
        206,
        196.5,
        191,
        186.5,
        186.5,
        181,
        181,
        180,
        180,
        179,
        174,
        169,
        159.5,
        141,
        140,
        133,
        132,
        132,
        127.64,
        127.33,
        125,
        124,
        122,
        121,
        109,
        107,
        107,
        105,
        103,
        101,
        98,
        98,
        98,
        93,
        89,
        88,
        83,
        77.64,
        77,
        76,
        76,
        75,
        73,
        72.33,
        71,
        71,
        71,
        70,
        68,
        65,
        64,
        61,
        59,
        58,
        58,
        56,
        51,
        51,
        51,
        49,
        47,
        47,
        45,
        45,
        44,
        41,
        39,
        35,
        35,
        33,
        33,
        32,
        32,
        32
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

| # | Driver | Points |
|--|--|--|
| 1. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 2386.0 |
| 2. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 2261.0 |
| 3. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 1834.0 |
| 4. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 1594.5 |
| 5. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 1566.0 |
| 6. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 1433.0 |
| 7. | [Jenson Button 🇬🇧](/f1/drivers/button) | 1235.0 |
| 8. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 1144.0 |
| 9. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 1047.5 |
| 10. | [Alain Prost 🇫🇷](/f1/drivers/prost) | 798.5 |
| 11. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 708.0 |
| 12. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 658.0 |
| 13. | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 614.0 |
| 14. | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | 535.0 |
| 15. | [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 522.0 |
| 16. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 485.5 |
| 17. | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 482.0 |
| 18. | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | 420.5 |
| 19. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 420.0 |
| 20. | [Sergio Pérez 🇲🇽](/f1/drivers/perez) | 411.0 |
| 21. | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 385.0 |
| 22. | [Nico Hülkenberg 🇩🇪](/f1/drivers/hulkenberg) | 380.0 |
| 23. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 360.0 |
| 24. | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | 360.0 |
| 25. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 329.0 |
| 26. | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 326.0 |
| 27. | [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | 310.0 |
| 28. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 307.0 |
| 29. | [Max Verstappen 🇳🇱](/f1/drivers/max_verstappen) | 298.0 |
| 30. | [Graham Hill 🇬🇧](/f1/drivers/hill) | 289.0 |
| 31. | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | 281.0 |
| 32. | [Riccardo Patrese 🇮🇹](/f1/drivers/patrese) | 281.0 |
| 33. | [Juan Fangio 🇦🇷](/f1/drivers/fangio) | 279.14 |
| 34. | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 275.0 |
| 35. | [Jim Clark 🇬🇧](/f1/drivers/clark) | 274.0 |
| 36. | [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 273.0 |
| 37. | [Jack Brabham 🇦🇺](/f1/drivers/jack_brabham) | 261.0 |
| 38. | [Nick Heidfeld 🇩🇪](/f1/drivers/heidfeld) | 259.0 |
| 39. | [Jody Scheckter 🇿🇦](/f1/drivers/scheckter) | 255.0 |
| 40. | [Denny Hulme 🇳🇿](/f1/drivers/hulme) | 248.0 |
| 41. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 246.5 |
| 42. | [Jean Alesi 🇫🇷](/f1/drivers/alesi) | 241.0 |
| 43. | [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | 235.0 |
| 44. | [Jacques Laffite 🇫🇷](/f1/drivers/laffite) | 228.0 |
| 45. | [Clay Regazzoni 🇨🇭](/f1/drivers/regazzoni) | 212.0 |
| 46. | [Alan Jones 🇦🇺](/f1/drivers/jones) | 206.0 |
| 47. | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 206.0 |
| 48. | [Bruce McLaren 🇳🇿](/f1/drivers/mclaren) | 196.5 |
| 49. | [Eddie Irvine 🇬🇧](/f1/drivers/irvine) | 191.0 |
| 50. | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 186.5 |
| 51. | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 186.5 |
| 52. | [Jacky Ickx 🇧🇪](/f1/drivers/ickx) | 181.0 |
| 53. | [René Arnoux 🇫🇷](/f1/drivers/arnoux) | 181.0 |
| 54. | [John Surtees 🇬🇧](/f1/drivers/surtees) | 180.0 |
| 55. | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | 180.0 |
| 56. | [James Hunt 🇬🇧](/f1/drivers/hunt) | 179.0 |
| 57. | [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | 174.0 |
| 58. | [John Watson 🇬🇧](/f1/drivers/watson) | 169.0 |
| 59. | [Keke Rosberg 🇫🇮](/f1/drivers/keke_rosberg) | 159.5 |
| 60. | [Patrick Depailler 🇫🇷](/f1/drivers/depailler) | 141.0 |
| 61. | [Alberto Ascari 🇮🇹](/f1/drivers/ascari) | 140.0 |
| 62. | [Dan Gurney 🇺🇸](/f1/drivers/gurney) | 133.0 |
| 63. | [Daniil Kvyat 🇷🇺](/f1/drivers/kvyat) | 132.0 |
| 64. | [Thierry Boutsen 🇧🇪](/f1/drivers/boutsen) | 132.0 |
| 65. | [Mike Hawthorn 🇬🇧](/f1/drivers/hawthorn) | 127.64 |
| 66. | [Nino Farina 🇮🇹](/f1/drivers/farina) | 127.33 |
| 67. | [Kamui Kobayashi 🇯🇵](/f1/drivers/kobayashi) | 125.0 |
| 68. | [Adrian Sutil 🇩🇪](/f1/drivers/sutil) | 124.0 |
| 69. | [Elio de Angelis 🇮🇹](/f1/drivers/angelis) | 122.0 |
| 70. | [Paul di Resta 🇬🇧](/f1/drivers/resta) | 121.0 |
| 71. | [Jochen Rindt 🇦🇹](/f1/drivers/rindt) | 109.0 |
| 72. | [Gilles Villeneuve 🇨🇦](/f1/drivers/gilles_villeneuve) | 107.0 |
| 73. | [Richie Ginther 🇺🇸](/f1/drivers/ginther) | 107.0 |
| 74. | [Heikki Kovalainen 🇫🇮](/f1/drivers/kovalainen) | 105.0 |
| 75. | [Patrick Tambay 🇫🇷](/f1/drivers/tambay) | 103.0 |
| 76. | [Didier Pironi 🇫🇷](/f1/drivers/pironi) | 101.0 |
| 77. | [Johnny Herbert 🇬🇧](/f1/drivers/herbert) | 98.0 |
| 78. | [Martin Brundle 🇬🇧](/f1/drivers/brundle) | 98.0 |
| 79. | [Phil Hill 🇺🇸](/f1/drivers/phil_hill) | 98.0 |
| 80. | [Carlos Sainz 🇪🇸](/f1/drivers/sainz) | 93.0 |
| 81. | [François Cevert 🇫🇷](/f1/drivers/cevert) | 89.0 |
| 82. | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 88.0 |
| 83. | [Chris Amon 🇳🇿](/f1/drivers/amon) | 83.0 |
| 84. | [José Froilán González 🇦🇷](/f1/drivers/gonzalez) | 77.64 |
| 85. | [Jean-Pierre Beltoise 🇫🇷](/f1/drivers/beltoise) | 77.0 |
| 86. | [Olivier Panis 🇫🇷](/f1/drivers/panis) | 76.0 |
| 87. | [Pastor Maldonado 🇻🇪](/f1/drivers/maldonado) | 76.0 |
| 88. | [Tony Brooks 🇬🇧](/f1/drivers/brooks) | 75.0 |
| 89. | [Kevin Magnussen 🇩🇰](/f1/drivers/kevin_magnussen) | 73.0 |
| 90. | [Maurice Trintignant 🇫🇷](/f1/drivers/trintignant) | 72.33 |
| 91. | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 71.0 |
| 92. | [Jochen Mass 🇩🇪](/f1/drivers/mass) | 71.0 |
| 93. | [Pedro Rodríguez 🇲🇽](/f1/drivers/rodriguez) | 71.0 |
| 94. | [Eddie Cheever 🇺🇸](/f1/drivers/cheever) | 70.0 |
| 95. | [Jo Siffert 🇨🇭](/f1/drivers/siffert) | 68.0 |
| 96. | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 65.0 |
| 97. | [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 64.0 |
| 98. | [Peter Revson 🇺🇸](/f1/drivers/revson) | 61.0 |
| 99. | [Andrea de Cesaris 🇮🇹](/f1/drivers/cesaris) | 59.0 |
| 100. | [Carlos Pace 🇧🇷](/f1/drivers/pace) | 58.0 |
| 101. | [Lorenzo Bandini 🇮🇹](/f1/drivers/bandini) | 58.0 |
| 102. | [Wolfgang von Trips 🇩🇪](/f1/drivers/trips) | 56.0 |
| 103. | [Jean Behra 🇫🇷](/f1/drivers/behra) | 51.0 |
| 104. | [Jean-Éric Vergne 🇫🇷](/f1/drivers/vergne) | 51.0 |
| 105. | [Timo Glock 🇩🇪](/f1/drivers/glock) | 51.0 |
| 106. | [Luigi Villoresi 🇮🇹](/f1/drivers/villoresi) | 49.0 |
| 107. | [Innes Ireland 🇬🇧](/f1/drivers/ireland) | 47.0 |
| 108. | [Peter Collins 🇬🇧](/f1/drivers/collins) | 47.0 |
| 109. | [Alexander Wurz 🇦🇹](/f1/drivers/wurz) | 45.0 |
| 110. | [Luigi Musso 🇮🇹](/f1/drivers/musso) | 45.0 |
| 111. | [Takuma Sato 🇯🇵](/f1/drivers/sato) | 44.0 |
| 112. | [Piero Taruffi 🇮🇹](/f1/drivers/taruffi) | 41.0 |
| 113. | [Jo Bonnier 🇸🇪](/f1/drivers/bonnier) | 39.0 |
| 114. | [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 35.0 |
| 115. | [Pedro de la Rosa 🇪🇸](/f1/drivers/rosa) | 35.0 |
| 116. | [Bruno Senna 🇧🇷](/f1/drivers/bruno_senna) | 33.0 |
| 117. | [Mika Salo 🇫🇮](/f1/drivers/salo) | 33.0 |
| 118. | [Harry Schell 🇺🇸](/f1/drivers/schell) | 32.0 |
| 119. | [Luigi Fagioli 🇮🇹](/f1/drivers/fagioli) | 32.0 |
| 120. | [Mark Blundell 🇬🇧](/f1/drivers/blundell) | 32.0 |

#### Statistic Summary

| **Column** | **Points** |
| **Row Count** | 120 |
| **Total Sum** | 35069.080 |
| **Mean μ (Average)** | 292.242 |
| **Maximum** | 2386.000 |
| **75th Percentile** | 289.000 |
| **Median** | 141.000 |
| **25th Percentile** | 72.330 |
| **Minimum** | 32.000 |
| **Variance** | 178575.895 |
| **Standard Deviation σ** | 422.582 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
