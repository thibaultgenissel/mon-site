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
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/CV_genissel.pdf
      button2:
        text: Download Speaker Sheet
        url: uploads/speaker_sheet_genissel.pdf        
      headings:
        about: ''
        education: ''
      #  interests: ''
      themes:
        - History of Conservation
        - Climate & Biodiversity Crisis
        - Institutions & Indicators of Environmental Transition
  
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # - block: markdown
  #   content:
  #     title: ''
  #     subtitle: ''
  #     text: |-
  #       <h3 style="font-weight: 700; color: #1a3d28; text-align: center; margin-bottom: 1.5rem; font-size: 1rem; letter-spacing: 0.15em; text-transform: uppercase; font-family: inherit;">Talk Topics</h3>
  #       <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 2.5rem; align-items: stretch;">
  #         <div style="background: linear-gradient(160deg, #f5ebe0 0%, #e8d5c0 100%); padding: 2.5rem 1.5rem; display: flex; align-items: center; justify-content: center; border-radius: 16px; box-shadow: 0 6px 20px rgba(61,42,26,0.2); border: 2px solid #8b6340;">
  #           <p style="font-weight: 600; color: #61462d; font-size: 1.3rem; line-height: 1.5; text-align: center; font-family: inherit; text-transform: uppercase; margin: 0;">History<br>of<br>Conservation</p>
  #         </div>
  #         <div style="background: linear-gradient(160deg, #f5ebe0 0%, #e8d5c0 100%); padding: 2.5rem 1.5rem; display: flex; align-items: center; justify-content: center; border-radius: 16px; box-shadow: 0 6px 20px rgba(61,42,26,0.2); border: 2px solid #8b6340;">
  #           <p style="font-weight: 600; color: #61462d; font-size: 1.3rem; line-height: 1.5; text-align: center; font-family: inherit; text-transform: uppercase; margin: 0;">Climate<br>&amp;<br>Biodiversity<br>Crisis</p>
  #         </div>
  #         <div style="background: linear-gradient(160deg, #f5ebe0 0%, #e8d5c0 100%); padding: 2.5rem 1.5rem; display: flex; align-items: center; justify-content: center; border-radius: 16px; box-shadow: 0 6px 20px rgba(61,42,26,0.2); border: 2px solid #8b6340;">
  #           <p style="font-weight: 600; color: #61462d; font-size: 1.3rem; line-height: 1.5; text-align: center; font-family: inherit; text-transform: uppercase; margin: 0;">Institutions<br>of<br>Environmental<br>Transition</p>
  #         </div>
  #       </div>
  #   design:
  #     columns: '1'
  #     spacing:
  #       padding: ['0', '0', '0', '0'] 

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
          <h2 style="font-size: 1.8rem; font-weight: 700; margin: 0;">My Research</h2>
        </div>
        <div style="text-align: justify;">

         I am interested in the connections between science, society, and biodiversity conservation. As part of my PhD at Sorbonne University, I worked the evocentric approach that promotes more integration of evolution in conseration and the reduction of the human evolutionary footprint on life. My research explores metrics and assessment tools and their implementation in conservation policies and practices. My academic path has also led me to study animal behavior, ecology and social interactions (primates, ungulates) and to take part in international forums (COP15 biodiversity, IUCN) where major biodiversity challenges are discussed. Beyond this, I have a strong personal interest in mountain ecosystems, for their understanding, their protection, and for fostering  ways of living that adapt to their changes while limiting our impact.

        Please reach out to collaborate!
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Works
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - book #events
#        featured_only: true
#    design:
#      view: card
  - block: collection
    demo: true
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
  #     Page type to display. E.g. post, talk, publication...
      page_type: blog
  #    Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
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
