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
      text: |-
        * 2025.06. I received [Neukom Research Prize](https://neukom.dartmouth.edu/research/neukom-research-prizes/2025-research-prize-winners) (2nd prize)
        * 2025.06. Our [paper](publication/2025ohd) received [SIGGRAPH 🏆Honorable mention](https://blog.siggraph.org/2025/06/siggraph-2025-technical-papers-awards-best-papers-honorable-mentions-and-test-of-time.html/)!
        * 2025.05. One EGSR [paper](publication/2025wave) accepted!
        * 2025.05. One SIGGRAPH [paper](publication/2025ohd) accepted!
      # 2024.06. I will be working at Intel for summer internship!
      # 2024.05. One ICCP [paper](publication/2024tas/index.md) accepted!
      # 2023.11. One SIGGRAPH Asia [paper](publication/) accepted!
      # 2023.05. One SIGGRAPH paper accepted!
    design:
      columns: '2'
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
  - block: experience
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
        - title: Summer Intern
          company: Intel
          company_url: ''
          company_logo: intel
          location: Bellevue, Washington
          date_start: '2024-06-10'
          date_end: '2024-09-10'
          description: Worked on low-count adaptive sampling.
        - title: Summer Intern
          company: Pearl Abyss
          company_url: ''
          company_logo: pearlabyss
          location: Gwacheon, South Korea
          date_start: '2022-06-01'
          date_end: '2022-08-01'
          description: Worked on building a [real-time path tracer](https://github.com/juhyeonkim95/DXRPathTracer).
        - title: Undergraduate Intern
          company: Kakao Mobility
          company_url: ''
          company_logo: kakaomobility
          location: Pangyo, South Korea
          date_start: '2018-12-01'
          date_end: '2019-03-01'
          description: Worked on [taxi dispatch strategy using RL](projects/2021taxi).
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
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: cardgif
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: cardgif
---
