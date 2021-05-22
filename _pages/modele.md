---
permalink: /modele/
title: "Modele de nowcasting"
---


## NowcastX versiune 0.0.1
NowCastX versiune 0.0.1 - Model preliminar bazat pe arhitectura Xception, antrenat pe un set de date conținând 6 zile cu fenomene meteorologice [(thredds)](https://thredds.met.no/thredds/catalog/remotesensing/reflectivity-nordic/catalog.html), selectate din datele disponibile la [weatherapi](https://api.met.no/weatherapi/metalerts/1.1?show=all&lang=en). Modelul a fost antrenat pe o regiune de aproximativ 300km x 300km din jurul orașului Oslo, pentru predicția reflectivitatății compozite după un interval de 5 minute folosind datele înregistrate pentru momentul actual. Ziua utilizată pentru ilustrarea predicțiilor nu a fost folosită la antrenare.

<video width="130%" controls>
  <source src="/assets/videos/xnow_5m_with_negative_5minutes_noRMSE_noCM.mp4" type="video/mp4">
</video>
