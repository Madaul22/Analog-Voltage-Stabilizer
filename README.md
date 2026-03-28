<h1 align="center">⚡ Sursă de Tensiune Stabilizată și Reglabilă</h1>
<h3 align="center">Proiect Sisteme cu Circuite Integrate Analogice (SCIA)</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Project_Completed-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Tools-LTspice_%7C_Scopy-blue?style=for-the-badge" alt="Tools">
  <img src="https://img.shields.io/badge/Hardware-ADALM2000-orange?style=for-the-badge" alt="ADALM">
</p>

---

### 📝 Descriere Proiect
[cite_start]Acest proiect vizează proiectarea, simularea în **LTspice** și implementarea fizică a unei surse de tensiune stabilizate[cite: 5]. [cite_start]Sistemul este conceput să mențină o tensiune de ieșire constantă utilizând un circuit de reglare cu reacție[cite: 5].

Designul teoretic complet al proiectului este structurat pe **4 etaje principale**, toate fiind validate prin simulări CAD.

---

### 📂 Structură Repository (Ordonată)

Organizarea fișierelor reflectă structura modulară a proiectului:

- 📁 **`measurements_data/`**: Date brute colectate cu ADALM2000.
- 📁 **`ltspice_files/`**: Profile de simulare `.asc` pentru toate cele **4 etaje** ale circuitului.
- 📄 **`Raport Proiect SCIA Madarasan.pdf`**: Documentația tehnică detaliată.

---

### 🧪 Implementare Fizică și Validare
Deși proiectul cuprinde 4 etaje în faza de design, **implementarea fizică pe breadboard a fost realizată cu succes pentru primele 3 etaje principale**:

<p align="center">
  <img src="etaj1_breadboard.jpeg" alt="Etaj 1" width="220"/>
  <img src="etaj2_breadboard.jpeg" alt="Etaj 2" width="220"/>
  <img src="etaj3_breadboard.jpeg" alt="Etaj 3" width="220"/>
</p>
<p align="center">
  <i>Fig. 1: Etaj 1 (Redresare/Filtrare) | Fig. 2: Etaj 2 (Referință) | Fig. 3: Etaj 3 (Reglaj Serie)</i>
</p>

> **Notă:** Etajul 4 a fost validat exclusiv prin simulări software în LTspice, în timp ce etapele 1-3 au fost confirmate prin măsurători reale folosind Scopy.

---

### 🛠️ Tehnologii și Unelte:
<p align="left">
  <img src="https://img.shields.io/badge/LTspice-003594?style=for-the-badge&logoColor=white" alt="LTspice" />
  <img src="https://img.shields.io/badge/Scopy-FF9900?style=for-the-badge&logoColor=white" alt="Scopy" />
  <img src="https://img.shields.io/badge/ADALM2000-Analog_Devices-green?style=for-the-badge" alt="ADALM" />
</p>

---

<p align="center">
  <i>Realizat de Mădărășan Ioan-Alexandru</i>
</p>
