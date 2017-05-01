---
title: Rank of Formula 1® Drivers by Number of Participations
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
            ],
            "borderColor": [
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
            "borderWidth": 1,
            "data": [
                326.0,
                308.0,
                308.0,
                278.0,
                257.0,
                257.0,
                256.0,
                256.0,
                247.0,
                231.0,
                217.0,
                215.0,
                214.0,
                210.0,
                207.0,
                206.0,
                202.0,
                202.0,
                192.0,
                192.0,
                184.0,
                183.0,
                180.0,
                180.0,
                179.0,
                174.0,
                165.0,
                165.0,
                165.0,
                165.0,
                164.0,
                164.0,
                162.0,
                162.0,
                159.0,
                158.0,
                154.0,
                149.0,
                147.0,
                146.0,
                143.0,
                143.0,
                138.0,
                129.0,
                129.0,
                128.0,
                128.0,
                123.0,
                123.0,
                122.0,
                122.0,
                121.0,
                121.0,
                119.0,
                117.0,
                115.0,
                114.0,
                113.0,
                113.0,
                112.0,
                112.0,
                112.0,
                111.0,
                111.0,
                110.0,
                109.0,
                108.0,
                107.0,
                107.0,
                106.0,
                103.0,
                103.0,
                100.0,
                100.0,
                99.0,
                98.0,
                97.0,
                96.0,
                95.0,
                95.0,
                95.0,
                93.0,
                91.0,
                88.0,
                88.0,
                88.0,
                87.0,
                87.0,
                87.0,
                84.0,
                84.0,
                82.0,
                82.0,
                81.0,
                81.0,
                80.0,
                80.0,
                80.0,
                78.0,
                78.0,
                77.0,
                76.0,
                76.0,
                75.0,
                75.0,
                74.0,
                73.0,
                73.0,
                72.0,
                72.0,
                70.0,
                70.0,
                70.0,
                69.0,
                68.0,
                64.0,
                64.0,
                63.0,
                63.0,
                63.0
            ],
            "label": "Participations"
        }
    ],
    "labels": [
        "Rubens Barrichello",
        "Jenson Button",
        "Michael Schumacher",
        "Fernando Alonso",
        "Kimi Räikkönen",
        "Riccardo Patrese",
        "Felipe Massa",
        "Jarno Trulli",
        "David Coulthard",
        "Giancarlo Fisichella",
        "Mark Webber",
        "Michele Alboreto",
        "Andrea de Cesaris",
        "Gerhard Berger",
        "Nelson Piquet",
        "Nico Rosberg",
        "Alain Prost",
        "Jean Alesi",
        "Lewis Hamilton",
        "Nigel Mansell",
        "Nick Heidfeld",
        "Sebastian Vettel",
        "Jacques Laffite",
        "Ralf Schumacher",
        "Graham Hill",
        "Niki Lauda",
        "Jacques Villeneuve",
        "Johnny Herbert",
        "Martin Brundle",
        "Mika Häkkinen",
        "René Arnoux",
        "Thierry Boutsen",
        "Ayrton Senna",
        "Derek Warwick",
        "Heinz-Harald Frentzen",
        "Olivier Panis",
        "John Watson",
        "Emerson Fittipaldi",
        "Eddie Irvine",
        "Carlos Reutemann",
        "Eddie Cheever",
        "Jean-Pierre Jarier",
        "Clay Regazzoni",
        "Jack Brabham",
        "Mario Andretti",
        "Adrian Sutil",
        "Keke Rosberg",
        "Pierluigi Martini",
        "Ronnie Peterson",
        "Damon Hill",
        "Patrick Tambay",
        "Jacky Ickx",
        "Nico Hülkenberg",
        "Sergio Pérez",
        "Alan Jones",
        "Philippe Alliot",
        "Jochen Mass",
        "Daniel Ricciardo",
        "Jody Scheckter",
        "Denny Hulme",
        "Heikki Kovalainen",
        "John Surtees",
        "Mika Salo",
        "Piercarlo Ghinzani",
        "Elio de Angelis",
        "Jo Bonnier",
        "Romain Grosjean",
        "Jos Verstappen",
        "Pedro de la Rosa",
        "Chris Amon",
        "Bruce McLaren",
        "Stefan Johansson",
        "Jackie Stewart",
        "Jo Siffert",
        "Pedro Diniz",
        "Ivan Capelli",
        "Ukyo Katayama",
        "Pastor Maldonado",
        "Juan Pablo Montoya",
        "Patrick Depailler",
        "Timo Glock",
        "James Hunt",
        "Takuma Sato",
        "Aguri Suzuki",
        "Jonathan Palmer",
        "Marc Surer",
        "Dan Gurney",
        "Jean-Pierre Beltoise",
        "Maurice Trintignant",
        "Arturo Merzario",
        "Bertrand Gachot",
        "Bruno Giacomelli",
        "Valtteri Bottas",
        "Hans-Joachim Stuck",
        "Stefano Modena",
        "Maurício Gugelmin",
        "Satoru Nakajima",
        "Vitantonio Liuzzi",
        "Gabriele Tarquini",
        "Vittorio Brambilla",
        "Alessandro Nannini",
        "Kamui Kobayashi",
        "Robert Kubica",
        "Alex Caffi",
        "Nicola Larini",
        "Roberto Moreno",
        "Carlos Pace",
        "Stirling Moss",
        "Didier Pironi",
        "Jim Clark",
        "Gianni Morbidelli",
        "Jyrki Järvilehto",
        "Teo Fabi",
        "Alexander Wurz",
        "Gilles Villeneuve",
        "Derek Daly",
        "Harry Schell",
        "Daniil Kvyat",
        "Érik Comas",
        "Mark Blundell"
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

| # | Driver | Participations |
|--|--|--|
| 1. | [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 326 |
| 2. | [Jenson Button 🇬🇧](/f1/drivers/button) | 308 |
| 3. | [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 308 |
| 4. | [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 278 |
| 5. | [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 257 |
| 6. | [Riccardo Patrese 🇮🇹](/f1/drivers/patrese) | 257 |
| 7. | [Felipe Massa 🇧🇷](/f1/drivers/massa) | 256 |
| 8. | [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 256 |
| 9. | [David Coulthard 🇬🇧](/f1/drivers/coulthard) | 247 |
| 10. | [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 231 |
| 11. | [Mark Webber 🇦🇺](/f1/drivers/webber) | 217 |
| 12. | [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 215 |
| 13. | [Andrea de Cesaris 🇮🇹](/f1/drivers/cesaris) | 214 |
| 14. | [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 210 |
| 15. | [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 207 |
| 16. | [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 206 |
| 17. | [Alain Prost 🇫🇷](/f1/drivers/prost) | 202 |
| 18. | [Jean Alesi 🇫🇷](/f1/drivers/alesi) | 202 |
| 19. | [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 192 |
| 20. | [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 192 |
| 21. | [Nick Heidfeld 🇩🇪](/f1/drivers/heidfeld) | 184 |
| 22. | [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 183 |
| 23. | [Jacques Laffite 🇫🇷](/f1/drivers/laffite) | 180 |
| 24. | [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 180 |
| 25. | [Graham Hill 🇬🇧](/f1/drivers/hill) | 179 |
| 26. | [Niki Lauda 🇦🇹](/f1/drivers/lauda) | 174 |
| 27. | [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | 165 |
| 28. | [Johnny Herbert 🇬🇧](/f1/drivers/herbert) | 165 |
| 29. | [Martin Brundle 🇬🇧](/f1/drivers/brundle) | 165 |
| 30. | [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 165 |
| 31. | [René Arnoux 🇫🇷](/f1/drivers/arnoux) | 164 |
| 32. | [Thierry Boutsen 🇧🇪](/f1/drivers/boutsen) | 164 |
| 33. | [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 162 |
| 34. | [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 162 |
| 35. | [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | 159 |
| 36. | [Olivier Panis 🇫🇷](/f1/drivers/panis) | 158 |
| 37. | [John Watson 🇬🇧](/f1/drivers/watson) | 154 |
| 38. | [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | 149 |
| 39. | [Eddie Irvine 🇬🇧](/f1/drivers/irvine) | 147 |
| 40. | [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | 146 |
| 41. | [Eddie Cheever 🇺🇸](/f1/drivers/cheever) | 143 |
| 42. | [Jean-Pierre Jarier 🇫🇷](/f1/drivers/jarier) | 143 |
| 43. | [Clay Regazzoni 🇨🇭](/f1/drivers/regazzoni) | 138 |
| 44. | [Jack Brabham 🇦🇺](/f1/drivers/jack_brabham) | 129 |
| 45. | [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | 129 |
| 46. | [Adrian Sutil 🇩🇪](/f1/drivers/sutil) | 128 |
| 47. | [Keke Rosberg 🇫🇮](/f1/drivers/keke_rosberg) | 128 |
| 48. | [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 123 |
| 49. | [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 123 |
| 50. | [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 122 |
| 51. | [Patrick Tambay 🇫🇷](/f1/drivers/tambay) | 122 |
| 52. | [Jacky Ickx 🇧🇪](/f1/drivers/ickx) | 121 |
| 53. | [Nico Hülkenberg 🇩🇪](/f1/drivers/hulkenberg) | 121 |
| 54. | [Sergio Pérez 🇲🇽](/f1/drivers/perez) | 119 |
| 55. | [Alan Jones 🇦🇺](/f1/drivers/jones) | 117 |
| 56. | [Philippe Alliot 🇫🇷](/f1/drivers/alliot) | 115 |
| 57. | [Jochen Mass 🇩🇪](/f1/drivers/mass) | 114 |
| 58. | [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 113 |
| 59. | [Jody Scheckter 🇿🇦](/f1/drivers/scheckter) | 113 |
| 60. | [Denny Hulme 🇳🇿](/f1/drivers/hulme) | 112 |
| 61. | [Heikki Kovalainen 🇫🇮](/f1/drivers/kovalainen) | 112 |
| 62. | [John Surtees 🇬🇧](/f1/drivers/surtees) | 112 |
| 63. | [Mika Salo 🇫🇮](/f1/drivers/salo) | 111 |
| 64. | [Piercarlo Ghinzani 🇮🇹](/f1/drivers/ghinzani) | 111 |
| 65. | [Elio de Angelis 🇮🇹](/f1/drivers/angelis) | 110 |
| 66. | [Jo Bonnier 🇸🇪](/f1/drivers/bonnier) | 109 |
| 67. | [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 108 |
| 68. | [Jos Verstappen 🇳🇱](/f1/drivers/verstappen) | 107 |
| 69. | [Pedro de la Rosa 🇪🇸](/f1/drivers/rosa) | 107 |
| 70. | [Chris Amon 🇳🇿](/f1/drivers/amon) | 106 |
| 71. | [Bruce McLaren 🇳🇿](/f1/drivers/mclaren) | 103 |
| 72. | [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 103 |
| 73. | [Jackie Stewart 🇬🇧](/f1/drivers/stewart) | 100 |
| 74. | [Jo Siffert 🇨🇭](/f1/drivers/siffert) | 100 |
| 75. | [Pedro Diniz 🇧🇷](/f1/drivers/diniz) | 99 |
| 76. | [Ivan Capelli 🇮🇹](/f1/drivers/capelli) | 98 |
| 77. | [Ukyo Katayama 🇯🇵](/f1/drivers/katayama) | 97 |
| 78. | [Pastor Maldonado 🇻🇪](/f1/drivers/maldonado) | 96 |
| 79. | [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 95 |
| 80. | [Patrick Depailler 🇫🇷](/f1/drivers/depailler) | 95 |
| 81. | [Timo Glock 🇩🇪](/f1/drivers/glock) | 95 |
| 82. | [James Hunt 🇬🇧](/f1/drivers/hunt) | 93 |
| 83. | [Takuma Sato 🇯🇵](/f1/drivers/sato) | 91 |
| 84. | [Aguri Suzuki 🇯🇵](/f1/drivers/suzuki) | 88 |
| 85. | [Jonathan Palmer 🇬🇧](/f1/drivers/palmer) | 88 |
| 86. | [Marc Surer 🇨🇭](/f1/drivers/surer) | 88 |
| 87. | [Dan Gurney 🇺🇸](/f1/drivers/gurney) | 87 |
| 88. | [Jean-Pierre Beltoise 🇫🇷](/f1/drivers/beltoise) | 87 |
| 89. | [Maurice Trintignant 🇫🇷](/f1/drivers/trintignant) | 87 |
| 90. | [Arturo Merzario 🇮🇹](/f1/drivers/merzario) | 84 |
| 91. | [Bertrand Gachot 🇧🇪](/f1/drivers/gachot) | 84 |
| 92. | [Bruno Giacomelli 🇮🇹](/f1/drivers/giacomelli) | 82 |
| 93. | [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 82 |
| 94. | [Hans-Joachim Stuck 🇩🇪](/f1/drivers/stuck) | 81 |
| 95. | [Stefano Modena 🇮🇹](/f1/drivers/modena) | 81 |
| 96. | [Maurício Gugelmin 🇧🇷](/f1/drivers/gugelmin) | 80 |
| 97. | [Satoru Nakajima 🇯🇵](/f1/drivers/satoru_nakajima) | 80 |
| 98. | [Vitantonio Liuzzi 🇮🇹](/f1/drivers/liuzzi) | 80 |
| 99. | [Gabriele Tarquini 🇮🇹](/f1/drivers/tarquini) | 78 |
| 100. | [Vittorio Brambilla 🇮🇹](/f1/drivers/brambilla) | 78 |
| 101. | [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 77 |
| 102. | [Kamui Kobayashi 🇯🇵](/f1/drivers/kobayashi) | 76 |
| 103. | [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 76 |
| 104. | [Alex Caffi 🇮🇹](/f1/drivers/caffi) | 75 |
| 105. | [Nicola Larini 🇮🇹](/f1/drivers/larini) | 75 |
| 106. | [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 74 |
| 107. | [Carlos Pace 🇧🇷](/f1/drivers/pace) | 73 |
| 108. | [Stirling Moss 🇬🇧](/f1/drivers/moss) | 73 |
| 109. | [Didier Pironi 🇫🇷](/f1/drivers/pironi) | 72 |
| 110. | [Jim Clark 🇬🇧](/f1/drivers/clark) | 72 |
| 111. | [Gianni Morbidelli 🇮🇹](/f1/drivers/morbidelli) | 70 |
| 112. | [Jyrki Järvilehto 🇫🇮](/f1/drivers/lehto) | 70 |
| 113. | [Teo Fabi 🇮🇹](/f1/drivers/fabi) | 70 |
| 114. | [Alexander Wurz 🇦🇹](/f1/drivers/wurz) | 69 |
| 115. | [Gilles Villeneuve 🇨🇦](/f1/drivers/gilles_villeneuve) | 68 |
| 116. | [Derek Daly 🇮🇪](/f1/drivers/daly) | 64 |
| 117. | [Harry Schell 🇺🇸](/f1/drivers/schell) | 64 |
| 118. | [Daniil Kvyat 🇷🇺](/f1/drivers/kvyat) | 63 |
| 119. | [Érik Comas 🇫🇷](/f1/drivers/comas) | 63 |
| 120. | [Mark Blundell 🇬🇧](/f1/drivers/blundell) | 63 |

#### Statistic Summary

| **Column** | **Participations** |
| **Row Count** | 120 |
| **Total Sum** | 15739.000 |
| **Mean μ (Average)** | 131.158 |
| **Maximum** | 326.000 |
| **75th Percentile** | 165.000 |
| **Median** | 112.000 |
| **25th Percentile** | 84.000 |
| **Minimum** | 63.000 |
| **Variance** | 3555.900 |
| **Standard Deviation σ** | 59.631 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
