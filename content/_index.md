---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-31
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
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD
          company: Dept. "Robotics, Brains and Cognitive Science", Italian Institute of Technology
          company_url: 'https://www.iit.it/it/home'
          # company_logo: ''
          location: Genova, Italy
          date_start: '2010-01-01'
          date_end: '2012-12-31'
          description: Motion and force control of the iCub humanoid robot, using force and tactile sensors.

        - title: Post-Doc
          company: iCub Facility, Italian Institute of Technology
          company_url: 'https://www.iit.it/it/cris-sanquirico'
          # company_logo: ''
          location: Genova, Italy
          date_start: '2013-01-01'
          date_end: '2013-12-31'
          description: |2-
              Multi-contact force control for the iCub humanoid robot, in the framework of the CoDyCo EU project.

        - title: Post-Doc / Associated Researcher
          company: Gepetto team, LAAS/CNRS
          company_url: 'http://projects.laas.fr/gepetto/index.php'
          # company_logo: ''
          location: Toulouse, France
          date_start: '2014-01-01'
          date_end: '2017-12-31'
          description: |2-
              Control of the humanoid robot HRP-2 using robust optimization, stochastic optimization, motor identification, torque control, hierarchical trajectory 
              optimization.

        - title: Research Scientist
          company: Max Planck Institute for Intelligent Systems
          company_url: 'https://is.tuebingen.mpg.de/person/lrighetti'
          # company_logo: org-x
          location: Tuebingen, Germany
          date_start: '2018-01-01'
          date_end: '2018-12-31'
          description: Optimization-based control for the humanoid robot Athena.

        - title: Assistant Professor (tenure track)
          company: Industrial Engineering Department, University of Trento
          company_url: 'https://www.dii.unitn.it'
          # company_logo: org-x
          location: Trento, Italy
          date_start: '2019-01-01'
          date_end: '2021-12-31'
          description: Research on robot co-design, robust and stochastic model predictive control. Teaching computer programming and optimization-based robot control.

        - title: Associate Professor
          company: Industrial Engineering Department, University of Trento
          company_url: 'https://www.dii.unitn.it'
          # company_logo: org-x
          location: Trento, Italy
          date_start: '2022-01-01'
          description: Carrying out research on merging learning and model-based techniques to achieve safe robot control. Teaching courses on robotics and programming for bachelor and master students.
    design:
      columns: '2'
  
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  
  - block: portfolio
    id: courses
    content:
      title: Courses
      filters:
        folders:
          - courses
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      # default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true

  - block: collection
    id: students
    content:
      title: PhD Students
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - students
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


  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      # Contact (add or remove contact options as necessary)
      email: andrea.delprete@unitn.it
      phone: 0039 0461 281915
      # appointment_url: 'https://calendly.com'
      address:
        street: Via Sommarive 9
        city: Trento
        postcode: '38123'
        country: Italy
        country_code: IT
      directions: Enter the building "Povo 2", take the stairs to the 1st floor, go left until the end of the corridor.
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
