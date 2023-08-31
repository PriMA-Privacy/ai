---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:    
  - block: hero
    content:
      title: | 
        **PriMA**
      image:
        filename: iconsmall.png
        size: 100%
      text: |
        Privacy Management Application for Individuals

   
  - block: slider
    content:
      slides:
      - title: Our tool will protect your data!
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: background.png
            filters:
              brightness: 0.9
          position: right
          color: '#666'
      - title: ️
        content: 
        align: left
        background:
          image:
            filename: PriMaIdea2.png
            filters:
              brightness: 0.9
          position: center
          color: '#555'
      - title: 
        design: 
        align: right
        background:
          image:
            filename: PriMAIdea.png
            flip: false
            filters:
              brightness: 0.8
          position: center
          color: '#333'
        link:
          icon: 
          icon_pack: fas
          text: Request a Demo
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000       
  - block: markdown
    design:
    content:
      title:
      subtitle: ''
      text:
    design:
      background:
        video: 
          size: 50%
          filename: output.mp4
          filters:
            brightness: 1
             size:10%
          parallax: false
          position: center
          size: 50%
          text_color_light: true
      spacing:
        padding: ['100px', '0px', '0px', '0px']
      css_class: fullscreen        
  - block: collection
    content:
      title: Latest News & Blog Posts
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet our team →" %}}
    design:
      columns: '1'
---
