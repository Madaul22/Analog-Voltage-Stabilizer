<h1 align="center"> Sursă de Tensiune Stabilizată și Reglabilă</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Status-Project_Completed-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Unelte-LTspice_%7C_Scopy-blue?style=for-the-badge" alt="Tools">
  <img src="https://img.shields.io/badge/Hardware-ADALM2000-orange?style=for-the-badge" alt="ADALM">
</p>

---

<h2>Descriere Proiect</h2>
<p>Acest proiect vizează proiectarea, simularea în <b>LTspice</b> și implementarea fizică a unei surse de tensiune stabilizate.Sistemul este conceput să mențină o tensiune de ieșire constantă utilizând un circuit de reglare cu reacție.
</p>
<p>
Designul teoretic complet al proiectului este structurat pe <b>4 etaje principale</b>, toate fiind validate prin simulări CAD.
</p>
<p>
Etajele proiectate sunt:
</p>
<lu>
  <li>Amplificator cu compensare DC</li>
  <li>Filtru Trece-Banda Rauch</li>
  <li>Amplificator cu Castig Programabil </li>
  <li>Redresor de precizie si Filtru de Integrare</li>
</lu>

---

 <h2>Implementare Fizică și Validare</h2>
<p>Deși proiectul cuprinde 4 etaje în faza de design, implementarea fizică pe breadboard a fost realizată cu succes pentru primele 3 etaje principale:
</p>

<p align="center">
  <img src="etaj1_breadboard.jpeg" alt="Etaj 1" width="220"/>
  <img src="etaj2_breadboard.jpeg" alt="Etaj 2" width="220"/>
  <img src="etaj3_breadboard.jpeg" alt="Etaj 3" width="220"/>
</p>
<p align="center">
  <i>Fig. 1: Etaj 1 (Amplificator cu compensare DC) | Fig. 2: Etaj 2 (Filtru Trece-Banda Rauch) | Fig. 3: Etaj 3 (Amplificator cu Castig Programabil)</i>
</p>

> **Notă:** Etajul 4 a fost validat exclusiv prin simulări software în LTspice, în timp ce etapele 1-3 au fost confirmate prin măsurători reale folosind Scopy.

---

 <h2>Tehnologii și Unelte:</h2>
 <ul>
   <li> <a href="https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html" target="_blank" rel="noreferrer">
           LTspice
        </a>
   </li>
   <li>
      <a href="https://wiki.analog.com/university/tools/m2k/scopy" target="_blank" rel="noreferrer">
           Scopy
      </a>
   </li>
   <li>
      <a href="https://www.analog.com/" target="_blank" rel="noreferrer">
           Analog Devices
      </a>
   </li>
   <li>
      <a href="https://www.analog.com/en/resources/evaluation-hardware-and-software/evaluation-boards-kits/adalm2000.html" target="_blank" rel="noreferrer">
           ADALM2000
      </a>
   </li>
 </ul>

---

<p align="center">
  <i>Realizat de Mădărășan Ioan-Alexandru</i>
</p>
