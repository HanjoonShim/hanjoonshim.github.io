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
    id: pub-ij
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
    id: pub-ic
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
    id: pub-dj
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
    id: pub-dc
    content:
      title: |-
        <div style="text-align: center;">
          </br></br></br> Domestic Conference Paper </br>(in Korean)
        </div>
      text: |-
        </br>
        </br>
        <div style="font-size: 15px">        
        ~34 papers have been presented. </br>
        (✅15 as the first author presentations, 19 as co-authors) </br>

        - Hanjoon Shim and Chandgon Kee. (2021). 
          <u>HILS Verification of SNUGLITE-II Cube Satellite Attitude Control System Equipped with Reaction Wheel and Magnetorquer.</u> 
          <i>Proceedings of the 2021 Korean Society for Aeronautical & Space Sciences Fall Conference, </i>
          Jeju, Korea, Nov 2021, pp. 321-322. </br>
          <span style="background-color: red; font-weight: bold; color: white;">&nbsp;Best Paper Presentation&nbsp;</span> 
        </div>

        </br>

        <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
          <title>Hover Button</title>
        </head>
        <body class="flex items-center justify-center min-h-screen">
          <div class="flex flex-col items-center">
            <a href="../pub-dconference/" class="inline-block text-center">
              <button class="border-2 border-black bg-gray-500 text-white py-2 px-4 hover:bg-gray-700 transition-colors duration-300 rounded-lg">
                <div style="font-size: 15px; font-weight: bold">  
                  See more
                </div>
              </button>
            </a>
          </div>
        </body>

    design:
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '20px', '0', '20px']

---
