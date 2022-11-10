---
permalink: /partners/
title: "Parteneri"
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

<h2>Membrii consorțiului</h2>
<button type="button" class="collapsible">Universitatea Babeș-Bolyai (UBB)</button>
<div class="content">

<p class="small" align="justify">Universitatea Babeș-Bolyai este o universitate publică românească, fiind astăzi cea mai mare universitate din România și una dintre cele mai bune și mai reprezentative universități românești. La nivel național, UBB a primit titlul de universitate de cercetare intensivă și a fost clasată ca cea mai bună universitate românească în metarankingul <a href="https://cwur.org/2019-2020.php">CWUR World University Rankings 2019-2020</a>. Echipa de cercetare Informatică de la UBB este un grup de cercetare în ML (<a href="www.cs.ubbcluj.ro/ml">MLyRE</a>) de la Facultatea de Matematică și Informatică format din membri cu înaltă expertiză și rezultate științifice valoroase în domeniul inteligenței artificiale, în special în ML. Vă rugăm să consultați <a href="https://metno.github.io/weamyl-website-ro/bbu_ro/">pagina partenerului</a> pentru mai multe detalii.</p>

<table style="width:100%">
  <tr>
    <td><img src="https://weamyl.met.no/assets/images/ubb/UBB7.png"></td>
    <td><img src="https://weamyl.met.no/assets/images/ubb/UBB2.png"></td>
  </tr>
  <tr>
  <td><img src="https://weamyl.met.no/assets/images/ubb/UBB5.png"></td>
  <td><img src="https://weamyl.met.no/assets/images/ubb/UBB1.png"></td>
</tr>
</table>
</div>

<button type="button" class="collapsible">Administrația Națională de Meteorologie (ANM)</button>
<div class="content">

<p class="small" align="justify">Administrația Națională de Meteorologie (ANM) este instituția română de meteorologie al cărei principal domeniu de activitate îl constituie observațiile meteorologice și climatologie necesare dezvoltării social-economice și integrării acestei activități în sistemul de convenții și relații internaționale. Cu scop principal în protecția vieților și a proprietății, are în responsabilitate emiterea avertizarilor cu privire la fenomenele meteorologice severe care ar putea pune în pericol siguranța publică. De asemenea, ANM oferă o gamă largă de servicii meteorologice operaționale pentru diferiți utilizatori din agricultură, navigație maritimă și aeriană, apărare națională, transport, energie, turism și mediu.</p>

<p class="small" align="justify">ANM deține o înaltă expertiză în cercetarea meteorologică (vreme severă, modelare numerică a vremii, variabilitatea climatică și schimbările climatice, fizica atmosferei și a poluării aerului, teledetecție și GIS) și domenii operaționale. În ceea ce privește educația și formarea, ANM este profund implicată în activități din cadrul Școlii Naționale de Meteorologie, precum și în cursuri de formare internaționale. Vă rugăm să consultați pagina partenerului <a href="https://metno.github.io/weamyl-website-ro/anm_ro/">pagina partenerului</a> pentru mai multe detalii.</p>

<table style="width:100%">
  <tr>
    <td><img src="https://weamyl.met.no/assets/images/anm/anm2.jpg"></td>
    <td><img src="https://weamyl.met.no/assets/images/anm/anm3.jpg"></td>
  </tr>
  <tr>
    <td><img src="https://weamyl.met.no/assets/images/anm/anm9.jpg"></td>
    <td><img src="https://weamyl.met.no/assets/images/anm/anm4.jpg"></td>
  </tr>

</table>

</div>
<button type="button" class="collapsible">Institutul Meteorologic Norvegian (MET Norvegia)</button>
<div class="content">

<p class="small" align="justify">Institutul Meteorologic Norvegian (MET Norvegia) este o agenție de stat din Norvegia, un centru internațional de expertiză responsabil pentru serviciile meteorologice publice în scopuri civile și militare. Acesta prognozează vremea, monitorizează clima și efectuează cercetări. MET Norvegia este implicată activ în activitatea OMM, a Centrului european pentru prognoze meteo pe distanțe medii și a Organizației europene pentru exploatarea sateliților meteorologici (EUMETSAT). Principalele activități de cercetare și dezvoltare includ cercetarea atmosferică, oceanică și climatologică și implică atât modele, cât și observații. MET Norvegia are, de asemenea, o lungă înregistrare a participării la programele de granturi regionale și SEE / Norvegia, în plus față de granturile UE, proiectele finanțate de organizații externe și proiectele finanțate de Consiliul Norvegian de Cercetare și de organizația nordică NordForsk. Vă rugăm să consultați <a href="https://metno.github.io/weamyl-website-ro/metno_ro/">pagina partenerului</a> pentru mai multe detalii.</p>



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
