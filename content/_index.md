---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: <strong>Hanjoon Shim</strong>
        content: 
          Specialist in GPS Applications for LEO and CubeSats
          </br>
          </br>
          
        align: center
        background:
          image:
            filename: welcome1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          # icon: graduation-cap
          # icon_pack: fas
          text: <strong>Biography</strong>
          url: aboutme/

      - title: '</br> </br> </br> </br> </br> </br> </br> </br> </br>'
        content: |-
          **Delivering professional,** </br>
          **high-impact presentations.**
          
        align: right
        background:
          image:
            filename: welcome2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: '</br> </br> </br> </br> </br> </br> </br> </br> </br>'
        content: |-
          **Passion** </br>
          **for Aerospace Engineering**
          
        align: left
        background:
          image:
            filename: welcome3.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 10000

  - block: collection
    content:
      title: Latest News
      text: ""
      count: 5
      filters:
        folders: 
          - post
        featured_only: true
        order: desc  # 최신 포스트를 우선 표시
    design:
      view: compact
      columns: '2'
    
---
