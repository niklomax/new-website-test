---
title: "Your Name – Academic Publications"
summary: "Researcher at Your Institution"
date: 2024-01-01
type: landing

sections:
  # --- COMMENTED OUT UNTIL PROFILE IS FIXED ---
  # - block: resume-biography-3
  #   content:
  #     username: me
  #     text: |
  #       I am a researcher...
  #   design:
  #     ...
  # --- END COMMENTED SECTION ---

  # 2. Publications Section (This will work now)
  - block: collection
    id: publications
    content:
      title: Publications
      text: "A list of my 70+ academic publications."
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 1
---
