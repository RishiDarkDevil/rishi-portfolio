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
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
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
          description: Created several beautiful R Shiny and Data Analysis Reports
          icon: r-project
          icon_pack: fab
        - name: Deep Learning
          description: Worked on several Research Projects leveraing and improving Deep Learning Techniques
          icon: brain
          icon_pack: fas
        - name: Quantum Computing
          description: Worked on Quantum Machine Learning, Optimization and Challenge Problems 
          icon: atom
          icon_pack: fas
        - name: Data Structure Algorithms
          description: Skilled in Implementation of several Advanced Data Structure and Algorithms
          icon: network-wired
          icon_pack: fas
        - name: Statistics
          description: Skilled in Statistical Inference, Quality Control and Operations Research
          icon: chart-line
          icon_pack: fas
        - name: Probability
          description: Love solving puzzles and have exposure to Advanced Probability
          icon: dice
          icon_pack: fas
  - block: experience
    id: experience
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
              > Contributing towards a Research Paper.


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
              > Recieved The Best Project Award at the School of AI and Data Science during my Summer Internship.
              
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
              > Best Report and Presentation of Data Analysis.

              * Analysed the results of the surveys conducted on cyber abuse from various online and offline platforms.
              * Modelled the response of people to their chances of being a victim through Decision Trees.
              * Heirarchial Clustering revealed groups of people with similar traits who were cyber abused as well as groups prone to cyber abuse.
              * Public sentiments about awareness and ways to curb cyber abuse were mined using natural language processing and sentiment classifiers.
    design:
      columns: '2'
  - block: collection
    id: events
    content:
      title: Recent & Upcoming Events
      count: 2
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: Arsenal of self-motivated past and present projects in on AI, ML and Data Science, with their applications in NLP, CV, Comp Neuro and AI4SG
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
        - name: Comp Neuroscience
          tag: Comp Neuroscience
        - name: Statistics
          tag: Statistics
        - name: Other
          tag: Misc
      sort_by: 'Date'
      sort_ascending: false
      default_button_index: 1
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
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
      offset: 1
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle: Always Engaged in Learning and Achieving Milestones
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://drive.google.com/file/d/1i8Vd063pxUWLurP8d_G5zGrDcwCD_h9N/view?usp=sharing
          date_end: ''
          date_start: '2023-01-01'
          description: 'Selected among large number of applicants to be a part of the Research Week with Google Conference with top-notch researchers in AI and Machine Learning from across the world. My sub-track was Natural Language Understanding.'
          organization: Google
          organization_url: https://research.google/locations/india/
          title: Research Week With Google
          url: ''
        - certificate_url: https://drive.google.com/file/d/1gfMCd-fIn_w5xbr56P6ea6lMC60R2O12/view
          date_end: ''
          date_start: '2022-12-31'
          description: 'Selected in the top 8 teams out of over 192 competitors in the IndoML22 Datathon Challenge and Awarded a full scholarship to attend Indian Symposium on Machine Learning 2022 Conference at IIT Gandhinagar.'
          organization: IndoML
          organization_url: https://indoml.in/
          title: Top Team at IndoML22 Datathon Challenge
          url: ''
        - certificate_url: https://drive.google.com/file/d/1QzUfs2xDo__ha8-5xNQyAlteHNFcrUQp/view?usp=sharing
          date_end: ''
          date_start: '2022-08-18'
          description: 'Contributed by producing significant scientific findings to a complicated research problem in the intersection of Machine Learning and Computational Neuroscience. My work revealed directions for continuing further research on the topic, that can lead to significant understanding and discoveries.'
          organization: Indian Institute of Technology Jodhpur
          organization_url: https://indoml.in/
          title: Best Project Award in Summer Internship Program
          url: ''
        - certificate_url: https://drive.google.com/file/d/1oac_ItVyXMd5b0tvzszWtZjCK5-3s31q/view?usp=sharing
          date_end: ''
          date_start: '2022-09-18'
          description: 'Recieved Full Scholarship (1200$) for both semesters of The Quantum Computing course by IBM Quantum and the Coding School.'
          organization: IBM
          organization_url: https://www.ibm.com
          title: IBM Introduction to Quantum Computing
          url: ''
        - date_end: ''
          date_start: '2020-12-01'
          description: 'In Top 10 students of my Institute in the 1st year awarded for academic excellence'
          organization: Indian Statistical Institute
          organization_url: https://www.isical.ac.in/
          title: Top 10 Students
          url: ''
        - certificate_url: https://drive.google.com/file/d/1gfMCd-fIn_w5xbr56P6ea6lMC60R2O12/view
          date_end: ''
          date_start: '2022-12-18'
          description: ''
          organization: IndoML
          organization_url: https://indoml.in/
          title: Indian Symposium on Machine Learning
          url: ''
        - certificate_url: https://www.credly.com/badges/b49daf48-7d8c-4c94-81f2-94c5d091bc36/public_url
          date_end: ''
          date_start: '2022-11-25'
          description: ''
          organization: IBM
          organization_url: https://www.ibm.com
          title: IBM Quantum Fall Challenge - Advanced
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/TDVFTF6HSUEH
          date_end: ''
          date_start: '2022-10-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Generative Adversarial Networks Specialization
          url: ''
        - certificate_url: https://drive.google.com/file/d/18R9Zj1jtMGQMaAWaV-nbY3QudKHKwXUA/view
          date_end: ''
          date_start: '2022-09-25'
          description: ''
          organization: International Institute of Information Technology
          organization_url: https://www.iiit.ac.in/
          title: Summer School on AI
          url: ''
        - certificate_url: https://drive.google.com/file/d/1rOvS7bHF0s_QsxL8djH2MpZ-neUZqJ5J/view
          date_end: ''
          date_start: '2022-08-25'
          description: ''
          organization: Indian Statistical Institute
          organization_url: https://www.isical.ac.in/
          title: Independence Day Debate Competition
          url: ''
        - certificate_url: https://drive.google.com/file/d/1_gkPAr836YY9sCucpK1K5ebjUTVEPVDX/view
          date_end: ''
          date_start: '2022-08-25'
          description: ''
          organization: Indian Institute of Technology Jodhpur
          organization_url: https://www.iitj.ac.in/
          title: Summer Internship at School of AI and Data Science
          url: ''
        - certificate_url: https://drive.google.com/file/d/1Pa18JXUNgIQidlNnD36mtHH9vwBjqW86/view
          date_end: ''
          date_start: '2022-07-25'
          description: ''
          organization: International Institute of Information Technology
          organization_url: https://www.iiit.ac.in/
          title: Advanced Summer School on Natural Language Processing
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/MLVVJJ2P2KAX
          date_end: ''
          date_start: '2021-07-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Deep Learning Specialization
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/FXKVM9SXHYEC
          date_end: ''
          date_start: '2022-07-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Natural Language Processing Specialization
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/JVZYDX2CV7W9
          date_end: ''
          date_start: '2022-07-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Machine Learning Specialization
          url: ''
        - certificate_url: https://drive.google.com/file/d/1caZHvdJwRPyQY7ruBHI_GRYpsrDYpcKb/view
          date_end: ''
          date_start: '2022-03-25'
          description: ''
          organization: Indian Statistical Institute
          organization_url: https://www.isical.ac.in/
          title: Winter School for Deep Learning - From Perceptrons to Transformers
          url: ''
        - certificate_url: https://jovian.ai/certificate/MFQTMMBZGM
          date_end: ''
          date_start: '2021-10-25'
          description: ''
          organization: Jovian
          organization_url: https://www.jovian.com
          title: Data Structures & Algorithms in Python
          url: ''
        - certificate_url: https://www.kaggle.com/learn/certification/rishideychowdhury/python
          date_end: ''
          date_start: '2021-04-25'
          description: ''
          organization: Kaggle
          organization_url: https://www.kaggle.com/
          title: Python Basics
          url: ''
        - certificate_url: 'https://drive.google.com/file/d/1sTn6efGe-rAlHem3gDusqnKFnFFKC02e/view?usp=sharing'
          date_end: ''
          date_start: '2020-09-25'
          description: 'JEE Advanced is considered to be the toughest entrance examination for engineering students in India. I received an All India Rank of 2225 in JEE Advanced out of 200000 candidates who qualified JEE Mains out of 1.1 million students who appeared.'
          organization: JEE Advanced
          organization_url:
          title: All India Rank 2225 
          url: ''
        - certificate_url: 'https://drive.google.com/file/d/10NHskDRy07otJMY4dRY4olM6aDQPJE3Z/view?usp=sharing'
          date_end: ''
          date_start: '2020-09-25'
          description: 'Secured an All India Rank of less than 1500 for getting into Birla Institute of Technology, India, considered as one of the top engineering colleges in the same tier as IITs, with over 3,50,000 competing students.'
          organization: Birla Institute of Technology
          organization_url: 
          title: All India Rank 1500
          url: ''
        - certificate_url: 'https://drive.google.com/file/d/1v7qZspn-I9_uuZnNqPKNf8UGR6fWK6Tc/view?usp=sharing'
          date_end: ''
          date_start: '2020-10-25'
          description: 'Secured an All India Rank of 64 out of more than 60,000 students who appeared for the B.Stat entrance examination of ISI, ranked the topmost college in India for education in Statistics.'
          organization: Indian Statistical Institute
          organization_url:
          title: All India Rank 64
          url: ''
        - certificate_url: 'https://drive.google.com/file/d/1KozCt7DpdGIy9KxdYwQyDCiT3Folj7S-/view?usp=sharing'
          date_end: ''
          date_start: '2020-02-25'
          description: 'Secured an All India Rank of 238 out of 3,00,000 plus students who appeared. This exam is held for getting into the best engineering colleges in West Bengal with Jadavpur University at the top, which is in the same tier as IITs.'
          organization: WBJEE
          organization_url:
          title: All India Rank 238
          url: ''
    design:
      columns: '2'
  - block: markdown
    content:
      title: Memories
      subtitle: 'The Proper Function of Man is to Live, Not to Exist. I Shall Not Waste My Days in Trying to Prolong Them. I Shall Use My Time.'
      text: |-
        {{< gallery album="photos" >}}
    design:
      columns: '1'
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
        region: India
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
