---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: slider
  #   content:
  #     slides:
  #     - title: 👋 Welcome to the group
  #       content: Take a look at what we're working on...
  #       align: center
  #       background:
  #         image:
  #           filename: coders.jpg
  #           filters:
  #             brightness: 0.9
  #         position: right
  #         color: '#666'
  #     - title: 👋 Welcome to the group
  #       content: Take a look at what we're working on...
  #       align: center
  #       background:
  #         image:
  #           filename: contact.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #     - title: 👋 Welcome to the group
  #       content: Take a look at what we're working on...
  #       align: center
  #       background:
  #         image:
  #           filename: welcome.jpg
  #           filters:
  #             brightness: 0.5
  #         position: center
  #         color: '#333'
  #       # link:
  #       #   icon: graduation-cap
  #       #   icon_pack: fas
  #       #   text: Join Us
  #       #   url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000


  - block: hero
    content:
      title: |
        <p style="font-size: 0.8em;">  
        IHCIL@OUC
        </p>   
      image:
        filename: ihcil.jpg
      text: |
        <p style="font-size: 0.77em;">  <br>
        Based on the interdisciplinary frontier of physical oceanography, meteorology, and ocean engineering, our laboratory focuses on the air-sea interface as the core research subject. We are committed to unraveling the fundamental dynamic processes of energy and material exchange within this critical boundary layer, deepening the understanding of the generation mechanisms and evolution patterns of key ocean-meteorological elements such as air-sea fluxes and wind wave generation and development. Furthermore, we aim to advance the theoretical methods for their accurate forecasting. The ultimate scientific vision of the laboratory is to establish a complete closed-loop research framework that spans from understanding fundamental mechanisms to achieving intelligent forecasting. This endeavor provides robust scientific support and technical solutions for addressing extreme weather and climate events, ensuring marine safety, and advancing Earth system science research.
        </p>   
  # - block: slider
  #   content:
  #     slides:
  #       - title: Slide One
  #         image:
  #           filename: welcome.jpg

  #       - title: Slide two
  #         image:
  #           filename: coders.jpg    

  # - block: collection
  #   content:
  #     title: Research
  #     subtitle:
  #     text:
  #     count: 4
  #     filters:
  #       author: ""
  #       category: ""
  #       exclude_featured: false
  #       publication_type: ""
  #       tag: ""
  #     offset: 0
  #     order: desc
  #     page_type: research
  #   design:
  #     view: showcase
  #     columns: "1"

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: list
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'
#   - block: markdown
#     id: papers
#     content:
#       title: Section 1
#       subtitle: A subtitle
#       text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1' # Choose how many columns the section has. Valid values: '1' or '2'.

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-4">
              <h5 class="text-muted" style="font-size: 0.95rem;">LINK</h5>
              <ul class="list-unstyled" style="font-size: 0.85rem;">
                <li><a href="https://www.ai-ouc.cn/" target="_blank">Institute of Artificial Intelligence</a></li>
                <li><a href="https://it.ouc.edu.cn/" target="_blank">Faculty of Information Science and Engineering</a></li>
              </ul>
            </div>
            <div class="col-md-4 text-center">
              <div style="margin-top: 1rem;">
                <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=QJLp3xQ-w7019B5p3jHJSpwxfsmjIoKGPvyGMIRtuXU&cl=ffffff&w=a"></script>
              </div>
            </div>
            <div class="col-md-4">
              <!-- 右侧部分为空 -->
            </div>
          </div>
        </div>
---
