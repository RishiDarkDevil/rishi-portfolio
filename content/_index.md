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
          description: This is my go-to language at the moment. Have written several packages in Python.
          icon: python
          icon_pack: fab
        - name: Computer Vision
          description: Worked Extensively on Face Recognition, Object Detection and Image Segmentation
          icon: eye
          icon_pack: fas
        - name: Natural Language Processing
          description: Worked extensively on Machine Translation, Document Representation and LLMs
          icon: language
          icon_pack: fas
        - name: Quant Trading Research
          description: Recently gained interest in this field. Working on Market Microstructure simulation.
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Deep Learning
          description: Contributed to several research work towards improving fairness and performance of DL Systems
          icon: brain
          icon_pack: fas
        - name: Quantum Computing
          description: Contributed to Transpilation Methods for advancement of NISQ Quantum Hardware
          icon: atom
          icon_pack: fas
        - name: Data Structure Algorithms
          description: Skilled in Implementation of several Advanced Data Structure and Algorithms
          icon: network-wired
          icon_pack: fas
        - name: Statistics
          description: Skilled in Statistical Inference, Stochastic Processes and Learning Theory
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
      subtitle: My past work mostly include Quant Finance, Quantum Computing, Computer Vision, NLP and GenAI.
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - title: Model Risk Quant
          company: JPMorgan Chase & Co.
          company_url: 'https://www.jpmorgan.com/global'
          company_logo: jpmc
          location: Bangalore, India
          date_start: '2024-05-20'
          date_end: '2024-07-12'
          description: |2-
              > Contributed to Transaction Model Risk Management and Review. Streamlined and automated key components of the Model Review Workflow.

        - title: Quantum Computing Research Intern
          company: IBM Quantum Research India
          company_url: 'https://research.ibm.com/labs/india'
          company_logo: ibm
          location: Bangalore, India
          date_start: '2024-02-01'
          date_end: '2024-05-13'
          description: |2-
              > Contributed to Traspilation Methods for efficient and fast mapping of Program Quantum Circuit on Hardware Topology Circuit via Graph-Cutting Algorithms. 

              Responsibilities included:

              * Worked with <a href="https://research.ibm.com/people/ritajit-majumdar--1" target="_blank" rel="noopener">Ritajit Majumdar</a>, <a href="https://research.ibm.com/people/anupama-ray" target="_blank" rel="noopener">Anupama Ray</a> and several other collaborators.
              * Devised a novel graph cutting method for implementing a large program circuit to be run on limited qubits NISQ Hardware efficiently.

        - title: Computer Vision Research Intern
          company: Trust AI and Biometrics Lab at IIT Jodhpur
          company_url: 'http://iab-rubric.org/'
          company_logo: iab
          location: Jodhpur, Rajasthan
          date_start: '2023-05-01'
          date_end: '2024-04-08'
          description: |2-
              > Contributed towards Neural Face Recognition Robustness Research Paper.
              > Contributed towards Biometric Capacity and Fairness of Deep FR Systems.

              Responsibilities include:

              * Worked with <a href="https://research.iitj.ac.in/researcher/richa-singh-2" target="_blank" rel="noopener">Prof Richa Singh</a> and <a href="https://research.iitj.ac.in/researcher/mayank-vatsa" target="_blank" rel="noopener">Mayank Vatsa</a>.
              * Created a Multi-Threaded Fast benchmarking pipelines for robustness of Neural Face Recognition systems.
              * Improved previously existing Fairness Benchmarks for Face Recognition Systems with new metrics and dataset creation.
              * Contributed to ongoing research on Biometric Capacity of Diffusion and other Generative AI Models through Prompt Engineering.

        - title: Deep Learning Research Intern
          company: AI Institute of University of South Carolina
          company_url: 'https://aiisc.ai/'
          company_logo: aiisc
          location: Columbia, South Carolina
          date_start: '2022-09-01'
          date_end: '2023-09-01'
          description: |2-
              > Contributed toward Unsupervised Image Segmentation, Object Detection and Generative AI Research.

              Responsibilities included:

              * Worked with <a href="http://amitavadas.com/" target="_blank" rel="noopener">Professor Amitava Das</a> in the Joint Embedding Group.
              * Developed a Novel Attention-Diffusion Algorithm for unsupervised semantic segmentation and object detection using Diffusion models.
              * Developed Large-Scale Data Generation Pipeline for Text-Based Object Discovery to tackle Extreme Object Detection and Classification.
              * Leveraged the above system to generate richer visuo-textual joint embedding using contextual and self-supervised learning and RPE transformer.
        - title: Natural Language Processing Research Intern
          company: Uniphore
          company_url: 'https://www.uniphore.com/'
          company_logo: uniphore
          location: Bangalore, India
          date_start: '2023-06-01'
          date_end: '2023-08-10'
          description: |2-
              > Improved the existing system in production for annotating speech transcript data at scale and presented my work at IndoML23 Tutorial Session.
              
              * Collaborated with a team of NLP Researchers on designing a Data Programming Pipeline using Active Learning and Weak Supervision.
              * Designed a no-code Web Interface to label large Natural Language and Transcript datasets at scale.
              * Improved existing enterprise labelling systems by incorporating Semantic Search, Hierarchical and Community Clustering strategies to label data at speed.
              * Improved existing Active Learning approach by chaining Ensemble Models and Label Model for Single Label Classification Task.
        - title: Computational Neuroscience Research Intern
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
      subtitle: Events That Keep Me Up-to-Date
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
      subtitle: Arsenal of self-motivated past and present projects in AI, ML and Data Science, with their applications in NLP, CV, Computational Neuroscience and AI For Social Good
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
        - name: Computer Vision
          tag: Computer Vision
        - name: NLP
          tag: NLP
        - name: Comp Neuroscience
          tag: Comp Neuroscience
        - name: Reinforcement Learning
          tag: Reinforcement Learning
        - name: Quantum Computing
          tag: Quantum Computing
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
      subtitle: 'Teaching is a Great Way to Keep Learning'
      text: |-
        I frequently put down my thoughts on [Medium](https://medium.com/@rishidarkdevil) about my research works, interesting puzzles and heart-stirring experiences 
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
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
      count: 5
      items:
        - certificate_url: https://drive.google.com/file/d/1sUPdRAYLiFOnm4RHzSpoeWG92GJ7r71k/view?usp=sharing
          date_end: ''
          date_start: '2023-08-01'
          description: ''
          organization: Oxford
          organization_url: https://www.ox.ac.uk/
          title: Machine Learning Summer School
          url: ''
        - certificate_url: https://drive.google.com/file/d/1TJwuk0S6mn86yKpt9K6WtkMPHAB8bnzQ/view?usp=sharing
          date_end: ''
          date_start: '2023-07-18'
          description: ''
          organization: Akuna
          organization_url: https://akunacapital.com/
          title: Options 101
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/XMSKXJNTUW5C
          date_end: ''
          date_start: '2023-04-11'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Reinforcement Learning Specialization
          url: ''
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
        Feel free to reach me out. I am always in an outlook for great people and awesome work.
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
        provider: formspree
        formspree:
          id: xvonkrgn
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
