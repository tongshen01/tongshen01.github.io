---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
#      featured_only: false
    design:
      columns: '2'
#     view: card

  - block: experience
    id: research
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Quantum Spin liquid and Kitaev honeycomb model
          company: Advised by Prof. Yang Qi, Fudan University
          company_url: ''
          company_logo: 
          location: Shanghai
          date_start: '2022-10-01'
          date_end: '2022-12-01'
          description: |2-
              
              * Review the concept of quantum spin liquid state and RVB theory
              * Study how to solve Kitaev honeycomb model using Majorana decomposition
              * Group work for the course Thermodynamics & Statistical Physics II
    
        - title: AdS/CFT Duality
          company: Advised by Prof. Yang Zhou, Fudan University
          company_url: ''
          company_logo: 
          location: Shanghai
          date_start: '2022-02-01'
          date_end: '2022-06-01'
          description: |2-
              
              * Review the correspondence between field theories and string theory. Focus on the relation between compactifications of string theory on Anti-de Sitter spaces and conformal field theories
              * Group work for the honors course in Methods of Mathematical Physics. Grade A
              {{% staticref "uploads/resume.pdf" "newtab" %}}**Click to view more details**{{% /staticref %}}

    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
#      subtitle:
#      text: |-
#      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: tongshen2022@gmail.com
      phone: (+86) 13248087846
#     appointment_url: 'https://calendly.com'
      address:
        street: No.220 Handan Rd
        city: Shanghai
#       region: CA
        postcode: '200433'
        country: P.R. China
        country_code: CN
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#       - icon: video
#         icon_pack: fas
#         name: Zoom Me
#         link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
