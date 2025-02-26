---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#F5A9F2'
        gradient_start: '#FBEFFB'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Hello there!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor of Medicine 
          company: Cleveland Clinic Lerner College of Medicine  
          company_url: ''
          company_logo: lerner
          location: Cleveland, OH 
          date_start: '2023-05-01'
          date_end: ''

        - title: Staff Physician  
          company: Cleveland Clinic Respiratory Institute 
          company_url: ''
          company_logo: ccf
          location: Cleveland, OH 
          date_start: '2022-08-01'
          date_end: ''
        
        - title: Pulmonary & Critical Care Fellowship 
          company: Henry Ford Hospital 
          company_url: ''
          company_logo: hfhs
          location: Detroit, MI 
          date_start: '2019-07-01'
          date_end: '2022-06-30'

        - title: Clinical Instructor of Medicine 
          company: Wayne State University 
          company_url: ''
          company_logo: wsu
          location: Detroit, MI
          date_start: '2018-07-01'
          date_end: '2019-06-30'  

        - title: Chief Residency
          company: Wayne State University 
          company_url: ''
          company_logo: wsu
          location: Detroit, MI
          date_start: '2018-07-01'
          date_end: '2019-06-30'

        - title: Internal Medicine Residency 
          company: Wayne State University 
          company_url: ''
          company_logo: wsu
          location: Detroit, MI
          date_start: '2015-07-01'
          date_end: '2018-06-30'  
     
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Board Certification'
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - organization: American Board of Internal Medicine 
          date_start: '2022-11-15'
          description: ''
          icon: abim
          organization_url: https://www.abim.org/
          title: Critical Care Medicine
          url: ''

        - organization: American Board of Internal Medicine   
          date_start: '2021-11-29'
          description: ''
          icon: abim
          organization_url: https://www.abim.org/
          title: Pulmonary Diseases
          url: ''

        - organization: American Board of Internal Medicine  
          date_start: '2018-10-29'
          description: ''
          icon: abim
          organization_url: https://www.abim.org/
          title: Internal Medicine
          url: ''

    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Certification'
      items:
      
      - organization: International Guideline Training and Certification Program 
        date_start: '2024-04-30'
        description: ''
        icon: inguide
        organization_url: https://inguide.org/
        title: Certified Guideline Panelist 
        url: ''

      - organization: SAS 
        date_start: '2023-12-15'
        description: ''
        icon: sas
        organization_url: https://www.sas.com/en_us/certification/credentials/foundation-tools/base-programming-specialist.html
        title: SAS Certified Specialist
        url: '' 

      - organization: Stanford University Faculty Development Center  
        date_start: '2018-12-31'
        description: ''
        icon: stanford
        title: Stanford Clinical Teaching Program 
        url: ''    
    
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc

    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Guidelines
          tag: Guidelines
        - name: Other
          tag: Other 
        - name: Large Data
          tag: Large Data
    
      design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Pancakes
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}

    design:
      columns: '2'
      view: compact
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false


    design:
      columns: '2'
  - block: collection
    id: instavlog
    content:
      title: InstaVlog
      subtitle: Rhyming Instagram Stories
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - instavlog
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
  
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics

 
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
