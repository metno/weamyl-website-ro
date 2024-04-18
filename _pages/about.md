---
permalink: /about/
title: "Despre proiectul WeaMyL"
---

<p align="justify"><small>Proiectul WeaMyL și-a propus să îmbunătățească acuratețea, performanța și fiabilitatea sistemelor naționale de avertizare <i>nowcasting</i> prin utilizarea tehnicilor de învățare automată (ML) aplicate pe observațiile obținute de la radar, satelit și stații meteo. Accentul s-a pus pe obținerea unei precizii mai mari în prezicerea apariției și a zonelor afectate de fenomene meteorologice severe, precum și pe obținerea unor timpi de decizie mai mici (în comparație cu timpi de decizie actuali, exclusiv umani). Scopul principal al proiectului a fost de a automatiza sistemele de avertizare <i>nowcasting</i> prin crearea unei platforme bazate pe ML pentru prognoza timpurie și precisă a fenomenelor severe. Astfel, s-a urmărit să fie baza unui nou cadru pentru detectarea iminentă a vremii severe, adaptat posibilităților tehnologice actuale.</small></p>

## Obiective principale

<small>Principalele obiective ale proiectului au fost următoarele:</small>
<ul>
<li><p align="justify"><small>Dezvoltarea și validarea științifică a noilor modele și tehnici de calcul ML adaptate special pentru <i>nowcasting</i> de precizie. <!--Modele de învățare nesupervizate (UL), cum ar fi analiza componentelor principale, _clustering_ și _autoencodere_ sunt avute în vedere ca instrumente inteligente pentru analiza mai multor surse de date, care pot fi relevante pentru _nowcasting_: date meteorologice (radar, satelit, observațiile stațiilor meteorologice) și datele geografice (altitudine, expunere, vegetație, elemente hidrologice, elemente antropice). În urma analizei datelor în mod nesupervizat, vor fi dezvoltate atât metode de învățare supervizate online, cât și off-line, cum ar fi rețelele neuronale convoluționale, rețelele U, rețelele de tip LSTM, XGBoost și mașinile restricționate Boltzmann, pentru a ajuta meteorologii să furnizeze alerte precise de _nowcasting_.--></small></p></li>


<li><p align="justify"><small>Dezvoltarea și evaluarea de către utilizator a Atlasului adnotat de observații meteorologice, o bază de date mare care conține date meteorologice (radar, satelit și alte observații meteorologice relevante) fiind utilizată ca sursă de date pentru tehnicile de învățare profundă dezvoltate în cadrul proiectului (extragerea, prelucrarea și clasificarea datelor). <!--După finalizarea proiectului, Atlasul adnotat va fi disponibil pentru analize de date meteorologice, redactări  de lucrări științifice, instruire a personalului și diseminarea publică a datelor meteorologice. Atlasul va oferi:
  1. gestionarea observațiilor meteorologice adnotate (adăugarea, actualizarea, salvarea, încărcarea, adnotarea și validarea înregistrărilor meteorologice) și
  2. tehnici inteligente de recuperare a informațiilor pentru recuperarea informațiilor istorice relevante pentru meteorologi în timp real. Aceasta include identificarea timpurie a zonelor predispuse la inițierea convecției pe baza datelor statistice, precum și identificarea modelelor de furtună convectivă pe baza datelor istorice. Diferite interogări și vizualizări pentru observații specifice vor fi accesibile și le vor include pe cele furnizate de metodele nesupervizate dezvoltate ca parte a O1 împreună cu diferite rezultate de raportare.--></small></p></li>


<li><p align="justify"><small>Dezvoltarea platformei open-source WeaMyL pentru prognoza timpurie a fenomenelor meteorologice severe. Obiectivul a fost de a oferi o platformă de prognoză bazată pe <i>big data</i>, care să includă metodele de învățare supervizată dezvoltate și care să sprijine meteorologii în îmbunătățirea calității alertelor emise acum.</small></p></li>

<!--* Integrarea platformei WeaMyL în cadrul sistemelor naționale de avertizare meteorologică din Norvegia și România. Platforma WeaMyL va fi integrată cu sistemele software relevante ale Serviciilor Meteorologice Naționale. Această integrare va facilita în mod direct activitatea meteorologilor, asistându-i în procesul de decizie _nowcasting_ și va accelera procedurile de emitere a alertelor.-->

<li><p align="justify"><small>Contribuția la dezvoltarea cunoștințelor științifice prin diseminarea rezultatelor științifice obținute prin publicații științifice, site-ul web al proiectului și social media.</small></p></li>
</ul>

## Platforma software WeaMyL

<p align="justify"><small>Platforma software WeaMyL este formată din trei componente:</small></p>
<ul>
<li><p align="justify"><small><b>Platformă de prognoză.</b> Având în vedere că acuratețea modulului de predicție este primordială pentru precizia sistemului, aceasta este componenta centrală a WeaMyL. Platforma de prognoză utilizează atât date istorice cât și date în timp real și este responsabilă cu estimarea locației, a timpului și a gravității fenomenelor meteorologice care se așteaptă să aibă loc în viitorul apropiat (0-6 ore). Algoritmii noștri modelează situația meteorologică pe baza situațiilor meteorologice anterioare. Modelele de învățare antrenate găsesc modele în datele meteorologice care se aplică circumstanțelor specifice și astfel se îmbunătățesc pe măsură ce devin disponibile din ce în ce mai multe date, făcând astfel modulul de prognoză autoadaptativ. Pentru a procesa cantitatea disponibilă de date meteorologice și pentru a accelera analiza științifică și extragerea informațiilor, au fost vizate abordările <i>big data</i>.</small></p></li>

<li><p align="justify"><small><b>Atlas adnotat de observații meteorologice.</b> Componenta Atlas adnotat furnizează o bază de date semantică asupra volumului mare de date istorice din surse variate, inclusiv observațiile stațiilor meteo, radar și imagini prin satelit. Principalele sale obiective au fost de a facilita studiul condițiilor din trecut utilizând analize statistice și comparative, furnizarea de informații inteligente bazate pe un model de date semantice și furnizarea unui model de adnotare personalizat, extensibil, între tipurile și sursele de observație. Componenta Atlas oferă două funcționalități principale: (a) gestionarea Atlasului și (b) vizualizări, statistici și rapoarte bazate pe datele meteorologice istorice stocate în Atlas.</small></p></li>

<li><p align="justify"><small><b>Modul de integrare.</b> Pentru ca componentele de mai sus să ofere informații acționabile, acestea au fost integrate cu sistemele software existente. Scopul acestui modul este de a oferi o serie de conectori pentru consumatori și furnizori de date care pot fi integrați în sistemele existente. Atât Platforma de prognoză, cât și Atlasul adnotat acționează drept consumatori pentru datele meteorologice generate în timp real, în timp ce platforma de prognoză furnizează date relevante pentru vremea severă viitoare.</small></p></li>
</ul>


## Pachete de lucru

<p align="justify"><small>Programul de lucru a fost împărțit în cinci pachete de lucru (WPs), urmând etapele obișnuite necesare pentru atingerea principalului obiectiv de cercetare, și anume dezvoltarea platformei software WeaMyL. Acestea sunt:</small></p>

### WP1 - Documentație, cerințe de sistem și arhitectură
<p align="justify"><small>În acest pachet de lucru, am efectuat mai întâi o documentare, un studiu și analize de literatură. Apoi, am identificat limitările abordărilor și soluțiilor de ultimă generație existente în tehnologia <i>nowcasting</i>. Ulterior, ne-am propus să definim cerințele funcționale și nefuncționale pentru WeaMyL, inclusiv cerințele utilizatorului final, precum și principalele condiții pentru buna funcționare a sistemului, pentru a stabili arhitectura generală și proiectarea platformei software WeaMyL.</small></p>

### WP2 - Modele de învățare automată pentru nowcasting
<p align="justify"><small>Cel de-al doilea pachet de lucru a constat în definirea unui model teoretic pentru <i>nowcasting</i> împreună cu (2) Dezvoltarea de modele ML scalabile special adaptate pentru <i>nowcasting</i> precis. (3) Validarea științifică a modelelor ML dezvoltate utilizând analiza și interpretarea rezultatelor experimentale, precum și comparația cu alte abordări din literatură.</small></p>

### WP3 - Dezvoltare software, testare și integrare
<p align="justify"><small>WP3 s-a concentrat pe dezvoltarea de software, testarea și integrarea platformei cu sistemele naționale de avertizare. Platforma de prognoză este alcătuită din componentele ML (accesibile printr-un API) împreună cu front-end-ul. S-a depus un efort privind integrarea WeaMyL cu sistemele naționale de avertizare. Prototipul platformei a fost dezvoltat într-o manieră incrementală, iterativă, având ca obiectiv final integrarea cu succes în sistemele de avertizare meteorologică din România și Norvegia.</small></p>


### WP4 - Evaluare, interpretare și analiză meteorologică
<p align="justify"><small>Activitățile WP4 au inclus extragerea, adnotarea și validarea datelor meteorologice relevante din bazele de date NMA și MET și pilotarea platformei în locațiile ANM și MET. Aceste activități au fost coordonate de ANM în strânsă cooperare cu MET-ML. Rezultatele privind acuratețea, performanța și fiabilitatea platformei au fost discutate cu MET-IT și UBB. Feedback-ul a fost utilizat pentru a îmbunătăți continuu modulele ML, componentele front-end și Atlasul adnotat.</small></p>
