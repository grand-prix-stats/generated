---
title: List of All Formula 1® Drivers that Have Raced in Japan by Number of Times
layout: page
collectionName: countries
collectionId: japan
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

| Driver | Times |
|--|--|
| [Michael Schumacher 🇩🇪](/f1/drivers/michael_schumacher) | 21 |
| [Rubens Barrichello 🇧🇷](/f1/drivers/barrichello) | 21 |
| [Jenson Button 🇬🇧](/f1/drivers/button) | 17 |
| [David Coulthard 🇬🇧](/f1/drivers/coulthard) | 15 |
| [Fernando Alonso 🇪🇸](/f1/drivers/alonso) | 15 |
| [Jarno Trulli 🇮🇹](/f1/drivers/trulli) | 14 |
| [Jean Alesi 🇫🇷](/f1/drivers/alesi) | 14 |
| [Kimi Räikkönen 🇫🇮](/f1/drivers/raikkonen) | 14 |
| [Felipe Massa 🇧🇷](/f1/drivers/massa) | 13 |
| [Gerhard Berger 🇦🇹](/f1/drivers/berger) | 13 |
| [Giancarlo Fisichella 🇮🇹](/f1/drivers/fisichella) | 13 |
| [Johnny Herbert 🇬🇧](/f1/drivers/herbert) | 13 |
| [Mark Webber 🇦🇺](/f1/drivers/webber) | 12 |
| [Mika Häkkinen 🇫🇮](/f1/drivers/hakkinen) | 12 |
| [Olivier Panis 🇫🇷](/f1/drivers/panis) | 12 |
| [Eddie Irvine 🇬🇧](/f1/drivers/irvine) | 11 |
| [Heinz-Harald Frentzen 🇩🇪](/f1/drivers/frentzen) | 11 |
| [Nico Rosberg 🇩🇪](/f1/drivers/rosberg) | 11 |
| [Ralf Schumacher 🇩🇪](/f1/drivers/ralf_schumacher) | 11 |
| [Lewis Hamilton 🇬🇧](/f1/drivers/hamilton) | 10 |
| [Nick Heidfeld 🇩🇪](/f1/drivers/heidfeld) | 10 |
| [Sebastian Vettel 🇩🇪](/f1/drivers/vettel) | 10 |
| [Aguri Suzuki 🇯🇵](/f1/drivers/suzuki) | 9 |
| [Damon Hill 🇬🇧](/f1/drivers/damon_hill) | 9 |
| [Jacques Villeneuve 🇨🇦](/f1/drivers/villeneuve) | 9 |
| [Ayrton Senna 🇧🇷](/f1/drivers/senna) | 8 |
| [Gianni Morbidelli 🇮🇹](/f1/drivers/morbidelli) | 8 |
| [Martin Brundle 🇬🇧](/f1/drivers/brundle) | 8 |
| [Michele Alboreto 🇮🇹](/f1/drivers/alboreto) | 8 |
| [Mika Salo 🇫🇮](/f1/drivers/salo) | 8 |
| [Riccardo Patrese 🇮🇹](/f1/drivers/patrese) | 8 |
| [Ukyo Katayama 🇯🇵](/f1/drivers/katayama) | 8 |
| [Adrian Sutil 🇩🇪](/f1/drivers/sutil) | 7 |
| [Andrea de Cesaris 🇮🇹](/f1/drivers/cesaris) | 7 |
| [Bertrand Gachot 🇧🇪](/f1/drivers/gachot) | 7 |
| [Jos Verstappen 🇳🇱](/f1/drivers/verstappen) | 7 |
| [Nigel Mansell 🇬🇧](/f1/drivers/mansell) | 7 |
| [Pedro Diniz 🇧🇷](/f1/drivers/diniz) | 7 |
| [Pierluigi Martini 🇮🇹](/f1/drivers/martini) | 7 |
| [Alain Prost 🇫🇷](/f1/drivers/prost) | 6 |
| [Daniel Ricciardo 🇦🇺](/f1/drivers/ricciardo) | 6 |
| [Heikki Kovalainen 🇫🇮](/f1/drivers/kovalainen) | 6 |
| [Mark Blundell 🇬🇧](/f1/drivers/blundell) | 6 |
| [Nico Hülkenberg 🇩🇪](/f1/drivers/hulkenberg) | 6 |
| [Nicola Larini 🇮🇹](/f1/drivers/larini) | 6 |
| [Pedro de la Rosa 🇪🇸](/f1/drivers/rosa) | 6 |
| [Romain Grosjean 🇫🇷](/f1/drivers/grosjean) | 6 |
| [Sergio Pérez 🇲🇽](/f1/drivers/perez) | 6 |
| [Takuma Sato 🇯🇵](/f1/drivers/sato) | 6 |
| [Thierry Boutsen 🇧🇪](/f1/drivers/boutsen) | 6 |
| [Timo Glock 🇩🇪](/f1/drivers/glock) | 6 |
| [Alex Caffi 🇮🇹](/f1/drivers/caffi) | 5 |
| [Derek Warwick 🇬🇧](/f1/drivers/warwick) | 5 |
| [Érik Comas 🇫🇷](/f1/drivers/comas) | 5 |
| [Juan Pablo Montoya 🇨🇴](/f1/drivers/montoya) | 5 |
| [Jyrki Järvilehto 🇫🇮](/f1/drivers/lehto) | 5 |
| [Maurício Gugelmin 🇧🇷](/f1/drivers/gugelmin) | 5 |
| [Nelson Piquet 🇧🇷](/f1/drivers/piquet) | 5 |
| [Pastor Maldonado 🇻🇪](/f1/drivers/maldonado) | 5 |
| [Pedro Lamy 🇵🇹](/f1/drivers/lamy) | 5 |
| [Robert Kubica 🇵🇱](/f1/drivers/kubica) | 5 |
| [Roberto Moreno 🇧🇷](/f1/drivers/moreno) | 5 |
| [Satoru Nakajima 🇯🇵](/f1/drivers/satoru_nakajima) | 5 |
| [Stefano Modena 🇮🇹](/f1/drivers/modena) | 5 |
| [Vitantonio Liuzzi 🇮🇹](/f1/drivers/liuzzi) | 5 |
| [Alexander Wurz 🇦🇹](/f1/drivers/wurz) | 4 |
| [Gabriele Tarquini 🇮🇹](/f1/drivers/tarquini) | 4 |
| [Ivan Capelli 🇮🇹](/f1/drivers/capelli) | 4 |
| [Kamui Kobayashi 🇯🇵](/f1/drivers/kobayashi) | 4 |
| [Karl Wendlinger 🇦🇹](/f1/drivers/wendlinger) | 4 |
| [Philippe Alliot 🇫🇷](/f1/drivers/alliot) | 4 |
| [Valtteri Bottas 🇫🇮](/f1/drivers/bottas) | 4 |
| [Alessandro Nannini 🇮🇹](/f1/drivers/nannini) | 3 |
| [Alessandro Zanardi 🇮🇹](/f1/drivers/zanardi) | 3 |
| [Bruno Senna 🇧🇷](/f1/drivers/bruno_senna) | 3 |
| [Christian Fittipaldi 🇧🇷](/f1/drivers/fittipaldi) | 3 |
| [Daniil Kvyat 🇷🇺](/f1/drivers/kvyat) | 3 |
| [David Brabham 🇦🇺](/f1/drivers/brabham) | 3 |
| [Eddie Cheever 🇺🇸](/f1/drivers/cheever) | 3 |
| [Emanuele Pirro 🇮🇹](/f1/drivers/pirro) | 3 |
| [Éric Bernard 🇫🇷](/f1/drivers/bernard) | 3 |
| [Esteban Gutiérrez 🇲🇽](/f1/drivers/gutierrez) | 3 |
| [Jaime Alguersuari 🇪🇸](/f1/drivers/alguersuari) | 3 |
| [Jean-Éric Vergne 🇫🇷](/f1/drivers/vergne) | 3 |
| [Jonathan Palmer 🇬🇧](/f1/drivers/palmer) | 3 |
| [Luca Badoer 🇮🇹](/f1/drivers/badoer) | 3 |
| [Marcus Ericsson 🇸🇪](/f1/drivers/ericsson) | 3 |
| [Olivier Grouillard 🇫🇷](/f1/drivers/grouillard) | 3 |
| [Paul di Resta 🇬🇧](/f1/drivers/resta) | 3 |
| [Piercarlo Ghinzani 🇮🇹](/f1/drivers/ghinzani) | 3 |
| [René Arnoux 🇫🇷](/f1/drivers/arnoux) | 3 |
| [Sakon Yamamoto 🇯🇵](/f1/drivers/yamamoto) | 3 |
| [Sébastien Buemi 🇨🇭](/f1/drivers/buemi) | 3 |
| [Stefan Johansson 🇸🇪](/f1/drivers/johansson) | 3 |
| [Taki Inoue 🇯🇵](/f1/drivers/inoue) | 3 |
| [Vitaly Petrov 🇷🇺](/f1/drivers/petrov) | 3 |
| [Yannick Dalmas 🇫🇷](/f1/drivers/dalmas) | 3 |
| [Alan Jones 🇦🇺](/f1/drivers/jones) | 2 |
| [Alex Yoong 🇲🇾](/f1/drivers/yoong) | 2 |
| [Andrea Montermini 🇮🇹](/f1/drivers/montermini) | 2 |
| [Bernd Schneider 🇩🇪](/f1/drivers/schneider) | 2 |
| [Carlos Sainz 🇪🇸](/f1/drivers/sainz) | 2 |
| [Charles Pic 🇫🇷](/f1/drivers/pic) | 2 |
| [Christian Klien 🇦🇹](/f1/drivers/klien) | 2 |
| [Christijan Albers 🇳🇱](/f1/drivers/albers) | 2 |
| [Clay Regazzoni 🇨🇭](/f1/drivers/regazzoni) | 2 |
| [Felipe Nasr 🇧🇷](/f1/drivers/nasr) | 2 |
| [Gunnar Nilsson 🇸🇪](/f1/drivers/nilsson) | 2 |
| [Hans Binder 🇦🇹](/f1/drivers/binder) | 2 |
| [Hans-Joachim Stuck 🇩🇪](/f1/drivers/stuck) | 2 |
| [Jacques Laffite 🇫🇷](/f1/drivers/laffite) | 2 |
| [James Hunt 🇬🇧](/f1/drivers/hunt) | 2 |
| [Jan Magnussen 🇩🇰](/f1/drivers/magnussen) | 2 |
| [Jean-Pierre Jarier 🇫🇷](/f1/drivers/jarier) | 2 |
| [Jochen Mass 🇩🇪](/f1/drivers/mass) | 2 |
| [Jody Scheckter 🇿🇦](/f1/drivers/scheckter) | 2 |
| [John Watson 🇬🇧](/f1/drivers/watson) | 2 |
| [Jules Bianchi 🇫🇷](/f1/drivers/jules_bianchi) | 2 |
| [Kazuki Nakajima 🇯🇵](/f1/drivers/nakajima) | 2 |
| [Kazuyoshi Hoshino 🇯🇵](/f1/drivers/hoshino) | 2 |
| [Kevin Magnussen 🇩🇰](/f1/drivers/kevin_magnussen) | 2 |
| [Luis Pérez-Sala 🇪🇸](/f1/drivers/sala) | 2 |
| [Marc Gené 🇪🇸](/f1/drivers/gene) | 2 |
| [Mario Andretti 🇺🇸](/f1/drivers/mario_andretti) | 2 |
| [Max Chilton 🇬🇧](/f1/drivers/chilton) | 2 |
| [Max Verstappen 🇳🇱](/f1/drivers/max_verstappen) | 2 |
| [Narain Karthikeyan 🇮🇳](/f1/drivers/karthikeyan) | 2 |
| [Noritake Takahara 🇯🇵](/f1/drivers/takahara) | 2 |
| [Oscar Larrauri 🇦🇷](/f1/drivers/larrauri) | 2 |
| [Patrick Depailler 🇫🇷](/f1/drivers/depailler) | 2 |
| [Paul Belmondo 🇫🇷](/f1/drivers/belmondo) | 2 |
| [Philippe Streiff 🇫🇷](/f1/drivers/streiff) | 2 |
| [Ricardo Rosset 🇧🇷](/f1/drivers/rosset) | 2 |
| [Ricardo Zonta 🇧🇷](/f1/drivers/zonta) | 2 |
| [Robert Doornbos 🇳🇱](/f1/drivers/doornbos) | 2 |
| [Ronnie Peterson 🇸🇪](/f1/drivers/peterson) | 2 |
| [Shinji Nakano 🇯🇵](/f1/drivers/nakano) | 2 |
| [Tiago Monteiro 🇵🇹](/f1/drivers/monteiro) | 2 |
| [Toranosuke Takagi 🇯🇵](/f1/drivers/takagi) | 2 |
| [Vittorio Brambilla 🇮🇹](/f1/drivers/brambilla) | 2 |
| [Adrián Campos 🇪🇸](/f1/drivers/campos) | 1 |
| [Alex Ribeiro 🇧🇷](/f1/drivers/ribeiro) | 1 |
| [Alexander Rossi 🇺🇸](/f1/drivers/rossi) | 1 |
| [Allan McNish 🇬🇧](/f1/drivers/mcnish) | 1 |
| [Anthony Davidson 🇬🇧](/f1/drivers/davidson) | 1 |
| [Antônio Pizzonia 🇧🇷](/f1/drivers/pizzonia) | 1 |
| [Arturo Merzario 🇮🇹](/f1/drivers/merzario) | 1 |
| [Carlos Pace 🇧🇷](/f1/drivers/pace) | 1 |
| [Carlos Reutemann 🇦🇷](/f1/drivers/reutemann) | 1 |
| [Christian Danner 🇩🇪](/f1/drivers/danner) | 1 |
| [Cristiano da Matta 🇧🇷](/f1/drivers/matta) | 1 |
| [Emanuele Naspetti 🇮🇹](/f1/drivers/naspetti) | 1 |
| [Emerson Fittipaldi 🇧🇷](/f1/drivers/emerson_fittipaldi) | 1 |
| [Enrico Bertaggia 🇮🇹](/f1/drivers/bertaggia) | 1 |
| [Enrique Bernoldi 🇧🇷](/f1/drivers/bernoldi) | 1 |
| [Eric van de Poele 🇧🇪](/f1/drivers/poele) | 1 |
| [Esteban Ocon 🇫🇷](/f1/drivers/ocon) | 1 |
| [Esteban Tuero 🇦🇷](/f1/drivers/tuero) | 1 |
| [Franck Lagorce 🇫🇷](/f1/drivers/lagorce) | 1 |
| [Gastón Mazzacane 🇦🇷](/f1/drivers/mazzacane) | 1 |
| [Gianmaria Bruni 🇮🇹](/f1/drivers/bruni) | 1 |
| [Giedo van der Garde 🇳🇱](/f1/drivers/garde) | 1 |
| [Gilles Villeneuve 🇨🇦](/f1/drivers/gilles_villeneuve) | 1 |
| [Giovanni Lavaggi 🇮🇹](/f1/drivers/lavaggi) | 1 |
| [Harald Ertl 🇦🇹](/f1/drivers/ertl) | 1 |
| [Hideki Noda 🇯🇵](/f1/drivers/noda) | 1 |
| [Jan Lammers 🇳🇱](/f1/drivers/lammers) | 1 |
| [Jean-Christophe Boullion 🇫🇷](/f1/drivers/boullion) | 1 |
| [Jean-Marc Gounon 🇫🇷](/f1/drivers/gounon) | 1 |
| [Jérôme d'Ambrosio 🇧🇪](/f1/drivers/ambrosio) | 1 |
| [Jolyon Palmer 🇬🇧](/f1/drivers/jolyon_palmer) | 1 |
| [Julian Bailey 🇬🇧](/f1/drivers/bailey) | 1 |
| [Justin Wilson 🇬🇧](/f1/drivers/wilson) | 1 |
| [Kunimitsu Takahashi 🇯🇵](/f1/drivers/takahashi) | 1 |
| [Larry Perkins 🇦🇺](/f1/drivers/perkins) | 1 |
| [Lucas di Grassi 🇧🇷](/f1/drivers/grassi) | 1 |
| [Masahiro Hasemi 🇯🇵](/f1/drivers/hasemi) | 1 |
| [Naoki Hattori 🇯🇵](/f1/drivers/hattori) | 1 |
| [Nelson Piquet Jr. 🇧🇷](/f1/drivers/piquet_jr) | 1 |
| [Nicolas Kiesa 🇩🇰](/f1/drivers/kiesa) | 1 |
| [Niki Lauda 🇦🇹](/f1/drivers/lauda) | 1 |
| [Olivier Beretta 🇲🇨](/f1/drivers/beretta) | 1 |
| [Paolo Barilla 🇮🇹](/f1/drivers/barilla) | 1 |
| [Pascal Wehrlein 🇩🇪](/f1/drivers/wehrlein) | 1 |
| [Patrick Tambay 🇫🇷](/f1/drivers/tambay) | 1 |
| [Pierre-Henri Raphanel 🇫🇷](/f1/drivers/raphanel) | 1 |
| [Ralph Firman 🇮🇪](/f1/drivers/firman) | 1 |
| [Roland Ratzenberger 🇦🇹](/f1/drivers/ratzenberger) | 1 |
| [Scott Speed 🇺🇸](/f1/drivers/speed) | 1 |
| [Sébastien Bourdais 🇫🇷](/f1/drivers/bourdais) | 1 |
| [Tarso Marques 🇧🇷](/f1/drivers/marques) | 1 |
| [Teo Fabi 🇮🇹](/f1/drivers/fabi) | 1 |
| [Tom Pryce 🇬🇧](/f1/drivers/pryce) | 1 |
| [Tomáš Enge 🇨🇿](/f1/drivers/enge) | 1 |
| [Tony Trimmer 🇬🇧](/f1/drivers/trimmer) | 1 |
| [Toshio Suzuki 🇯🇵](/f1/drivers/toshio_suzuki) | 1 |
| [Will Stevens 🇬🇧](/f1/drivers/stevens) | 1 |
| [Zsolt Baumgartner 🇭🇺](/f1/drivers/baumgartner) | 1 |

#### Statistic Summary

| **Column** | **Times** |
| **Row Count** | 198 |
| **Total Sum** | 814.000 |
| **Mean μ (Average)** | 4.111 |
| **Maximum** | 21.000 |
| **75th Percentile** | 6.000 |
| **Median** | 2.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 15.846 |
| **Standard Deviation σ** | 3.981 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})
