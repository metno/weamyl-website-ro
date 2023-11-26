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
<a href="https://metno.github.io/weamyl-website-ro/modele1"><button type="button">Modele de învățare profundă pentru platforma de prognoză</button></a>
<h2>Sistemul WeaMyL</h2>

<figure>
  <center><figcaption>Sistemul WeaMyL</figcaption></center>
  <img src="https://weamyl.met.no/assets/images/Container.png" alt="Sistemul WeaMyL" style="width:100%">
</figure>



<button type="button" class="collapsible"><h1>Platforma de prognoză</h1></button>
<div class="content">

<p class="small" align="justify">
Platforma de prognoză este formată din următoarele componente:</p>
<ul>
<li> <p class="small" align="justify"> GeoWeb - aplicație web folosită pentru a vizualiza diferite date meteorologice. Aceasta include rezultate de la algoritmul de învățare automată și avertismente CAP.</p></li>

<li style="small"><p class="small" align="justify">  WebMapService - Servicii care furnizează diferite date meteorologice, inclusiv imagini din satelit a modelului, date radar, observatii obtinute in timp real ca imagini care pot fi afișate pe o hartă. </p></li>

<li > <p class="small" align="justify"><a href="https://weamyl.met.no/models1">Algoritmi Machine Learning</a> - realizează prognoze bazându-se cele mai recente seturi de date radar înregistrate.</p></li>

<!--<li> <p class="small" align="justify"> WebMapServices - Services providing all kinds of meteorological data, including model output, satellite images, radar data, in situ observations, as images that can be displayed on a map.</p></li>-->

<li > <p class="small" align="justify"> Editorul CAP - editor folosit de meteorolog pentru a furniza avertismente CAP.</p></li>

<li> <p class="small" align="justify"> CAP feed -  serviciu care furnizează toate avertismentele CAP emise.</p></li>

</ul>

<!--<p class="small" align="justify">Mai jos este prezentat un exemplu de vizualizare a rezultatelor ML ca factor de reflectivitate echivalent prognozat (stânga) versus factor de reflectivitate echivalent observat (dreapta), folosind serviciul de cartografiere Open GeoWeb pentru evenimentul meteorologic din 08 aprilie 2022 la 18:05 UTC. Această vizualizare se bazează pe date asimilate la fiecare 5 până la 10 minute.</p>

<img src="https://weamyl.met.no/assets/images/demo_GeoWeb.png" />

<p class="small" align="justify"><b>Video 1.</b> Un exemplu care ilustrează rezultatul ML ca prognoză (stânga) față de factorul de reflectivitate echivalent observat (dreapta) folosind serviciul de cartografiere Open GeoWeb pentru evenimentul meteorologic din 08 aprilie 2022 la 18:05 UTC. Acest videoclip este generat pe baza datelor asimilate la fiecare 5 până la 10 minute.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/GeoWeb_demo.mp4">
</video>

</div>-->
<p class="small" align="justify"><b>Video 1.</b> Videoclipul prezintă o comparație paralelă a reflectivității compozite reale, derivate din datele captate de radarul meteorologic Bobohalma (afișat în panoul din stânga) și reflectivitatea compozită prezisă generată de modelul WeaMyL, utilizând în special algoritmul de predicție SepConv 2.0.0. Acest videoclip este creat prin Visual Weather, software-ul de vizualizare operațională utilizat de Administrația Română de Meteorologie. Evenimentul prezentat a avut loc pe 15 noiembrie 2023, cu date colectate între orele 0:36 și 9:03 UTC. Este de remarcat faptul că absența datelor din sectorul azimut se datorează unei setări radar concepute pentru a limita volumul de scanare; această restricție este doar temporară și rezultă din instalarea în curs de desfășurare a unui nou radar meteorologic la fața locului.	</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/weamyl_video.mp4" type="video/mp4">
</video>
<br><br>
<p class="small" align="justify"><b>Video 2.</b> Un exemplu ilustrând factorul echivalent de reflectivitate observat (stânga) versus predicția XNow 1.0.0 (mijloc) versus predicția XNow 2.0.3 (dreapta) utilizând serviciul de cartografiere Open GeoWeb pentru evenimente meteo în data de 28 iunie 2022 la ora 09:55 UTC. Acest videoclip este generat folosind modelele, deoarece platforma este destinată să fie utilizată de meteorologi pentru a analiza vremea în 60 de minute în viitor.	</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/video29mar.mp4" type="video/mp4">
</video>
<br><br>
<p class="small" align="justify"><b>Video 3.</b> Acest clip a fost generat utilizând modelul XNow versiune 0.0.1, deoarece platforma este destinată analizării de către meteorologi a vremii cu anticipație de 5 minute.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/GeoWeb_demo.mp4" type="video/mp4">
</video>


</div>



<button type="button" class="collapsible"><h1>Atlasul adnotat de observații meteorologice</h1></button>
<div class="content">

<p class="small" align="justify">Această componentă oferă o interfață web unui motor de căutare conectat la o bază de date semantică care conține avertismente de vreme severă. Interfața web este ușor de utilizat și permite căutarea/filtrarea pentru diferite tipuri de evenimente meteorologice și, de asemenea, pentru anumite evenimente meteo. Interfața web oferă și posibilitatea de a investiga zone geografice afectate de evenimente adnotate și anterioare. În plus, oferă informații despre locația fișierelor de date sursă, oferind astfel suport în antrenarea modelelor de învățare automată pentru detectarea posibilelor evenimente meteo interesante. Figura 1 ilustrează interfața grafică a Atlasului Adnotat implementat la MET.
</p>
<figure>
<img src="https://weamyl.met.no/assets/images/atlas1.png"/>
<center><figcaption><b>Figura 1.</b> Interfața grafică a Atlasului Adnotat implementat la MET</figcaption></center>
</figure>
<br>
<p class="small" align="justify">La ANM, interfața grafică a Atlasului Adnotat a fost implementată cu succes pe un server dedicat (Figura 2).</p>
<figure>
<img src="https://weamyl.met.no/assets/images/atlas2.png"/>
<center><figcaption><b>Figura 2.</b> Interfața grafică a Atlasului Adnotat implementat la ANM</figcaption></center>
</figure>
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
