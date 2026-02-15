---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-15
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      title: About Me
      username: admin

  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Graduate Assistant
          company: Penn State University
          company_url: 'https://psu.edu'
          company_logo: org-psu
          location: Pennsylvania, US
          date_start: '2021-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Lead ML/NLP research combating harmful content across 79 languages
              * Published 12 papers (260+ citations) in ACL, EMNLP, NAACL, IEEE
              * Mentor 5+ interns and manage 3 computing courses (150+ students)
              * Develop end-to-end AI pipelines using PyTorch, HuggingFace, cloud APIs
              * NSF Fellow: $9K funding for interdisciplinary AI research
        - title: DSSI Graduate Research Intern
          company: Lawrence Livermore National Lab
          company_url: 'https://www.llnl.gov/'
          company_logo: org-llnl
          location: Livermore, CA
          date_start: '2025-05-01'
          date_end: '2025-08-01'
          description: |2-
              Focus Areas:

              * NLP, LLM, LRM, MLLM development and optimization
              * Safe AI and reasoning systems research
              * Mixture-of-Agents architectures
              * Multilingual AI system development
        - title: NLP Research Intern
          company: Interaction LLC
          company_url: 'https://www.interactions.com/'
          company_logo: org-interaction
          location: Remote
          date_start: '2024-05-01'
          date_end: '2024-08-01'
          description: |2-
              Research & Development:

              * NLP and Intelligent Virtual Assistant (IVA) development
              * Large Language Model optimization and prompt engineering
              * Conversational AI and dialogue summarization systems
              * Advanced LLM integration for customer interaction platforms
        - title: Cybersecurity Consultant Intern
          company: Coalfire
          company_url: 'https://coalfire.com/'
          company_logo: org-coalfire
          location: Remote
          date_start: '2023-05-01'
          date_end: '2023-08-01'
          description: |2-
              Security & Compliance:

              * AI applications for cybersecurity threat detection
              * Security compliance and standards implementation
              * Security Operations Center (SOC) operations
              * Payment Card Industry (PCI) compliance frameworks
        - title: Faculty - Instructor, Head of Division & Technical Lead
          company: St. George's University
          company_url: 'https://www.sgu.edu/'
          company_logo: org-sgu
          location: Grenada, WI
          date_start: '2011-06-01'
          date_end: '2021-07-01'
          description: |2-
              Leadership & Education:

              * Led 6-person team supporting 4000+ medical students
              * Achieved 99% uptime on SimCapture/Examsoft platforms
              * Pioneered virtual OSCE system during COVID-19, trained 100+ faculty
              * Taught IT, Medical, and Public Health Informatics courses
        - title: Information Technology Instructor
          company: Government of Grenada
          company_url: ''
          company_logo: org-gnd
          location: Grenada, WI
          date_start: '2010-08-01'
          date_end: '2011-07-01'
          description: Managed IT infrastructure for 500+ students; achieved 95% pass rate in CSEC IT examinations; implemented digital literacy program reaching 300+ students.
    design:
      columns: '2'

  - block: resume-skills
    id: skills
    content:
      title: Skills
      text: ''
      username: admin
    design:
      columns: '2'

  - block: collection
    id: service
    content:
      title: Service & Leadership
      subtitle: ''
      text: '[View all service roles →](./service/)'
      count: 4
      filters:
        folders:
          - service
      order: desc
    design:
      view: card
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: All Publications
      text: |-
        > [!NOTE]
        > Quickly discover relevant content by [filtering publications](./publication/).
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: '2'

  - block: collection
    id: talks
    content:
      title: Talks & Media Presence
      filters:
        folders:
          - event
    design:
      view: card
      columns: '2'

  - block: collection
    id: posts
    content:
      title: Recent News
      subtitle: ''
      text: ''
      count: 5
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
      offset: 0
      order: desc
    design:
      view: card
      columns: '2'

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Multilingual NLP
          tag: Multilingual NLP
        - name: Deep Learning
          tag: Deep Learning
    design:
      view: card
      columns: '1'

  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        Browse photos from conferences, presentations, and campus life.
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        Book an appointment or contact me using the information below.

        **Email:** [jsl5710@psu.edu](mailto:jsl5710@psu.edu)

        **Phone:** [954 864 4494](tel:9548644494)

        **Address:** 123 S Burrowes St, State College, PA 16801, United States

        **Directions:** Enter Building and take the elevator or stairs to the 4th Floor, locate College of IST.

        **Office Hours:** Monday & Wednesday, 09:00–17:00

        ---

        [Book a Meeting](https://calendly.com/jasonsamlucas/meeting) | [DM on Twitter](https://twitter.com/jasonslucas1) | [Zoom Me](https://psu.zoom.us/my/jasonslu)
    design:
      columns: '2'
---
