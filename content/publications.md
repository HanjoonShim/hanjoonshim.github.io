---
# Leave the homepage title empty to use the site title
title: Publications
date: 2024-09-29
type: landing

#---------------------------------------------------------------------------------

sections:

#---------------------------------------------------------------------------------

  - block: markdown
    content:
      title: "Publications"
      text: |-
        </br>

        _Last Update: 2024-11-13_

        | Category                           | First Author | Co-author |  Total |
        |------------------------------------|:------------:|:---------:|:------:|
        | [Journal (SCIE/SCOPUS)](#id-ij)    |      3       |     2     |  **5** |        
        | [International Conference](#id-ic) |      4       |     6     | **10** |
        | [Domestic Journal](#id-dj)         |      3       |     2     |  **5** |
        | [Domestic Conference](#id-dc)      |     15       |    23     | **38** |
        | [Thesis](#id-thesis)               |
        | **Overall Total**                  |   **25**     |  **33**   | **58** |
      
#---------------------------------------------------------------------------------

  - block: collection
    id: id-ij
    content:
      title: Journal Papers (SCIE/SCOPUS)
      text: |-
        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications**](/publication).
        {{% /callout %}}
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation   
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-ic
    content:
      title: Conference Papers
      text: |-
        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications**](/publication).
        {{% /callout %}}
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'paper-conference'
    design:
      view: citation
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-dj
    content:
      title: Domestic Journal Papers (Korean)
      text: |-
        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications**](/publication).
        {{% /callout %}}
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'domestic-journal'
    design:
      view: citation
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-dc
    content:
      title: Domestic Conference Papers (Korean)
      text: |-
        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications**](/publication).
        {{% /callout %}}
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'domestic-conference'
    design:
      view: citation
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-thesis
    content:
      title: Thesis
      text: |-
        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications**](/publication).
        {{% /callout %}}
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'thesis'
    design:
      view: citation
      columns: '2'


---