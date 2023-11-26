---
permalink: /modele1/
title: "Modele"
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



<h2>Modele de învățare profundă pentru Platforma de predicție</h2>

<button type="button" class="collapsible">MET - Modele de învățare profundă pe date radar</button>
<div class="content">



<h3>XNow 3.0.0</h3>
<p class="small" align="justify">XNow 3.0.0 - ansamblu de tipul Xception cu 3 modele antrenate pe un set de date  conținând 102 zile de date radar (thredds). Fiecare model a fost antrenat pe o region de aproximativ 300km x 300km în jurul orașului Oslo pentru predicția valorilor reflectivității composite din viitor, utilizând valorile radar curente și o funcție loss îmbunătățită. Ziua utilizată pentru ilustrarea predicțiilor nu a fost utilizată în antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/V5_102Days.mp4" >
</video>

<h3>XNow 2.0.4</h3>
<p class="small" align="justify">XNow 2.0.4 - ansamblu de tipul Xception cu 3 modele antrenate pe un set de date  conținând 45 de zile de date radar (thredds). Fiecare model a fost antrenat pe o region de aproximativ 300km x 300km în jurul orașului Oslo pentru predicția valorilor reflectivității composite din viitor, utilizând valorile radar curente și o funcție loss îmbunătățită. Ziua utilizată pentru ilustrarea predicțiilor nu a fost utilizată în antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/V4_new_01_07_2021.mp4" >
</video>

<h3>XNow 2.0.3</h3>
<p class="small" align="justify">XNow 2.0.3 - ansamblu de tipul Xception cu 3 modele antrenate pe un set de date  conținând 45 de zile de date radar (thredds). Fiecare model a fost antrenat pe o region de aproximativ 300km x 300km în jurul orașului Oslo pentru predicția valorilor reflectivității composite din viitor, utilizând valorile radar curente și o funcție loss îmbunătățită. Ziua utilizată pentru ilustrarea predicțiilor nu a fost utilizată în antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/V3_old_01_07_2021.mp4" type="video/mp4" >
</video>



<h3> XNow versiune 1.0.0</h3>

<p class="small" align="justify">XNow 1.0.0 - <a href="https://ieeexplore.ieee.org/document/9118849">Xception-based model</a> antrenat pe un set de date conținând 45 de zile de date radar <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>. Fiecare model a fost antrenat pe o region de aproximativ 300km x 300km în jurul orașului Oslo pentru predicția valorilor reflectivității composite din viitor, utilizând valorile radar curente și o funcție loss îmbunătățită. Ziua utilizată pentru ilustrarea predicțiilor nu a fost utilizată în antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-5min-publ.mp4" type="video/mp4">
</video>
<p class="small">XNow 5 min - pe baza datelor radar disponibile în prezent, prezice valorile radar cu anticipație de 5 minute. </p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-15min-publ.mp4" type="video/mp4">
</video>
<p class="small">XNow 15 min -  pe baza datelor radar disponibile în prezent, prezice valorile radar cu anticipație de 15 minute. </p>

<h3> XNow versiune 0.0.1</h3>

<p class="small" align="justify">XNow versiune 0.0.1 - Model preliminar bazat pe arhitectura Xception, antrenat pe un set de date conținând 6 zile cu fenomene meteorologice <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>, selectate din datele disponibile la <a href="https://api.met.no/weatherapi/metalerts/1.1?show=all&lang=en">weatherapi</a>. Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivității compozite după un interval de 5 minute folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow_5m_with_negative_5minutes_noRMSE_noCM.mp4" type="video/mp4" >
</video>

</div>


<button type="button" class="collapsible">ANM - Modele de învățare profundă pe date radar</button>
<div class="content">

<h3>SepConv 2.0.0</h3>
<p class="small" align="justify">SepConv 2.0.0 - Ansamblu bazat pe Rețea Neuronală Convoluțională Separabilă de 3 modele antrenate pe un set de date care conține 211 zile cu evenimente convective (din 2020, 2021 și 2022) care au avut loc în centrul României, pe o zonă definită de o rază de 230 km față de locul radar. Pentru a prezice reflectivitatea maximă pentru 6 până la 48 de minute înainte, modelul utilizează reflectivitatea radar de la patru marcaje de timp anterioare ca intrare. Exemplele de mai jos arată comparația de predicție radar - model DL pentru 7 mai 2023, pentru un interval de 22,7 ore (6 min înainte) și, respectiv, 22,3 ore (20 min înainte).
 </p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/anm_V2_wl32_3ani_6min.mp4" type="video/mp4" >
</video>
<p class="small">SepConv 2.0.0 6 min - pe baza datelor radar disponibile în prezent, prezice valorile maxime de reflectivitate cu 6 minute înainte.</p>

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/anm_V2_wl32_3ani_20min.mp4" type="video/mp4" >
</video>
<p class="small">SepConv 2.0.0 20 min - pe baza datelor radar disponibile în prezent, prezice valorile maxime de reflectivitate cu 6 minute înainte.</p>

<h3>SepConv 1.0.0</h3>
<p class="small" align="justify">SepConv 1.0.0 - Model îmbunătățit bazat pe rețea neuronală convoluțională separabilă, antrenat folosind o pierdere ponderată personalizată pe un set de date care conține 20 de zile cu evenimente convective care au avut loc în centrul României, pe o zonă definită cu o rază de 230 km față de locul radar. Pentru a prezice reflectivitatea maximă pentru următoarea scanare (~ 6 minute), modelul DL utilizează reflectivitatea radar de la patru marcaje temporale anterioare ca intrare. Ziua folosită pentru ilustrarea predicțiilor de reflectivitate maximă a radarului nu a fost folosită pentru antrenament. Exemplul de mai jos arată comparația de predicții radar - model DL pentru 22,5 ore (7 mai 2023).</p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/anm_V2_wl32.mp4" type="video/mp4" >
</video>

<h3>SepConv 0.0.1</h3>
<p class="small" align="justify">SepConv 0.0.1 - Model bazat pe rețea neuronală convoluțională convoluțională incipientă antrenat pe un set de date care conține 20 de zile cu evenimente convective care au avut loc în centrul României. Setul de date radar utilizat pentru antrenament constă în reflectivitate radar eșantionată la 6 unghiuri de elevație, în timp ce rezultatul modelului de învățare profundă (DL) constă în reflectivitate radar maximă, calculată din toate cele 6 cote, pentru fiecare celulă de grilă, pe o zonă definită de un 230. km rază față de locul radar. Pentru a prezice reflectivitatea maximă pentru următoarea scanare (~ 6 minute), modelul DL utilizează reflectivitatea radar de la patru marcaje temporale anterioare ca intrare. Ziua folosită pentru ilustrarea predicțiilor de reflectivitate maximă a radarului nu a fost folosită pentru antrenament. Exemplul de mai jos arată comparația de predicție radar - model DL pentru un interval de timp de două ore.</p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/anm_V1_xnow.mp4" >
</video>
</div>

<button type="button" class="collapsible">Modele de învățare profundă pe date satelit </button>
<div class="content">
<h3>ConvSNow 1.0.0</h3>

<p class="small" align="justify"> ConvSNow versiunea 1.0.0 - Model LSTM convoluțional antrenat pe imagini satelit din Europa colectate de satelitul Meteosat-11 de la EUMESAT, utilizând produsul Severe Storms RGB.Modelul a fost antrenat în data de 24 iunie 2021. Datele folosite pentru ilustrarea predictiilor aparțin unei zile din iunie care nu a fost utilizată in antrenare.</p>

<img src="https://weamyl.met.no/assets/images/ConvSNow.gif" style="width:50%">

<p class="small" align="justify">ConvSNow 15 min - pe baza datelor satelit disponibile face predicție pentru produsul Severe Storms RGB pentru următoarele 15 minute. Animația din partea superioară reprezintă predicția modelului, iar animația din partea inferioară reprezintă observația actuală (reală).</p>



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
