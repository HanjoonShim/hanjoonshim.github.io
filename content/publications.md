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
      title: |-
        <div style="text-align: center;">
          </br></br></br> ⭐ International Journal Paper </br>(SCIE / SCOPUS)
        </div>
      text: ""
      filters:
        folders:
          - pub-journal
        exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '20px', '0', '20px']

  #-------------------------------------------------------------
  # International Conference Paper
  #-------------------------------------------------------------
  - block: collection
    content:
      title: |-
        <div style="text-align: center;">
          </br></br></br> ⭐ International Conference Paper
        </div>
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
        padding: ['0', '20px', '0', '20px']

  #-------------------------------------------------------------
  # Domestic Journal Paper
  #-------------------------------------------------------------
  - block: collection
    content:
      title: |-
        <div style="text-align: center;">
          </br></br></br>Domestic Journal Paper </br>(in Korean)
        </div>
      text: ""
      filters:
        folders:
          - pub-djournal
        exclude_featured: false
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '20px', '0', '20px']

  #-------------------------------------------------------------
  # Domestic Conference Paper
  #-------------------------------------------------------------
  - block: markdown
    content:
      title: |-
        <div style="text-align: center;">
          </br></br></br> Domestic Conference Paper </br>(in Korean)
        </div>
      text: ""
    design:
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '20px', '0', '20px']
     
---
