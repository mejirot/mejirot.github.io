---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: 趣味
      items:
        - name: Guitar
          description:
          icon: guitar
          icon_pack: fas
        - name: DTM
          description:
          icon: music
          icon_pack: fas
        - name: Vocal
          description:
          icon: microphone
          icon_pack: fas
        - name: Cooking
          description:
          icon: kitchen-set
          icon_pack: fas
        - name: Game
          description: "デジタル/アナログどちらも"
          icon: dice
          icon_pack: fas
  - block: markdown
    id : music
    content:
      title: 曲
      subtitle: ''
      text: |-
        {{<youtube 7L0UCH_wOSE>}}
        {{<youtube YxfOPLrz3QI>}}
        {{<youtube Lue8Y4oOgz8>}}
        {{<niconico sm11669430>}}
        {{<niconico sm23159618>}}
        {{<niconico sm15473985>}}
        {{<niconico sm20097140>}}
    design:
      columns: '1'
      sections:
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
---
