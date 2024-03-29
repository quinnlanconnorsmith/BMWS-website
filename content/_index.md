---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Walleye Bright Spots 
      image:
        filename: gh_wae.png
        caption: G. Hansen
#      cta:
#        label: '**A link to something**'
#        url: https://quinnlan-connor-smith.netlify.app/
#      cta_alt:
#        label: Secondary link
#        url: https://quinnlan-connor-smith.netlify.app/
      
      text: |-
        **Welcome to the Bright Spots Website!**

        **Habitat loss, pollution, species introductions, and overfishing have impacted inland fisheries for decades. The impact of climate change threatens to compound these other factors. Our work focuses on walleye fisheries of inland lakes of the Upper Great Lakes region, which have been declining since the early 2000s. Rather than the usual focus on understanding walleye population declines, our research emphasizes ‘bright spots’ - fisheries success stories. We seek to understand the drivers associated with fisheries that perform far better than expectations (‘bright’ fisheries).**

    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
        
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Previous Projects
          tag: Previous Project
        - name: Current Projects
          tag: Current Project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
  - block: experience
    id: timeline
    content:
      title: Project Timelines
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Walleye Bright Spots 
          company: 
          company_url: 'https://www.sciencebase.gov/catalog/item/627c0f97d34e8d45aa6ee6b9'
          company_logo: sci-base
          location: Minnesota, Michigan, Wisconsin, USA
          date_start: '2021-11-01'
          date_end: ''
          description: 
#This goes up behind the description (the 2, not the whole thing)
#          |2-
#              A checklist of things:
#
#              * Habitat use
#              * Movement within systems 
        - title: Walleye Safe Operating Space
          company: 
          company_url: 'https://www.sciencebase.gov/catalog/item/573f4df1e4b04a3a6a24ae6b'
          company_logo: sci-base
          location: Wisconsin, USA
          date_start: '2016-05-04'
          date_end: '2022-09-30'
          description: 
        - title: Climate Change and Resilience of Sport Fisheries in Lakes 
          company: 
          company_url: 'https://www.sciencebase.gov/catalog/item/52b4603ee4b029a4958d603f'
          company_logo: sci-base
          location: Wisconsin, USA
          date_start: '2011-04-01'
          date_end: '2015-04-01'
          description: 
    design:
      columns: '2'
  - block: collection
    id: pubs
    content:
      title: Project Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 
  - block: features
    content:
      title: Institutions
      items:
        - name: University of Wisconsin - Madison
          description: 
          icon: 
          icon_pack: 
        - name: University of Wisconsin - Steven's Point
          description: 
          icon: 
          icon_pack: 
        - name: University of Minnesota - Twin Cities 
          description: 
          icon: 
          icon_pack: 
        - name: United States Geological Survey 
          description: 
          icon: 
          icon_pack:
        - name: Great Lakes Indian Fish & Wildlife Commission 
          description: 
          icon: 
          icon_pack:
        - name: Wisconsin Department of Natural Resources
          description: 
          icon: 
          icon_pack:     
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: about.avatar
    id: about
    content:
      username: chris
      text:
  - block: about.avatar
    id: about
    content:
      username: ben
      text:
  - block: about.avatar
    id: about
    content:
      username: holly
      text:
  - block: about.avatar
    id: about
    content:
      username: gretchen
      text:
  - block: about.avatar
    id: about
    content:
      username: jake
      text:
  - block: about.avatar
    id: about
    content:
      username: olaf
      text:
  - block: about.avatar
    id: about
    content:
      username: zach
      text:
  - block: about.avatar
    id: about
    content:
      username: aaron
      text:
  - block: about.avatar
    id: about
    content:
      username: greg
      text:
    design:
      rows: '0.5'
  
  
#  - block: accomplishments
#    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Updates 
#      subtitle: ''
#      text: ''
      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
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
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
      # Choose a layout view
#      view: compact
#      columns: '2'
  
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card

#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
#  - block: markdown
#    content:
#      title: Project Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="bmws" >}}
#    design:
#      columns: '1'
#      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: Feel free to contact me with any questions about the project!
      email: qcsmith2@wisc.edu
      address:
        street: Hasler Laboratory of Limnology - 680 Park St. 
        city: Madison
        region: WI
        postcode: '53706'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
