---
title: About Me
date: 2024-09-29

type: landing

#---------------------------------------------------------------------------------

sections:

#---------------------------------------------------------------------------------

  - block: about.biography
    id: about
    content:
      title: |-
        **Biography**
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          # filename: welcome.jpg
          # filters:
          #   brightness: 1.0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.  
          size: cover
          position: center
          parallax: false

#---------------------------------------------------------------------------------

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher
          company: GNSS Laboratory, Seoul National University
          company_url: 'https://gnss.snu.ac.kr/'
          company_logo: 'snu'
          location: Seoul
          date_start: '2024-09-01'
          date_end: ''
          description: |2-
              Related Projects:
              * [SNUGLITE-III CubeSat (2022-)](/project/snuglite-iii/)

        - title: Graduate Student Full-time Researcher
          company: GNSS Laboratory, Seoul National University
          company_url: 'https://gnss.snu.ac.kr/'
          company_logo: snu
          location: Seoul
          date_start: '2017-03-01'
          date_end: '2024-08-31'
          description: |-
              MSc, PhD Advisor: Changdon Kee </br>
              Related Projects:
              * [SNUGLITE-III CubeSat (2022-)](/project/snuglite-iii/)
              * [SNUGLITE-II CubeSat (2019-2022)](/project/snuglite-ii/)
              * [KARDSAT CubeSat (2019-2020)](/project/kardsat/)
              * [SNUGLITE-I CubeSat (2017-2019)](/project/snuglite-i/)

        - title: Undergraduate Internship
          company: Smart Autonomous System Laboratory, Handong Global University
          company_url: 'https://sites.google.com/handong.edu/idcl'
          company_logo: hgu
          location: Pohang
          date_start: '2015-08-01'
          date_end: '2016-06-01'
          description: |-
              BSc Advisor: Wonsang Ra

        - title: Sergent, Mandatory Military Service
          company: Republic of Korea Army
          company_url: 'https://www.army.mil.kr/'
          company_logo: roka
          location: Yang-gu
          date_start: '2011-01-11'
          date_end: '2012-10-14'          

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

#---------------------------------------------------------------------------------

  - block: accomplishments
    content:
      title: Awards and Honors
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      items:
        - title: Best Paper Seleted – 2022 KSAS Fall Conference
          certificate_url: '/awards/2023_ksas.jpg' #static /awards
          date_end: ''
          date_start: '2023-10-06'
          description: ''
          icon: ksas
          organization: The Korean Society for Aeronautical and Space Sciences (KSAS), Korea
          organization_url: https://ksas.or.kr/
          url: 'https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11531094&language=ko_KR&hasTopBanner=true'

        - title: Best Presentation Award – ION GNSS+ 2023
          certificate_url: '/awards/2023_ion.jpg' #static /awards
          date_end: ''
          date_start: '2023-09-01'
          description: ''
          icon: ion
          organization: The Institute of Navigation (ION), USA
          organization_url: https://www.ion.org/

        - title: Minister Award - 2019 Korea CubeSat Contest
          certificate_url: '/awards/2022_kor_cubesat.jpg' #static /awards
          date_end: ''
          date_start: '2022-11-01'
          description: 
          icon: korgov
          organization: Minister of Science and ICT, Republic of Korea
          organization_url: https://www.msit.go.kr/

        - title: Certificate - 2022 Korea CubeSat Contest Finalist
          certificate_url: '/awards/2022_kari_cubesat.jpg'
          date_end: ''
          date_start: '2022-11-01'
          description: 
          icon: kari
          organization: Korea Aerospace Research Institute (KARI), Korea
          organization_url: https://www.kari.re.kr/

        - title: Best Paper Presentation Award – 2021 KSAS Fall Conference
          certificate_url: '/awards/2021_ksas.jpg'
          date_end: ''
          date_start: '2022-04-01'
          description: 
          icon: ksas
          organization: The Korean Society for Aeronautical and Space Sciences (KSAS), Korea
          organization_url: https://ksas.or.kr/

        - title: Certificate - 2019 Korea CubeSat Contest Finalist
          certificate_url: /awards/2020_kari_cubesat.jpg
          date_end: ''
          date_start: '2020-02-01'
          description: 
          icon: kari
          organization: Korea Aerospace Research Institute (KARI), Korea
          organization_url: https://www.kari.re.kr/

        - title: Director Award - 2015 Korea CubeSat Contest
          certificate_url: '/awards/2015_kari_cubesat.jpg'
          date_end: ''
          date_start: '2019-04-01'
          description: 
          icon: kari
          organization: Korea Aerospace Research Institute (KARI), Korea
          organization_url: https://www.kari.re.kr/

        - title: Aviation Specialized University Excellent Talent Certificate
          certificate_url: '/awards/2019_kor_certificate.jpg'
          date_end: ''
          date_start: '2019-03-01'
          description: 
          icon: korgov
          organization: Minister of Ministry of Land, Infrastructure and Transport, Republic of Korea
          organization_url: https://www.molit.go.kr

        - title: Director Award - Capstone Contest
          certificate_url: '/awards/2015_hgu_capstone.jpg'
          date_end: ''
          date_start: '2015-12-01'
          description: 
          icon: hgu
          organization: School of Mechanical and Control Engineering, Handong Global University, Korea
          organization_url: https://www.handong.edu/


    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

#---------------------------------------------------------------------------------
# PUBLICATIONS
#---------------------------------------------------------------------------------

  - block: collection
    content:
      title: Featured Journal Papers
      text: ""
      count: 3
      filters:
        folders:
          - publication
        featured_only: true 
    design:
      view: compact
      columns: '2'

#---------------------------------------------------------------------------------
# Contect
#---------------------------------------------------------------------------------

  - block: contact
    id: id-contact
    content:
      title: Contact
      text: |-
        
      email: hanjos@snu.ac.kr
      # phone: 888 888 88 88
      address:
        street: 1, Gwanak-ro
        city: Gwanak-gu
        region: Seoul
        postcode: '08826'
        country: Korea
        country_code: KOR
      coordinates:
        latitude: '37.45085'
        longitude: '126.95178'
      directions: |-
        Enter Building 312 and take the stairs to Room 501 on Floor 5 
        </br>
        서울시 관악구 관악로 1 서울대학교 정밀기계설계공동연구소 312동 501호

      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'

---