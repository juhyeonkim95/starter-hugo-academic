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
  - block: markdown
    content:
      title: News
      subtitle: ''
      text: 
    design:
      columns: '1'
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD in Computer Science
          company: Dartmouth College
          company_url: ''
          company_logo: dart
          location: Hanover, New Hampshire
          date_start: '2022-09-01'
          date_end: ''
          # description: Major in Electrical and Computer Engineering
        - title: MSc in Electrical and Computer Engineering
          company: Seoul National University
          company_url: ''
          company_logo: snu
          location: Seoul
          date_start: '2019-09-01'
          date_end: '2022-02-28'
          description: |2-
              * Thesis : Fast and lightweight Path Guiding Algorithm on GPU
        - title: BSc in College of Liberal Arts
          company: Seoul National University
          company_url: ''
          company_logo: snu
          location: Seoul
          date_start: '2014-03-01'
          date_end: '2019-08-31'
          description: |2-
            * Major in Electrical and Computer Engineering
            * Thesis : Efficient Taxi Dispatch Strategy using Deep Reinforcement Learning
    design:
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="render" >}}
    design:
      columns: '1'
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: card
---
