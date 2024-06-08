---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

# design:
#   # Default section spacing
#   spacing: "10rem"

sections:

  #-------------------------------------------------------------
  # Section1: Image (Hanjoon Shim)
  #-------------------------------------------------------------
  - block: cta-card
    content:
      title: |-
        
        [<span style="font-size: 55px; font-weight: bold;">HANJOON SHIM</span>](aboutme/)        

      text: |-
        </br>
        <i>Ph.D in Aerospace Engineering</i>
        </br></br>   

    design:
      card:
        # Card background color (CSS class)
        css_class: "text"

      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['160px', '0', '200px', '0']
       
      # css_class: dark
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: index_background.jpg
          filters:
            brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.  
          size: cover
          position: center
          parallax: false

  # - block: collection
    # id: news
    # content:
    #   title: |-
    #     </br></br></br>
    #     Recent News
    #   subtitle: ''
    #   text: ''
    #   # Page type to display. E.g. post, talk, publication...
    #   page_type: post
    #   # Choose how many pages you would like to display (0 = all pages)
    #   count: 3
    #   # Filter on criteria
    #   filters:
    #     author: ""
    #     category: ""
    #     tag: ""
    #     exclude_featured: false
    #     exclude_future: false
    #     exclude_past: false
    #     publication_type: ""
    #   # Choose how many pages you would like to offset by
    #   offset: 0
    #   # Page order: descending (desc) or ascending (asc) date.
    #   order: desc
    # design:
    #   # Choose a layout view
    #   view: date-title-summary
    #   # Reduce spacing
    #   spacing:
    #     padding: [0, 0, 0, 0]

---
