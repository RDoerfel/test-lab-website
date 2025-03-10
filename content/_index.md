---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: about 
    content:
      title: |
        # Evaluating geroprotective interventions using *in vivo* medical imaging 
      image:
        filename: lnn-logo.png
      text: |
        <span style="font-size:0.9em;">  We aim to develop biomarkers and new treatments for neurodegenerative diseases. We do this by applying medical imaging techniques, such as MRI, PET and CT, to pre-clinical models of neurodegeneration, as well as human patients. Currently, we are running an academically sponsored phase IIa trial in early Alzheimer's disease, where we assess the effect of the drug sirolimus (a.k.a. rapamycin) on neurodegeneration, brain metabolism and aging processes. </span> <br>
        
        <span style="font-size:0.9em;">Our work also involves developing and validating biomarkers of aging that can be used as endpoints in clinical trials of geroprotective compounds. To this end, we apply machine learning models to large batches of multi-modal imaging data to estimate the biological age of different organ-systems in the human body.</span>

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
        tags: publication
  
---