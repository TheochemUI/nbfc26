---
title: "Program"
draft: false
---

<style>
.program-table {
  --program-meta: #ece7e2;         /* registration / opening */
  --program-break: #dbe8f6;        /* coffee + lunch */
  --program-poster: #f3e8b2;       /* poster session */
  --program-session: #214a86;      /* session title */
  --program-session-text: #ffffff;
  --program-line: rgba(0, 0, 0, 0.08);

  width: 100%;
  border-collapse: collapse;
  margin: 1rem 0 2rem;
  font-size: 1.7rem;
}

@media (prefers-color-scheme: dark) {
  .program-table {
    --program-meta: #3a342f;
    --program-break: #24384c;
    --program-poster: #5b5227;
    --program-session: #2a5aa0;
    --program-session-text: #f7faff;
    --program-line: rgba(255, 255, 255, 0.08);
  }
}

.program-table tr {
  background: transparent !important;
}

.program-table td {
  padding: 1.0rem 1.2rem;
  vertical-align: top;
  border: none;
  border-bottom: 1px solid var(--program-line);
  background: transparent !important;   /* default for talks */
}

.program-table td.time {
  width: 10rem;
  white-space: nowrap;
  font-weight: 600;
}

.program-table tr.meta td {
  background: var(--program-meta) !important;
}

.program-table tr.break td,
.program-table tr.lunch td {
  background: var(--program-break) !important;
  font-weight: 600;
}

.program-table tr.poster td {
  background: var(--program-poster) !important;
  font-weight: 600;
}

.program-table tr.session-title td {
  background: var(--program-session) !important;
  color: var(--program-session-text) !important;
  font-weight: 700;
  border-bottom: none;
}

.program-table tr.session-title td strong {
  color: inherit;
}

.program-table tr:last-child td {
  border-bottom: none;
}
</style>


### Monday, June 29
<table class="program-table">
  <tr class="meta">
    <td class="time">8:00–9:00</td>
    <td>Registration</td>
  </tr>
  <tr class="meta">
    <td class="time">9:00–9:10</td>
    <td>Opening Remarks</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 1 – Solvation and Reaction Dynamics</strong></td>
  </tr>
  <tr>
    <td class="time">9:10–9:40</td>
    <td>Michael Odelius (Stockholm University)</td>
  </tr>
  <tr>
    <td class="time">9:40–10:00</td>
    <td>Elisa Biasin (Pacific Northwest National Laboratory)</td>
  </tr>
  <tr>
    <td class="time">10:00–10:20</td>
    <td>Ali Hassanali (International Center for Theoretical Physics, Trieste)</td>
  </tr>
  <tr>
    <td class="time">10:20–10:40</td>
    <td>Adam Sapnik (Technical University of Denmark)</td>
  </tr>
  <tr class="break">
    <td class="time">10:40–11:10</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td class="time">11:10–11:40</td>
    <td>Luis Bañares (Universidad Complutense de Madrid)</td>
  </tr>
  <tr>
    <td class="time">11:40–12:00</td>
    <td>Marcos Dantus (Michigan State University)</td>
  </tr>
  <tr>
    <td class="time">12:00–12:20</td>
    <td>Markus Meuwly (University of Basel)</td>
  </tr>
  <tr class="lunch">
    <td class="time">12:20–13:30</td>
    <td>Lunch</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 2 – Nonlinear Spectroscopy and Polariton Dynamics</strong></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>Markus Kowalewski (Stockholm University)</td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>Jussi Toppari (University of Jyväskylä)</td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>Ágnes Vibók (University of Debrecen)</td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>Franco Camargo (Institute for Photonics and Nanotechnologies, Milan)</td>
  </tr>
  <tr class="break">
    <td class="time">15:10–15:40</td>
    <td>Coffee Break</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 3 – Frontiers in Ultrafast Science at Large Scale Facilities</strong></td>
  </tr>
  <tr>
    <td class="time">15:40–16:10</td>
    <td>Sakura Pascarelli (European XFEL)</td>
  </tr>
  <tr>
    <td class="time">16:10–16:30</td>
    <td>Morten Haubro (Technical University of Denmark)</td>
  </tr>
  <tr>
    <td class="time">16:30–16:50</td>
    <td>Tiffany Walmsley (Central Laser Facility, UK)</td>
  </tr>
  <tr>
    <td class="time">16:50–17:00</td>
    <td>Light Conversion</td>
  </tr>
  <tr class="poster">
    <td class="time">17:00-18:30</td>
    <td>Poster Session 1</td>
  </tr>
</table>
<br>
       
### Tuesday, June 30
<table class="program-table">
  <tr class="session-title">
    <td colspan="2"><strong>Session 4 – Ultrafast X-ray Science</strong></td>
  </tr>
  <tr>
    <td class="time">9:00–9:30</td>
    <td>Adam Kirrander (University of Oxford)</td>
  </tr>
  <tr>
    <td class="time">9:30–10:00</td>
    <td>Simon Wall (Aarhus University)</td>
  </tr>
  <tr>
    <td class="time">10:00–10:20</td>
    <td>Kerstin Mitterer (Technical University of Denmark)</td>
  </tr>
  <tr>
    <td class="time">10:20–10:40</td>
    <td>Madhusree Roy Chowdhury (University of Kassel)</td>
  </tr>
  <tr class="break">
    <td class="time">10:40–11:10</td>
    <td>Coffee Break</td>
  </tr>
  <tr class="session-title">
    <td colspan="2"><strong>Session 5 – Electronic and Attosecond Dynamics</strong></td>
  </tr>
  <tr>
    <td class="time">11:10–11:40</td>
    <td>Francesca Calegari (DESY &amp; University of Hamburg)</td>
  </tr>
  <tr>
    <td class="time">11:40–12:00</td>
    <td>Thomas Schnappinger (Stockholm University)</td>
  </tr>
  <tr>
    <td class="time">12:00–12:20</td>
    <td>Marco Marchetta (University of Trieste)</td>
  </tr>
  <tr class="lunch">
    <td class="time">12:20–13:30</td>
    <td>Lunch and group photo</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 6 – Theoretical and Computational Modelling for Ultrafast Dynamics 1</strong></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>Emmanuel Fromager (Strasbourg University)</td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>Henrik Koch (Norwegian University of Science and Technology)</td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>Oliver Kühn (University of Rostock)</td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>Darius Abramavičius (Vilnius University)</td>
  </tr>
  <tr>
    <td class="time">15:10–15:30</td>
    <td>Giulia Dall'Osto (Elettra Sincrotrone Trieste)</td>
  </tr>

  <tr class="poster">
    <td class="time">15:30–17:00</td>
    <td>Poster Session 2</td>
  </tr>

  <tr class="lunch">
    <td class="time">18:00</td>
    <td>Reception and conference dinner in Harpa</td>
  </tr>
</table>
<br>

### Wednesday, July 1
<table class="program-table">
  <tr class="session-title">
    <td colspan="2"><strong>Session 7 – Ultrafast Dynamics in Biosystems</strong></td>
  </tr>
  <tr>
    <td class="time">9:00–9:30</td>
    <td>Juergen Hauer (Technical University of Munich)</td>
  </tr>
  <tr>
    <td class="time">9:30–9:50</td>
    <td>Janne Ihalainen (University of Jyväskylä)</td>
  </tr>
  <tr>
    <td class="time">9:50–10:10</td>
    <td>Kloz Miroslav (The Extreme Light Infrastructure ERIC, Czech Republic)</td>
  </tr>
  <tr>
    <td class="time">10:10–10:30</td>
    <td>Lukas Grunewald (Uppsala University)</td>
  </tr>
  <tr class="break">
    <td class="time">10:30–11:00</td>
    <td>Coffee Break</td>
  </tr>
  <tr class="session-title">
    <td colspan="2"><strong>Session 8 – Ultrafast Dynamics in Solids and Catalysis</strong></td>
  </tr>
  <tr>
    <td class="time">11:00–11:30</td>
    <td>Martin Beye (Stockholm University)</td>
  </tr>
  <tr>
    <td class="time">11:30–11:50</td>
    <td>Tero-Petri Ruoko (Tampere University)</td>
  </tr>
  <tr>
    <td class="time">11:50–12:10</td>
    <td>Yanmei He (Lund University)</td>
  </tr>
  <tr>
    <td class="time">12:10–12:30</td>
    <td>Marius Navickas (Laser Research Center, Vilnius University)</td>
  </tr>
  <tr class="lunch">
    <td class="time">12:30–13:30</td>
    <td>Lunch</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 9 – Theoretical and Computational Modelling for Ultrafast Dynamics 2</strong></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>Nanna Holmgaard List (KTH &amp; University of Birmingham)</td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>Basile Curchod (University of Bristol)</td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>Francesco Segatta (University of Bologna)</td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>Mathilde Goullieux (DESY)</td>
  </tr>
  <tr>
    <td class="time">15:10–15:30</td>
    <td>Léon Cicrang (University College London)</td>
  </tr>

  <tr class="meta">
    <td class="time">15:30–15:40</td>
    <td>Closing remarks</td>
  </tr>
</table>
