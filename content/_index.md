---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  #-------------------------------------------------------------
  # Section1: Image (Hanjoon Shim)
  #-------------------------------------------------------------
  - block: cta-card
    id: papers

    content:
      title: |-
        <strong>HANJOON SHIM</strong>
      text: |- 
        {{ $html := "<em>emphasized</em>" }}
        <font>
          <strong><i><font size=5><font color="white">
          Ph.D in Aerospace Engineering
          </i></strong>
        </font>
        </br></br>      

      button:
        text:
          Get Started          
        url: aboutme/

    design:
      card:
        # Card background color (CSS class)
        css_class: "text"

      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['200px', '0', '200px', '0']
       
      # css_class: dark
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: index_background.jpg
          filters:
            brightness: 0.7
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.  
          size: cover
          position: center
          parallax: false

---
