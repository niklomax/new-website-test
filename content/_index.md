---
title: "Your Name – Academic Publications"
summary: "Researcher at Your Institution"
date: 2024-01-01
type: landing

sections:
  # 1. About Me Section
  - block: resume-biography-3
    content:
      # CHANGE THIS to match your folder name (e.g., 'me', 'admin', or your name)
      username: me
      text: |
        I am a researcher at **Your Institution**. My work focuses on **[Your Field]**. 
        I have published **70+ papers** in top-tier venues.
        
        Please reach out to collaborate!
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 2. Publications Section (Shows ALL publications)
  - block: collection
    id: publications
    content:
      title: Publications
      text: "A list of my 70+ academic publications."
      filters:
        folders:
          - publications
        # Remove 'featured_only: true' to show ALL papers, not just featured ones
    design:
      view: citation # Clean list view
      columns: 1
---
