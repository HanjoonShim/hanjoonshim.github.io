---
title: My page
type: landing

sections:

  - block: collection
    id: projects
    content:
      title: |-
        Projects
      subtitle: '</br>'
      text: |-
        <div style="text-align: center;"> 
          <strong> Ongoing Research </strong> </br>
            <a href="/project/snuglite-iii/">SNUGLITE-III (2022-)</a></br>          
            </br>
          <strong> Completed Research </strong> </br>
            <a href="/project/snuglite-ii/">SNUGLITE-II (2019-2022)</a></br>
            <a href="/project/kardsat/">KARDSAT (2019-2020)</a></br>
            <a href="/project/snuglite-i/">SNUGLITE-I (2017-2019)</a></br>
        </div>
        </br>
        </br>
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    #   default_button_index: 0
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase  
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
---