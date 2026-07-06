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

.group.flex.no-underline {
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


<div class="speaker-page">

  <div class="speaker-header">
<div style="font-size: clamp(1rem, 3vw, 2.5rem); font-weight: 900; color: var(--tw-prose-headings, #111827); font-family: inherit; margin-bottom: 0.5rem; line-height: 1.1; letter-spacing: -0.02em;">Speaker Profile</div>
 <img src="/bandeau.jpg" alt="" class="speaker-banner">

  <h1 class="speaker-title">Environmental Transition & Biodiversity</h1>
  </div>

  <div class="main-layout">
    <div class="left-col">

     <!-- <div class="section-label">Profile</div --> 
      <p class="profile-text">
        I am a researcher specialised in applied conservation biology and alumnus of the École Normale Supérieure de Lyon, I deliver talks and presentations on a wide range of topics, tailored to the needs of the host institution. My doctoral work, conducted at the Muséum National d'Histoire Naturelle, focused on the evocentric approach to conservation and led to the development of the Evolutionary Footprint framework — a standardised tool for quantifying the evolutionary impact of human activities on biodiversity.
      </p>
      <p class="profile-text">
        Through a multidisciplinary background built on three master's degrees in biology, agronomy, and philosophy of science, my positioning is unique. I offer an integrative vision of contemporary challenges, combining life sciences, environmental philosophy, and political, economic, and social sciences.
      </p>

      <div class="quote-block">
        "Ecocentrism comes down to a few words: leave room, leave margins. Nature conservation is Sisyphean. But we keep proposing other possibilities. And all things considered, we should not fight to conserve. No, what we want above all is to enable."
      </div>

      <div class="section-label" style="margin-top:2rem;">Proposed talks</div>
      <div style="margin-top: 1rem;text-align: center;">
        <a href="/en/book/" style="display: inline-flex; align-items: center; gap: 0.5rem; background: linear-gradient(to right, #2d6e3e, #1a4d28); color: white; padding: 0.8rem 1.6rem; font-size: 0.9rem; font-weight: 700; text-decoration: none; border-radius: 0.75rem; box-shadow: 0 4px 12px rgba(45,110,62,0.3); transition: all 0.3s;"> Go to talk proposals page</a>
      </div>

      <div class="section-label" style="margin-top:2rem;">Cross-perspectives: off-topic themes</div>
      <div class="cross-grid">
        <div class="cross-item">
          <h4>Human-Animal Perspectives</h4>
          <p>Exploring pathways of coexistence between the wild world and human societies</p>
        </div>
        <div class="cross-item">
          <h4>Alpine Futures: rethinking the mountain</h4>
          <p>The Alps as a model of ecosystem and land-use transformation</p>
        </div>
        <div class="cross-item">
          <h4>Writing the Living</h4>
          <p>Reimagining narratives by opening contemporary issues to literature</p>
        </div>
      </div>

      <div class="section-label" style="margin-top:2rem;">Formats</div>
      <div class="formats-grid">
        <div class="format-item">
          <span class="format-icon">🎤</span>
          <span class="format-name">Talk</span>
          <span class="format-duration">45–60 min</span>
        </div>
        <div class="format-item">
          <span class="format-icon">💬</span>
          <span class="format-name">Round table</span>
          <span class="format-duration">30–90 min</span>
        </div>
        <div class="format-item">
          <span class="format-icon">✏️</span>
          <span class="format-name">Workshop</span>
          <span class="format-duration">2–3 hours</span>
        </div>
        <div class="format-item">
          <span class="format-icon">🍽</span>
          <span class="format-name">Lunch debate</span>
          <span class="format-duration">1 hour</span>
        </div>
        <div class="format-item">
          <span class="format-icon">💻</span>
          <span class="format-name">Webinar</span>
          <span class="format-duration">Flexible</span>
        </div>
      </div>

    </div>

    <div class="sidebar">

      <div class="sidebar-section">
        <div class="section-label">Domains</div>
        <ul>
          <li>Conservation Sciences</li>
          <li>Ecology / Evolution</li>
          <li>Ethics</li>
          <li>Biodiversity COP</li>
          <li>Biodiversity Indicators</li>
          <li>Reintroduction, Rewilding</li>
          <li>Animal Behaviour</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Academic profile</div>
        <ul>
          <li>École Normale Sup. de Lyon</li>
          <li>PhD, jury distinction</li>
          <li>MA Philosophy, Paris IV</li>
          <li>MS CLUES, AgroParisTech</li>
          <li>MS Complex Systems, ENSL</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Engagements</div>
        <ul>
          <li>COP 15 Kunming-Montreal</li>
          <li>IUCN Education Committee</li>
          <li>ECCB 2024</li>
          <li>Port-Cros National Park</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Teaching</div>
        <ul>
          <li>Lecturer, Sorbonne Univ.</li>
          <li>Undergraduate–Master biology</li>
          <li>Private tutoring</li>
          <li>Medicine & prep school exams</li>
        </ul>
      </div>

      <div class="sidebar-section">
        <div class="section-label">Availability</div>
        <ul>
          <li>All of France</li>
          <li>In-person & remote</li>
          <li>Bespoke talks</li>
          <li>Invoiced as sole trader</li>
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
      <a href="/uploads/speaker_sheet_genissel.pdf" class="download-btn" download>📄 Speaker sheet</a>
<!--  <div class="footer-quote">
    « La perfection des moyens et la confusion des buts semblent caractériser notre époque. » — A. Einstein
  </div>-->


</div>
{{</ raw >}}