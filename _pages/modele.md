---
permalink: /modele/
title: "Modele de nowcasting"
---
## NowCastX versiune 1.0.0

<p class="small">NowCastX versiune 1.0.0 - <a href="https://ieeexplore.ieee.org/document/9118849">Xception-based model</a>
antrenat pe un set de date conținând 45 de zile cu date radar <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>. Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivității compozite, folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.
</p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-5min-publ.mp4" type="video/mp4">
</video>
<p class="small">NowCastX 5 min - bazat pe datele radar disponibile face predicție pentru următoarele 5 minute. </p>
<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow-4steps-15min-publ.mp4" type="video/mp4">
</video>
<p class="small">NowCastX 15 min - bazat pe datele radar disponibile face predicție pentru următoarele 15 minute. </p>

## NowcastX versiune 0.0.1
<p class="small">NowCastX versiune 0.0.1 - Model preliminar bazat pe arhitectura Xception, antrenat pe un set de date conținând 6 zile cu fenomene meteorologice <a href="https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html">(thredds)</a>, selectate din datele disponibile la <a href="https://api.met.no/weatherapi/metalerts/1.1?show=all&lang=en">weatherapi</a>. Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivității compozite după un interval de 5 minute folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.

<video width="100%" controls>
  <source src="https://weamyl.met.no/assets/videos/xnow_5m_with_negative_5minutes_noRMSE_noCM.mp4" type="video/mp4">
</video>
