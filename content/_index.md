---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-11-2
type: landing

# [book layout]({{< relref “_index.md” >}})

sections:
  - block: about.biography
    id: about
    content:
      title: Short Bio
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin



  - block: collection
    id: publications
    content:
      title: Publications and Papers
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      count: 3
      filters:
        folders:
          - publications
        exclude_featured: false
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '1'
      view: compact




  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Team member
          company: National Natural Science Foundation of China - Major Program Sub-Project
          location: Beijing, China
          date_start: '2022-04-01'
          date_end: ''
          description: |2-
              Subject:
              Land surface anomaly remote sensing response characteristics and semantic representation

              Responsibilities include:

              * Surveyed a total of 54 articles, and completed a 10,000-word report containing remote sensing response characteristics for three types of land surface anomalies.
              * Collected 42 real remote sensing early warning cases for land surface anomaly and relevant remote sensing data.
        - title: Team member
          company: Special Project of Science and Technology Basic Resources Survey
          location: Beijing, China
          date_start: '2022-01-01'
          date_end: '2022-12-01'
          description: |2-
              Subject: 
              Knowledge Points on the Overall Distribution and Variation of Land Cover

              Responsibilities include:

              * Extracted about hundreds of knowledge points about the overall distribution and changes of the three land cover types of forest, shrub and grassland from 2000 to 2020.
              * Automatically completed all knowledge point documents in batches using R language.
        - title: Team member
          company: Crop Field Survey in Shandong Province 
          location: Shandong, China
          date_start: '2022-08-01'
          date_end: '2022-09-01'
          description: |2-
              Responsibilities include:

              * Participated in collecting 736 sample points and 11 drone flight areas.
              * Designed rules for vegetable extraction using radar remote sensing feature and peak growth period extraction on the GEE platform
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true




  # - block: collection
  #   id: grant
  #   content:
  #     title: Awards & Grants
  #     filters:
  #       folders:
  #         - posts
  #   design:
  #     columns: '1'
  #     view: compact

  - block: collection
    id: event
    content:
      title: Recent posts
      filters:
        folders:
          - posts
    design:
      columns: '2'
      view: compact



   
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
      



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



 
# - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'


  
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'



  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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



  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'



  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'


---
