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
  --program-affiliation: rgba(0, 0, 0, 0.55);

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
    --program-affiliation: rgba(255, 255, 255, 0.62);
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

.program-table .session-chair {
  margin-top: 0.35rem;
  font-size: 1.7rem;
  font-weight: 400;
  color: var(--program-session-text);
}

.program-table tr:last-child td {
  border-bottom: none;
}

.program-table .talk-speaker {
  font-weight: 700;
}

.program-table .talk-affiliation {
  margin-left: 0.7rem;
  font-size: 1.45rem;
  color: var(--program-affiliation);
  font-weight: 400;
}

.program-table .talk-title {
  margin-top: 0.25rem;
  font-size: 1.7rem;
  line-height: 1.35;
  font-weight: 400;
}

.program-table .talk-title a {
  font-weight: 500;
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
    <td colspan="2"><strong>Session 1 – Solvation and Reaction Dynamics</strong><div class="session-chair">Chair: Hannes Jónsson</div></td>
  </tr>
  <tr>
    <td class="time">9:10–9:40</td>
    <td>
      <div><span class="talk-speaker">Michael Odelius</span><span class="talk-affiliation">Stockholm University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=129ZxsFRTquLqVRU0VT9HUnYjA0CA9Ph_&amp;usp=drive_fs">Theoretical Studies of Reaction Pathways in Homogeneous Photocatalysis</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">9:40–10:00</td>
    <td>
      <div><span class="talk-speaker">Elisa Biasin</span><span class="talk-affiliation">Pacific Northwest National Laboratory</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1lmQtF1NQYpziTGktO97GC2-fKVjzf_Mf&amp;usp=drive_fs">Ultrafast X-ray Studies of Solute–Solvent Hydrogen-Bond Dynamics</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">10:00–10:20</td>
    <td>
      <div><span class="talk-speaker">Ali Hassanali</span><span class="talk-affiliation">International Center for Theoretical Physics, Trieste</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1juzGH_I4ORtnIYZNTI3qTIjykfpmppZO&amp;usp=drive_fs">From Hydrogen-Bond Defects to Hydrated Electrons: Ultrafast Pathways in Liquid Water</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">10:20–10:40</td>
    <td>
      <div><span class="talk-speaker">Adam Sapnik</span><span class="talk-affiliation">Technical University of Denmark</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1FjfBJxyidtHopKVxWLCu3Stox8fta-i2&amp;usp=drive_fs">Structural Dynamics of Photo-Aquation in [Fe(CN)<sub>6</sub>]<sup>4−</sup></a></div>
    </td>
  </tr>
  <tr class="break">
    <td class="time">10:40–11:10</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td class="time">11:10–11:40</td>
    <td>
      <div><span class="talk-speaker">Luis Bañares</span><span class="talk-affiliation">Universidad Complutense de Madrid</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1_x9T7FHteFhMsfkfkwAQWvfcElb-xKHm&amp;usp=drive_fs">Conformational Chemistry by Resonant Coulomb Explosion Imaging</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">11:40–12:00</td>
    <td>
      <div><span class="talk-speaker">Marcos Dantus</span><span class="talk-affiliation">Michigan State University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=12IQFKLBV74xftgbEHpLEBp0MlXMK0a4l&amp;usp=drive_fs">Ultrafast Cation–Dication Dynamics in Ammonia Borane: H-Migration to Roaming H<sub>2</sub> and Reduced H<sub>3</sub><sup>+</sup> Formation Under Strong-Field Ionization</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">12:00–12:20</td>
    <td>
      <div><span class="talk-speaker">Markus Meuwly</span><span class="talk-affiliation">University of Basel</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1S0K6AymrPHs1e3LIchpvREMUWVxCIaXR&amp;usp=drive_fs">Elementary Reactions in the Hypersonic Regime: Picosecond Dynamics of Highly Excited Species</a></div>
    </td>
  </tr>
  <tr class="lunch">
    <td class="time">12:20–13:30</td>
    <td>Lunch</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 2 – Polariton Dynamics and Nonlinear Spectroscopy</strong><div class="session-chair">Chair: Siim Pikker</div></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>
      <div><span class="talk-speaker">Markus Kowalewski</span><span class="talk-affiliation">Stockholm University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1CYlh3xxI3K37dwR3g3Ks9vTIzwdbXyPM&amp;usp=drive_fs">Photochemistry in Optical Cavities: Strong Light–Matter Coupling and Collective Effects</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>
      <div><span class="talk-speaker">Jussi Toppari</span><span class="talk-affiliation">University of Jyväskylä</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1IADJhPLAn9ZaeA1gkOCvFyk1hYX8AGWE&amp;usp=drive_fs">Polaritonic Chemistry – Polaritons or Optical Illusions</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>
      <div><span class="talk-speaker">Ágnes Vibók</span><span class="talk-affiliation">University of Debrecen</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1Z4pqj6OTJ5BT-MYbPcwql_RkzN9JypYq&amp;usp=drive_fs">Dissipative Molecular Cavity Quantum Dynamics</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>
      <div><span class="talk-speaker">Franco Camargo</span><span class="talk-affiliation">Institute for Photonics and Nanotechnologies, Milan</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1wQrAJ0mgzF1dbSllqqIbMklzIHLxte50&amp;usp=drive_fs">Connecting Many-Body Kinetics and Higher-Order Nonlinear Signals in Ultrafast Spectroscopy</a></div>
    </td>
  </tr>
  <tr class="break">
    <td class="time">15:10–15:40</td>
    <td>Coffee Break</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 3 – Frontiers in Ultrafast Science at Large Scale Facilities</strong><div class="session-chair">Chair: Janne Ihalainen</div></td>
  </tr>
  <tr>
    <td class="time">15:40–16:10</td>
    <td>
      <div><span class="talk-speaker">Sakura Pascarelli</span><span class="talk-affiliation">European XFEL</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1C8-CGdmu41i8f9n7N81H0kkcUoz4amvP&amp;usp=drive_fs">New Scientific Opportunities at the European X-ray Free Electron Laser</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">16:10–16:30</td>
    <td>
      <div><span class="talk-speaker">Morten Haubro</span><span class="talk-affiliation">Technical University of Denmark</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1ei7mPxhYlp80G7OVy2S48QPhhwsr3B6s&amp;usp=drive_fs">Ultrafast THz-Induced Lattice Dynamics in Prototypical Solid State Electrolyte LLZO</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">16:30–16:50</td>
    <td>
      <div><span class="talk-speaker">Tiffany Walmsley</span><span class="talk-affiliation">Central Laser Facility, UK</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=150Ikzt1eophzwkKMm-1lEgKPMY32TB-x&amp;usp=drive_fs">Resolving the Inner-Shell Ionization and Fragmentation of Selenophene Using 3D Momentum Covariance Analysis</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">16:50–17:00</td>
    <td>Light Conversion</td>
  </tr>
  <tr class="poster">
    <td class="time">17:00–18:30</td>
    <td>Poster Session 1</td>
  </tr>
</table>
<br>

### Tuesday, June 30
<table class="program-table">
  <tr class="session-title">
    <td colspan="2"><strong>Session 4 – Ultrafast X-ray Science</strong><div class="session-chair">Chair: Klaus B. Møller</div></td>
  </tr>
  <tr>
    <td class="time">9:00–9:30</td>
    <td>
      <div><span class="talk-speaker">Adam Kirrander</span><span class="talk-affiliation">University of Oxford</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1SC10fQ1jTkjIHJMXlBTwuE5xdR-JKHT4&amp;usp=drive_fs">Mapping Electrons and Electron Dynamics by X-Ray Scattering</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">9:30–10:00</td>
    <td>
      <div><span class="talk-speaker">Simon Wall</span><span class="talk-affiliation">Aarhus University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1YzMZb-GBFZ_LLbYbTmZfQlDjs5uqEZmT&amp;usp=drive_fs">Coherence and Disorder in Photon and Phonon Induced Phase Transitions</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">10:00–10:20</td>
    <td>
      <div><span class="talk-speaker">Kerstin Mitterer</span><span class="talk-affiliation">Technical University of Denmark</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1XdP9Cmc5RHNdbxM4r57JLReZ5LiLtIi5&amp;usp=drive_fs">Ultrafast Structural Dynamics in and around a Photoexcited Organic Chromophore in Aqueous Solution Visualized with Time-Resolved X-Ray Scattering</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">10:20–10:40</td>
    <td>
      <div><span class="talk-speaker">Madhusree Roy Chowdhury</span><span class="talk-affiliation">University of Kassel</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1V1RCYj6-Ka4HmKrZoBCJS4lz4EsJ8Up9&amp;usp=drive_fs">Core-Level Electron Transfer Mediated Decay in Hydrated Pyrimidine</a></div>
    </td>
  </tr>
  <tr class="break">
    <td class="time">10:40–11:10</td>
    <td>Coffee Break</td>
  </tr>
  <tr class="session-title">
    <td colspan="2"><strong>Session 5 – Electronic and Attosecond Dynamics</strong><div class="session-chair">Chair: Basile Curchod</div></td>
  </tr>
  <tr>
    <td class="time">11:10–11:40</td>
    <td>
      <div><span class="talk-speaker">Francesca Calegari</span><span class="talk-affiliation">DESY &amp; University of Hamburg</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1rNKGX7CPj9AHwehAziO6NP9I3iGV2_fp&amp;usp=drive_fs">Attosecond Charge Migration and Chiral Control</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">11:40–12:00</td>
    <td>
      <div><span class="talk-speaker">Thomas Schnappinger</span><span class="talk-affiliation">Stockholm University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1JKMDtGHgaY3bC7TuKIq8ESCenZdNv71p&amp;usp=drive_fs">Attosecond Spectroscopy Uncovers a 1.5-fs Delay in Population Transfer</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">12:00–12:20</td>
    <td>
      <div><span class="talk-speaker">Marco Marchetta</span><span class="talk-affiliation">University of Trieste</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1OsU-RbVtILexeQ0i-LsxbgPPG3PlCLfH&amp;usp=drive_fs">Dynamical Symmetries and Selection Rules in High-Harmonic Generation Spectroscopy of Nonlinear Molecules</a></div>
    </td>
  </tr>
  <tr class="lunch">
    <td class="time">12:20–13:30</td>
    <td>Lunch and group photo</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 6 – Theoretical and Computational Modelling for Ultrafast Dynamics 1</strong><div class="session-chair">Chair: Elvar Ö. Jónsson</div></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>
      <div><span class="talk-speaker">Emmanuel Fromager</span><span class="talk-affiliation">Strasbourg University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1iqBMcmxu33AUO-WepbJo6G1niX-h5BiJ&amp;usp=drive_fs">Density Functional Theory Beyond the Born–Oppenheimer Approximation: Molecular Kohn–Sham Formalism with or without Exact Factorization</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>
      <div><span class="talk-speaker">Henrik Koch</span><span class="talk-affiliation">Norwegian University of Science and Technology</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1E_N_bt0LGfrp4KDXrVG7ODvPw-yjA9lu&amp;usp=drive_fs">Nonadiabatic Dynamics Using Coupled Cluster Theory</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>
      <div><span class="talk-speaker">Oliver Kühn</span><span class="talk-affiliation">University of Rostock</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1dLbzlkTIxcxPI25zQFozyYqywRPj_zhA&amp;usp=drive_fs">BSE@GW-Based Spin-Vibronic Quantum Dynamics of Transition Metal Complexes Using the Linear Vibronic Coupling Model</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>
      <div><span class="talk-speaker">Darius Abramavičius</span><span class="talk-affiliation">Vilnius University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1HmlJDCFNr7v9VnkGsaH5_gyAdrcLtteD&amp;usp=drive_fs">Simulation of Excitation Dynamics in Molecular Complexes: From Excitons to Polarons</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">15:10–15:30</td>
    <td>
      <div><span class="talk-speaker">Giulia Dall'Osto</span><span class="talk-affiliation">Elettra Sincrotrone Trieste</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1Zj7astLmN4JKg6gYbTKZUdaONZ__9S4H&amp;usp=drive_fs">Time-Dependent Open-Quantum Approach to Two-Dimensional Electronic Spectroscopy within a GW/BSE Active Space</a></div>
    </td>
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
    <td colspan="2"><strong>Session 7 – Ultrafast Dynamics in Biosystems</strong><div class="session-chair">Chair: Darius Abramavičius</div></td>
  </tr>
  <tr>
    <td class="time">9:00–9:30</td>
    <td>
      <div><span class="talk-speaker">Juergen Hauer</span><span class="talk-affiliation">Technical University of Munich</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1mwPf9X709jyo7xQMEVwLixxksybypzOV&amp;usp=drive_fs">Two-Dimensional Fluorescence Excitation Spectroscopy (2D-FLEX): Experimental Approaches and First Insights</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">9:30–9:50</td>
    <td>
      <div><span class="talk-speaker">Janne Ihalainen</span><span class="talk-affiliation">University of Jyväskylä</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1nqIpDAhks7FwZD8hMu1Ek2XoMb44_Rif&amp;usp=drive_fs">Chromophore Isomerization and Ultrafast Protein Response after Photoexcitation in a Bacteriophytochrome – A Time-Resolved Fluorescence and IR Study</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">9:50–10:10</td>
    <td>
      <div><span class="talk-speaker">Miroslav Kloz</span><span class="talk-affiliation">The Extreme Light Infrastructure ERIC, Czech Republic</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1EfXlfD2t1X4SIvHJINJGT4fuoQUQP0Jm&amp;usp=drive_fs">Excited-State Manifold of Retinal and Its Derivatives Analyzed by Femtosecond Stimulated Raman Spectroscopy</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">10:10–10:30</td>
    <td>
      <div><span class="talk-speaker">Lukas Grunewald</span><span class="talk-affiliation">Uppsala University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1uVEvAzIxDh5BXy3bMjOha002oJTJtd8I&amp;usp=drive_fs">Shining Light on Phytochromes: Ultrafast Photosignalling Captured by Time-Resolved Serial Crystallography</a></div>
    </td>
  </tr>
  <tr class="break">
    <td class="time">10:30–11:00</td>
    <td>Coffee Break</td>
  </tr>
  <tr class="session-title">
    <td colspan="2"><strong>Session 8 – Ultrafast Dynamics in Solids and Catalysis</strong><div class="session-chair">Chair: Kristoffer Haldrup</div></td>
  </tr>
  <tr>
    <td class="time">11:00–11:30</td>
    <td>
      <div><span class="talk-speaker">Martin Beye</span><span class="talk-affiliation">Stockholm University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=155Xmqsoq4_4x_2r5ZmjPxCi1quBz6ZjA&amp;usp=drive_fs">Towards Femtochemistry X-Ray Studies of Catalysis on Surfaces under Operando Conditions</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">11:30–11:50</td>
    <td>
      <div><span class="talk-speaker">Tero-Petri Ruoko</span><span class="talk-affiliation">Tampere University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1Qqn-mNql0OzwdLCc95idF9DOnY7xlMXr&amp;usp=drive_fs">Photochemical n-Doping of Organic Semiconductors</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">11:50–12:10</td>
    <td>
      <div><span class="talk-speaker">Yanmei He</span><span class="talk-affiliation">Lund University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1UeDWxCVPQwFpqIs6R13UCRSl4vGfvd_a&amp;usp=drive_fs">Dimensionality-Dependent Electronic and Vibrational Dynamics in Low-Dimensional Organic–Inorganic Tin Halides</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">12:10–12:30</td>
    <td>
      <div><span class="talk-speaker">Marius Navickas</span><span class="talk-affiliation">Laser Research Center, Vilnius University</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1q8KutcA2B-DUO6RImdPNBlN4Nj5TmnQM&amp;usp=drive_fs">Time-Resolved Visualisation of Photopolymerisation Dynamics in SZ2080™</a></div>
    </td>
  </tr>
  <tr class="lunch">
    <td class="time">12:30–13:30</td>
    <td>Lunch</td>
  </tr>

  <tr class="session-title">
    <td colspan="2"><strong>Session 9 – Theoretical and Computational Modelling for Ultrafast Dynamics 2</strong><div class="session-chair">Chair: Gianluca Levi</div></td>
  </tr>
  <tr>
    <td class="time">13:30–14:00</td>
    <td>
      <div><span class="talk-speaker">Nanna Holmgaard List</span><span class="talk-affiliation">KTH &amp; University of Birmingham</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1xo4hIpukU1sKaPE2Vtj8ZAYE3ZCDwciV&amp;usp=drive_fs">From Photochemical Mechanism toward Control: Seam Access, Seam Reactivity and Environmental Gating</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:00–14:30</td>
    <td>
      <div><span class="talk-speaker">Basile Curchod</span><span class="talk-affiliation">University of Bristol</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=15dAmvaIMq3QzMJlPKdndvuZWzLCpdFpN&amp;usp=drive_fs">On the Description of Photoexcitation in Nonadiabatic Molecular Dynamics</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:30–14:50</td>
    <td>
      <div><span class="talk-speaker">Francesco Segatta</span><span class="talk-affiliation">University of Bologna</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1EXVxZAsb2yAmI9grzQkbfj6nW_MfLCrm&amp;usp=drive_fs">Unveiling the Ultrafast Relaxation of Solvated Thymidine with XUV-TRPES Experiments and Simulations</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">14:50–15:10</td>
    <td>
      <div><span class="talk-speaker">Mathilde Goullieux</span><span class="talk-affiliation">DESY</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1cI7BWQCZagoeuFzD4WDMo9MdbCoW0QNc&amp;usp=drive_fs">Ultrafast Radiation Chemistry of Glycine in Aqueous Solution</a></div>
    </td>
  </tr>
  <tr>
    <td class="time">15:10–15:30</td>
    <td>
      <div><span class="talk-speaker">Léon Cigrang</span><span class="talk-affiliation">University College London</span></div>
      <div class="talk-title"><a href="https://drive.google.com/open?id=1jfH9-26WsRfDLB7dq7t6k64jueknXFY2&amp;usp=drive_fs">Quantum Dynamics in Explicit Environments</a></div>
    </td>
  </tr>

  <tr class="meta">
    <td class="time">15:30–15:40</td>
    <td>Closing Remarks</td>
  </tr>
</table>