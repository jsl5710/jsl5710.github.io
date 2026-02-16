---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-15
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ""
      button:
        text: Download Resumé
        url: uploads/jsl_resume.pdf

  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: resume-skills
    id: skills
    content:
      title: Skills & Hobbies
      username: admin

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

        {{< gallery album="demo" >}}
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
