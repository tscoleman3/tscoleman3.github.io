---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Trusted Science Center
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **T**rusted **S**cience **C**enter, led by Tyler Steven Coleman at Southeastern Louisiana University, brings together students, collaborators, and communities to tackle complex ecological questions with transparency, rigor, and innovation. 
        Our mission is to advance quantitative, applied research that links ecosystems, people, and policy through a coupled human and natural systems lens. We integrate careful study design, strategic analytics, and clear communication to produce science that informs conservation, restoration, and management. 
        We are committed to mentorship and training future scientists to approach challenges with curiosity, creativity, and skill.
  
  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        folders: [publication]              # pull from content/publication/
        publication_type: "article-journal" # only journal articles
        exclude_featured: false
      offset: 0
      sort_by: date
      sort_ascending: false
    design:
      view: citation
      columns: '1'
      spacing:
        padding: ['8px', '0', '8px', '0']

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: manatee.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest News
      text: ""
      count: 2
      filters:
        folders: [post]   # pull from content/post/
      offset: 0
      sort_by: date
      sort_ascending: false
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---