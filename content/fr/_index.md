---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-09-29
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: /uploads/CV_Génissel.pdf
      button2:
        text: Fiche conférencier
        url: /uploads/fiche_conferencier_genissel.pdf       
      headings:
        about: ''
        education: ''
        interests: ''
      themes_title: 'Thèmes des conférences'
      themes:
        - History of Conservation
        - Climate & Biodiversity Crisis
        - Institutions & Indicators of Environmental Transition      
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
     

  - block: markdown
    content:
    #  title: '📚 Ma Recherche'
      subtitle: ''
      text: |-
        <style>
          .page-body   {background: linear-gradient(135deg, #fdf8f3 0%, #f0e6d3 100%)}
         /*.dark .page-body { background: #3b2b19  }*/
          .dark .page-body { background: none }
          .hbb-section { padding-top: 0 !important; margin-top: 0 !important; }
          .blox-markdown { padding-top: 0 !important; margin-top: 0 !important; }
          .prose p { text-align: justify; }
           article { padding-top: 0 !important; }
          main { padding-top: 0 !important; }
        </style>
        <div style="display: flex; align-items: center; justify-content: center; gap: 1rem; margin-bottom: 2rem;">
          <svg class="w-8 h-8 text-primary-600 dark:text-primary-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
          <h2 style="font-size: 1.8rem; font-weight: 700; margin: 0;">Ma Recherche</h2>
        </div>
        <div style="text-align: justify;">

        Mes travaux portent sur les liens entre science, société et conservation de la biodiversité. Dans le cadre de ma thèse à Sorbonne Université, j'ai travaillé sur l'approche évocentrée, qui promeut une meilleure intégration de l'évolution en conservation et la réduction de l'empreinte évolutive humaine sur les vivants. Mes recherches explorent les métriques et concepts de l'approche évocentrée, ainsi que leur mise en œuvre dans les politiques et pratiques de conservation. Mon parcours s'est nourri d'un travail sur le comportement animal, l'écologie spatiale et les interactions sociales chez les mammifères (primates, ongulés), ainsi que de ma participation à des forums internationaux (COP15 biodiversité, UICN) où sont débattus les grands enjeux de la conservation. De manière plus locale, je porte un intérêt personnel fort pour les écosystèmes de montagne, leur compréhension et la protection de leur faune et de leur flore.

        Contactez-moi pour collaborer! 
        </div>
    design:
      columns: '1'
      css_class: 'universal-wrapper'
      spacing:
        padding: ['0', '1rem', '0', '1rem']
  - block: collection
    id: papers
    content:
      title: Travaux sélectionnés
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications récentes
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Conférences récentes & à venir
  #     filters:
  #       folders:
  #         - book #events
  #       featured_only: true
  #   design:
  #     view: card 
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: blog
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ''
#        category: ''
#        tag: ''
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ''
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: card
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300'
        css_style: ''
---
