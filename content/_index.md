---
# Leave the homepage title empty to use the site title
title: 
date: 2025-07-16
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: features
  #   content:
  #     title: My scholarly output
  #     subtitle: Overview of my publications
  #     text: This section provides a summary of my research contributions.
  #     items:
  #       - name: Journal Papers
  #         description: 14
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Conference Papers
  #         description: 12
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Research projects
  #         description: 6
  #         icon: camera-retro
  #         icon_pack: fas
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
      title: Recent publications
      subtitle: '[See all publications](./publication/).'
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: |-
        If you have any questions, please feel free to contact me via email or visit my office during office hours.
        You can also find me on GitHub.
      # Contact (add or remove contact options as necessary)
      email: jlgarrido@ubu.es
      address:
        street: Campus Río Vena. Avda. Cantabria s/n 09006
        city: Burgos
        region: Castilla y León
        postcode: '09006'
        country: Spain
        country_code: ES
      directions: Enter Building A1 and take the stairs to Office 3108 on Floor 3, through classroom 36
      office_hours:
        - '1st Semester: Worksdays 08:30 to 14:00'
        - '2nd Semester: Only by appointment'
      contact_links:
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/jlgarridol'
      autolink: true
    design:
      columns: '2'
---
