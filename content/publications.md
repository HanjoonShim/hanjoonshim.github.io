---
title: 'Publications'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:

  #-------------------------------------------------------------
  # International Journal Paper (SCIE/SCOPUS)
  #-------------------------------------------------------------
  - block: collection
    content:
      title: International Journal Paper (SCIE/SCOPUS)
      text: ""
      filters:
        folders:
          - pub-journal
        exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '5px', '0', '5px']

  #-------------------------------------------------------------
  # International Conference Paper
  #-------------------------------------------------------------
  - block: collection
    content:
      title: International Conference Paper
      text: ""
      filters:
        folders:
          - pub-conference
        exclude_featured: false
    design:
      view: citation
      # Reduce spacing
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '5px', '0', '5px']

  #-------------------------------------------------------------
  # Domestic Journal Paper
  #-------------------------------------------------------------
  - block: collection
    content:
      title: Domestic Journal Paper
      text: ""
      # filters:
      #   folders:
      #     - pub-conference
      #   exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '5px', '0', '5px']

  #-------------------------------------------------------------
  # Domestic Conference Paper
  #-------------------------------------------------------------
  - block: collection
    content:
      title: Domestic Conference Paper
      text: ""
      # filters:
      #   folders:
      #     - pub-conference
      #   exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '5px', '0', '5px']
     

---
