---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: Built several end to end projects AI and ML Projects in Python
          icon: python
          icon_pack: fab
        - name: Natural Language Processing
          description: Worked extensively on Machine Translation and Document Representation
          icon: language
          icon_pack: fas
        - name: Computer Vision
          description: Worked Extensively on Joint Embedding, Object Detection and Image Segmentation
          icon: eye
          icon_pack: fas
        - name: R
          description: Created beautiful R Shiny and Data Analysis Reports in R
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: Skilled in Statistical Inference, Quality Control and Operations Research
          icon: chart-line
          icon_pack: fas
        - name: Probability
          description: Love solving puzzles and have exposure to Advanced Probability
          icon: dice
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      subtitle: My past work included mostly Multi-Modal Learning, Computational Learning and AI Fairness.
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern
          company: AI Institute of University of South Carolina
          company_url: 'https://aiisc.ai/'
          company_logo: aiisc
          location: Columbia, South Carolina
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Working with <a href="http://amitavadas.com/" target="_blank" rel="noopener">Professor Amitava Das</a> in the Joint Embedding Group.
              * Developing Large-Scale Data Generation Pipeline for Text-Based Object Discovery to tackle Extreme Object Detection and Classification.
              * Leveraging the above system to generate richer visuo-textual joint embedding using contextual and self-supervised learning and RPE transformer.
              * Handling downstream tasks of detecting harmful meme content, labelling food items, image-to-text and text-to-image retrieval.
        - title: Summer Research Intern
          company: Cognitive Brain Dynamics Lab at IIT Jodhpur
          company_url: 'https://cbdlnbrc.weebly.com/'
          company_logo: IITJ
          location: Jodhpur, Rajasthan
          date_start: '2022-05-15'
          date_end: '2022-08-31'
          description: |2-
              * Recieved Best Project Award in the School of AI and Data Science during my Summer Internship.
              * Worked on unraveling uncertainty as a major underlying latent variable for explaining emotional dynamics.
              * Study revealed significant uncertainty representation difference in young and old subjects and identified the Brain Regions capturing this.
              * Devised improved sequence models for multivariate BOLD time series predictions and entropy estimation for each Brain ROIs, for quantifying outcome uncertainty.
              * Implemented modified dimension reduction and manifod learning techniques for Brain image data in order to capture neural uncertainty representation.
        - title: Data Science Intern
          company: People Against Cyber Abuse
          company_url: 'https://www.linkedin.com/company/pacaorg/'
          company_logo: PACA
          location: Delhi
          date_start: '2021-12-31'
          date_end: '2022-01-31'
          description: |2-
              * Analysed the results of the surveys conducted on cyber abuse from various online and offline platforms.
              * Modelled the response of people to their chances of being a victim through Decision Trees.
              * Heirarchial Clustering revealed groups of people with similar traits who were cyber abused as well as groups prone to cyber abuse.
              * Public sentiments about awareness and ways to curb cyber abuse were mined using natural language processing and sentiment classifiers.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
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
      subtitle: Arsenal of self-motivated past and present projects, focussing on AI, ML and Data Science, with their applications in NLP, CV, Comp Neuro and AI4SG
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
        - name: Deep Learning
          tag: Deep Learning
        - name: NLP
          tag: NLP
        - name: Computer Vision
          tag: Computer Vision
        - name: Data Analysis
          tag: Statistics
        - name: Comp Neuroscience
          tag: Comp Neuroscience
        - name: Other
          tag: Misc
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Events
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: showcase
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Get In Touch
      subtitle: Let's build, research and collaborate.
      text: |-
        Feel me to reach me out. I am always in an outlook for great people and awesome work.
      # Contact (add or remove contact options as necessary)
      email: rishi8001100192@gmail.com
      appointment_url: 'https://calendly.com/rishidarkdevil/30min'
      address:
        street: Indian Statistical Institute
        city: Kolkata
        region: APAC
        postcode: '700108'
        country: India
        country_code: IN
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Connect with Me on LinkedIn
          link: 'https://www.linkedin.com/in/rishi-dey-chowdhury/'
        - icon: twitter
          icon_pack: fab
          name: Send Me a DM on Twitter
          link: 'https://twitter.com/rishidarkdevil'
        - icon: instagram
          icon_pack: fab
          name: Send Me a DM on Instagram
          link: 'https://www.instagram.com/rishidarkdevil/'
        - icon: facebook
          icon_pack: fab
          name: Send Me a DM on Facebook
          link: 'https://www.facebook.com/rishi.deychowdhury'
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
