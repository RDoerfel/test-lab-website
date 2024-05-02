---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: about 
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
    id: people
    content:
      title: Meet the Group
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Research Support
          - Colaborators
          - Alumni
      sort_by: Params.position
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: collection
    id: publications
    view: citation
    content:
      title: Publications 
      subtitle: ''
      text:
      filters:
        publication_types: ['article-journal'] 
  
---