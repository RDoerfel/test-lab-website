---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: collections
    content:
      title: |
        Imaging Biomarkers of Biological Aging
        Research Group
      image:
        filename: 
      text: |
        <br>
        
        At the **Imaging Biomarkers of Biological Aging Group** we aim to develop and validate biomarkers of biological aging using neuroimaging, and machine learning. The overarging goal is to develop frameworks for clinical trials assessing the effect of putative geroprotective compounds.  this includes the development of protocols for imaging studies and the development and validation of potential biomarkers.
  
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.position
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: publication
    content:
      title: Publications 
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: 
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
---