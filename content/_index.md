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
        
        The **Trusted Science Center** is led by Tyler Steven Coleman at Southeastern Louisiana University. We bring together students, collaborators, and communities to tackle complex ecological questions with transparency, rigor, and innovation. Our *mission* is to advance quantitative and applied research that links ecosystems, people, and policy, treating systems as coupled human and natural systems. By integrating careful study design, strategic analytics, and diverse perspectives, we aim to deliver science that is not only academically sound, but also actionable for conservation, restoration, and management. We are committed to mentorship and capacity building, preparing the next generation of scientists to approach problems with curiosity, creativity, and skill.
  
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