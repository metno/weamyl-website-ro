---
permalink: /modele/
title: "Rezultate"
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #2073ac;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>
</head>
<body>
<figure>
  <center><figcaption>Sistemul WeaMyL</figcaption></center>
  <img src="https://weamyl.met.no/assets/images/Container.png" alt="Sistemul WeaMyL" style="width:100%">
</figure>


<button type="button" class="collapsible"><h1>Modele de nowcasting</h1></button>
<div class="content">
<h2>NowCastX versiune 1.0.0</h2>

<p class="small" align="justify">NowCastX versiune 1.0.0 - <a href="https://ieeexplore.ieee.org/document/9118849">Model bazat pe arhitectura Xception</a>
antrenat pe un set de date conținând 45 de zile cu date radar <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>. Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivității compozite, folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.
</p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-5min-publ.mp4" type="video/mp4">
</video>
<p class="small" align="center">NowCastX 5 min - bazat pe datele radar disponibile face predicție pentru următoarele 5 minute. </p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-15min-publ.mp4" type="video/mp4">
</video>
<p class="small"align="center">NowCastX 15 min - bazat pe datele radar disponibile face predicție pentru următoarele 15 minute. </p>

<h2> NowcastX versiune 0.0.1</h2>
<p class="small" align="justify">NowCastX versiune 0.0.1 - Model preliminar bazat pe arhitectura Xception, antrenat pe un set de date conținând 6 zile cu fenomene meteorologice <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>, selectate din datele disponibile la <a href="https://api.met.no/weatherapi/metalerts/1.1?show=all&lang=en">weatherapi</a>. Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivității compozite după un interval de 5 minute folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow_5m_with_negative_5minutes_noRMSE_noCM.mp4" type="video/mp4">
</video>
</div>

<button type="button" class="collapsible"><h1>Atlasul adnotat de observații meteorologice</h1></button>
<div class="content">

<p class="small" align="justify">Această componentă oferă o interfață web unui motor de căutare conectat la o bază de date semantică care conține avertismente de vreme severă. Interfața web este ușor de utilizat și permite căutarea/filtrarea pentru diferite tipuri de evenimente meteorologice și, de asemenea, pentru anumite evenimente meteo. Interfața web oferă și posibilitatea de a investiga zone geografice afectate de evenimente adnotate și anterioare. În plus, oferă informații despre locația fișierelor de date sursă, oferind astfel suport în antrenarea modelelor de învățare automată pentru detectarea posibilelor evenimente meteo interesante.
</p>

<img src="https://weamyl.met.no/assets/images/Atlas.png"/>
</div>

<button type="button" class="collapsible"><h1>Platforma de prognoză</h1></button>
<div class="content">

<p class="small" align="justify">
Platforma de prognoză este formată din următoarele componente:</p>
<ul>
<li> <p class="small" align="justify"> GeoWeb - aplicație web folosită pentru a vizualiza diferite date meteorologice. Aceasta include rezultate de la algoritmul de învățare automată și avertismente CAP.</p></li>

<li style="small"><p class="small" align="justify">  WebMapService - Servicii care furnizează diferite date meteorologice, inclusiv imagini din satelit a modelului, date radar, observatii obtinute in timp real ca imagini care pot fi afișate pe o hartă. </p></li>

<li > <p class="small" align="justify">Algoritmi Machine Learning - realizează prognoze bazându-se pe producing forecasts based on the cele mai recente seturi de date radar înregistrate.</p></li>

<!--<li> <p class="small" align="justify"> WebMapServices - Services providing all kinds of meteorological data, including model output, satellite images, radar data, in situ observations, as images that can be displayed on a map.</p></li>-->

<li > <p class="small" align="justify"> Editorul CAP -
editor folosit de meteorolog pentru a furniza avertismente CAP.</p></li>

<li> <p class="small" align="justify"> CAP feed -  serviciu care furnizează toate avertismentele CAP emise.</p></li>

</ul>

<p class="small" align="justify">Mai jos este prezentat un exemplu de vizualizare a rezultatelor ML ca factor de reflectivitate echivalent prognozat (stânga) versus factor de reflectivitate echivalent observat (dreapta), folosind serviciul de cartografiere Open GeoWeb pentru evenimentul meteorologic din 08 aprilie 2022 la 18:05 UTC. Această vizualizare se bazează pe date asimilate la fiecare 5 până la 10 minute.</p>

<img src="https://weamyl.met.no/assets/images/demo_GeoWeb.png" />

<p class="small" align="justify">Video</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/GeoWeb_demo.mp4">
</video>

</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>



</body>
</html>
