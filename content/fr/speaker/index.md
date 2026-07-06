---
title: ""
type: page
reading_time: false

---
{{< raw >}}
<style>


.flex.flex-row.flex-wrap.justify-center.pt-4.text-xl {
  display: none !important;
}

a.group.flex.no-underline {
  display: none !important;
}

.speaker-page {
    font-family: inherit;
    max-width: 100%;
    margin: 0 auto;
    padding: 1rem 0;
    color: #2a1f14;
  }

  .speaker-header {
    margin-bottom: 2rem;
    border-bottom: 2px solid #433a1f;
    padding-bottom: 1rem;
  }
s
  .speaker-header .eyebrow {
    font-size: 0.7rem;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: #2d6e3e;
    font-family: inherit;
    font-weight: 700;
    margin-bottom: 0.3rem;
  }

  .speaker-title {
    font-size: 2rem;
    font-weight: 800;
    color: #433a1f;
    /*color: #1a3d28;*/
    margin: 0.2rem 0 0.4rem 0;
    line-height: 1.2;
  }

  .speaker-header .tagline {
    font-size: 1rem;
    color: #555;
    font-style: italic;
    margin: 0;
  }

  .main-layout {
    display: block;
  }

  .section-label {
    font-size: 1.4rem;
    letter-spacing: 0.1em;
    /*text-transform: uppercase;*/
    /*color: #2d6e3e;*/
    /*color: #1a3d28;*/
    font-family: inherit;
    font-weight: 800;
    margin-bottom: 0.5rem;
    padding-bottom: 0.3rem;
    /*border-bottom: 1px solid #d4b896;*/
    text-align: center;
  }

  .profile-text {
    font-size: 0.95rem;
    line-height: 1.75;
    color: #333;
    margin-bottom: 1.2rem;
  }

  .quote-block {
    border-left: 3px solid #2d6e3e;
    background: #f5f0e8;
    padding: 1rem 1.2rem;
    margin: 1.5rem 0;
    font-style: italic;
    font-size: 0.9rem;
    color: #2d6e3e;
    line-height: 1.6;
  }

  .talk {
    border-left: 4px solid #2d6e3e;
    padding: 0.8rem 1rem;
    margin-bottom: 1.2rem;
    background: #faf8f4;
  }

  .talk h3 {
    font-size: 0.95rem;
    font-weight: 700;
    color: #1a3d28;
    margin: 0 0 0.4rem 0;
  }

  .talk p {
    font-size: 0.85rem;
    color: #555;
    line-height: 1.6;
    margin: 0;
  }

  .cross-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin-top: 0.8rem;
  }

  .cross-item {
    background: #f5f0e8;
    padding: 0.8rem;
    border-top: 2px solid #2d6e3e;
  }

  .cross-item h4 {
    font-size: 0.8rem;
    font-weight: 700;
    font-style: italic;
    color: #2d6e3e;
    margin: 0 0 0.3rem 0;
  }

  .cross-item p {
    font-size: 0.78rem;
    color: #666;
    margin: 0;
    line-height: 1.5;
  }

  .formats-grid {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    margin-top: 0.8rem;
  }

  .format-item {
    text-align: center;
    flex: 1;
    min-width: 80px;
    border: 1px solid #d4b896;
    padding: 0.8rem 0.5rem;
    background: white;
  }

  .format-icon {
    font-size: 1.4rem;
    display: block;
    margin-bottom: 0.3rem;
  }

  .format-name {
    font-size: 0.75rem;
    font-weight: 700;
    color: #1a3d28;
    display: block;
  }

  .format-duration {
    font-size: 0.7rem;
    color: #888;
    display: block;
  }

  .sidebar {
    margin-top: 2rem;
    border-top: 1px solid #d4b896;
    padding-top: 1.5rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;

  }

  .sidebar-section {
    margin-bottom: 1.2rem;
  }

.sidebar .section-label {
  text-align: left;
} 
  .sidebar-section ul {
    list-style: none;
    padding: 0;
    margin: 0.5rem 0 0 0;
  }

  .sidebar-section ul li {
    font-size: 0.82rem;
    color: #444;
    padding: 0.15rem 0;
    padding-left: 1rem;
    position: relative;
    line-height: 1.5;
  }

  .sidebar-section ul li::before {
    content: '▸';
    color: #2d6e3e;
    position: absolute;
    left: 0;
    font-size: 0.7rem;
  }

  .contact-item {
    font-size: 0.82rem;
    color: #444;
    margin-bottom: 0.4rem;
    white-space: nowrap;
  }

.download-btn {
  
    display: block;
    width: fit-content;
    margin: 1rem auto 0;
    align-items: center;
    gap: 0.5rem;
    background: linear-gradient(to right, #1a3d28, #1a3d28);
    color: white;
    padding: 1rem 2rem;
    font-size: 1.1rem;
    font-weight: 700;
    text-decoration: none;
    margin-top: 1rem;
    font-family: inherit;
    border-radius: 0.75rem;
    box-shadow: 0 4px 12px rgba(139, 99, 64, 0.3);
    transition: all 0.3s;
  }

  .download-btn:hover {
    background: linear-gradient(to right, #2d6e3e, #2d6e3e);
    box-shadow: 0 6px 16px rgba(139, 99, 64, 0.4);
    transform: scale(1.05);
    color: white;
  }


  .footer-quote {
    background: #1a3d28;
    color: #cce0d4;
    text-align: center;
    padding: 1.2rem;
    margin-top: 3rem;
    font-style: italic;
    font-size: 0.9rem;
  }

  @media (max-width: 700px) {
    .cross-grid { grid-template-columns: 1fr; }
    .sidebar { grid-template-columns: 1fr; }
  }

  .dark .speaker-header { border-bottom-color: #3d5a3d; }
  .dark .speaker-page { color: #e8d5c0; }
  .dark .speaker-title { color: #c0d4c0; }
  .dark .profile-text { color: #ccc; }
  .dark .talk { background: #1a2a1a; }
  .dark .talk h3 { color: #a0c8a0; }
  .dark .talk p { color: #aaa; }
  .dark .quote-block { background: #1a1a0a; color: #a0c8a0; }
  .dark .cross-item { background: #1a2a1a; }
  .dark .cross-item h4 { color: #a0c8a0; }
  .dark .cross-item p { color: #aaa; }
  .dark .format-item { background: #1a2a1a; border-color: #3d5a3d; }
  .dark .format-name { color: #a0c8a0; }
  .dark .contact-item { color: #ccc; }
  .dark .sidebar-section ul li { color: #ccc; }

    .speaker-banner {
    width: 100%;
    height: 250px;
    object-fit: cover;
    object-position: center;
    display: block;
    margin-bottom: 2rem;
  }

/* .page-body:has(.speaker-page) {
  background: linear-gradient(135deg, #fdf8f3 0%, #f0e6d3 100%);
  margin-top: 0 !important;
  padding-top: 0 !important;
} */

.dark .page-body:has(.speaker-page) {
  background: none;
}

.prose p { text-align: justify; }

</style>
  <div class="speaker-header">
<div style="font-size: clamp(1rem, 3vw, 2rem); font-weight: 700; color: var(--tw-prose-headings, #111827); text-align: center; font-family: inherit; margin-bottom: 0.5rem; line-height: 1.1; letter-spacing: -0.02em;">Profil conférencier</div>
 
 <img src="/bandeau.jpg" alt="" class="speaker-banner">
  <h1 class="speaker-title">Transition Environnementale & Biodiversité</h1>
  <!--<p class="tagline">Conférences & interventions — France entière, présentiel & distanciel</p>-->
</div>

  <div class="main-layout">

    <div class="left-col">

      <!-- <div class="section-label">Profil</div> -->
      <p class="profile-text">
        Chercheur spécialisé en biologie appliquée à la conservation, ancien élève de l'École Normale Supérieure de Lyon, je propose des conférences et des interventions sur des thèmes variés, préparées ou adaptées aux besoins de l'institution d'accueil. Mes travaux de thèse, conduits au Muséum National d'Histoire Naturelle, ont porté sur l'approche évocentrée de la conservation et ont conduit au développement du cadre de l'Empreinte évolutive, outil standardisé pour quantifier l'impact évolutif des activités humaines sur la biodiversité.
      </p>
      <p class="profile-text">
        À travers un parcours pluridisciplinaire nourri par un triple master en biologie, agronomie et philosophie des sciences, mon positionnement est singulier. Je propose une vision intégrative des enjeux contemporains en associant sciences du vivant, philosophie de l'environnement et sciences politiques, économiques et sociales.
      </p>

      <div class="quote-block">
        « L'évocentrisme tient en quelques mots : laisser libre, laisser des marges. La conservation de la nature est sisyphéenne. Mais nous continuons de proposer d'autres possibles. Et tout bien pesé, il ne faut pas se battre pour conserver. Non, ce que nous souhaitons avant tout, c'est permettre. »
      </div>


      <div class="section-label" style="margin-top:2rem;">Conférences</div>
      <div style="margin-top: 1rem;text-align: center;">
        <a href="/fr/book/" style="display: inline-flex; align-items: center; gap: 0.5rem; background: linear-gradient(to right, #2d6e3e, #1a4d28); color: white; padding: 0.8rem 1.6rem; font-size: 0.9rem; font-weight: 700; text-decoration: none; border-radius: 0.75rem; box-shadow: 0 4px 12px rgba(45,110,62,0.3); transition: all 0.3s;"> Voir les conférences proposées</a>
      </div>
<!--
      <div class="section-label" style="margin-top:2rem;">Conférences proposées</div>

      <div class="talk">
        <h3>De la wilderness aux marchés carbone : histoire des idées et enjeux de la conservation</h3>
        <p>Des impacts de l'activité humaine sur le vivant aux réponses scientifiques et politiques : une introduction complète aux enjeux historiques et contemporains de la conservation de la biodiversité, accessible à tous les publics.</p>
      </div>

      <div class="talk">
        <h3>Biodiversité en crise : quelle est la réalité des changements passés et à venir ?</h3>
        <p>Comprendre les enjeux contemporains liés à la biodiversité nécessite une vision large : des grands cycles biogéochimiques de la planète jusqu'à l'évolution des populations sauvages, cette conférence propose un panorama des empreintes humaines sur le vivant.</p>
      </div>

      <div class="talk">
        <h3>Évocentrisme : la conservation de la biodiversité au prisme de l'évolution</h3>
        <p>Les activités humaines impactent l'évolution du vivant à toutes les échelles biologiques. L'évocentrisme est une approche éthique et scientifique qui vise à identifier et réduire ces impacts, pour répondre à la crise de la biodiversité.</p>
      </div>

      <div class="talk">
        <h3>GIEC, IPBES, COP... : comprendre les institutions et les indicateurs de la transition environnementale</h3>
        <p>Des organisations contribuent à la documentation et à la planification de la lutte contre les changements globaux. À travers une revue des institutions incontournables, cette conférence donne le nécessaire à la compréhension des rapports qu'elles produisent.</p>
      </div>
-->
      <div class="section-label" style="margin-top:2rem;">Regards croisés : thèmes hors-cadres</div>
      <div class="cross-grid">
        <div class="cross-item">
          <h4>Perspectives humain-animal</h4>
          <p>Explorer les voies de coexistence entre le monde sauvage et les sociétés humaines</p>
        </div>
        <div class="cross-item">
          <h4>Devenirs alpins : penser la montagne</h4>
          <p>Les Alpes comme modèle de la transformation des usages et des écosystèmes</p>
        </div>
        <div class="cross-item">
          <h4>Écrire les vivants</h4>
          <p>Repenser les récits en ouvrant les enjeux contemporains à la littérature</p>
        </div>
      </div>

      <div class="section-label" style="margin-top:2rem;">Formats d'intervention</div>
      <div class="formats-grid">
        <div class="format-item">
          <span class="format-icon">🎤</span>
          <span class="format-name">Conférence</span>
          <span class="format-duration">45–60 min</span>
        </div>
        <div class="format-item">
          <span class="format-icon">💬</span>
          <span class="format-name">Table ronde</span>
          <span class="format-duration">30–90 min</span>
        </div>
        <div class="format-item">
          <span class="format-icon">✏️</span>
          <span class="format-name">Atelier</span>
          <span class="format-duration">2–3 heures</span>
        </div>
        <div class="format-item">
          <span class="format-icon">🍽</span>
          <span class="format-name">Déj. débat</span>
          <span class="format-duration">1 heure</span>
        </div>
        <div class="format-item">
          <span class="format-icon">💻</span>
          <span class="format-name">Visioconférence</span>
          <span class="format-duration">Flexible</span>
        </div>
      </div>

    </div>

    <div class="sidebar">

      <div class="sidebar-section">
        <div class="section-label">Domaines</div>
        <ul>
          <li>Sciences de la Conservation</li>
          <li>Écologie / Évolution</li>
          <li>Éthique</li>
          <li>COP Biodiversité</li>
          <li>Indicateurs Biodiversité</li>
          <li>Réintroduction, Rewilding</li>
          <li>Comportement animal</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Profil académique</div>
        <ul>
          <li>École Normale Sup. de Lyon</li>
          <li>PhD, félicitations du jury</li>
          <li>M2 Philosophie, Paris IV</li>
          <li>M2 CLUES, AgroParisTech</li>
          <li>M2 Complex Systems, ENSL</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Engagements</div>
        <ul>
          <li>COP 15 Kunming-Montréal</li>
          <li>Comité IUCN Education</li>
          <li>ECCB 2024</li>
          <li>Parc National de Port-Cros</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Enseignements</div>
        <ul>
          <li>Chargé d'enseignement SU</li>
          <li>Licence – Master biologie</li>
          <li>Cours particuliers</li>
          <li>Concours médecine – prépas</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Disponibilité</div>
        <ul>
          <li>France entière</li>
          <li>Présentiel & distanciel</li>
          <li>Conférences sur mesure</li>
          <li>Facturation auto-entrepreneur</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Contact</div>
        <div class="contact-item">thibault.genissel@ikmail.fr</div>
        <div class="contact-item">+33 6 24 35 02 04</div>
        <div class="contact-item"><a href="https://linkedin.com/in/thibaultgenissel" style="color:#2d6e3e;">LinkedIn</a></div>
        <div class="contact-item">SIREN: 104 565 536</div>
      </div>

    </div>
  </div>
      <div style="text-align: center;">
      <a href="/uploads/fiche_conferencier_genissel.pdf" class="download-btn" download>📄 Fiche PDF</a>
<!--  <div class="footer-quote">
    « La perfection des moyens et la confusion des buts semblent caractériser notre époque. » — A. Einstein
  </div>-->



</div>
{{</ raw >}}