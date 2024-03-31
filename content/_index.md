---
# Leave the homepage title empty to use the site title
title: ''
date: '2024-31-03'
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin
  - block: experience
    content:
      title: Experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      items:
        - title: PhD Student
          company: Scalable Trustworthy AI
          company_url: "https://scalabletrustworthyai.github.io"
          company_logo: 
          location: Tübingen, Germany
          date_start: '2024-03-01'
          date_end: ''
        - title: Research Software Engineer
          company: Tübingen AI Center
          company_url: 'https://tuebingen.ai'
          company_logo: 
          location: Tübingen, Germany
          date_start: '2022-08-01'
          date_end: '2024-02-29'
        - title: Research Assistant
          company: Deutsches Forschungszentrum für Künstliche Intelligenz (DFKI)
          company_url: 'https://www.dfki.de/web'
          location: Kaiserslautern, Germany
          date_start: '2022-02-01'
          date_end: '2022-06-30'
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---