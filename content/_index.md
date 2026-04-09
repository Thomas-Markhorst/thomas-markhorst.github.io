---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-biography
    content:
      username: me
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      show_status: false
      spacing:
        padding: ['0', '0', '0', '0']
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: compact
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: me
  # - block: awards
  #   content:
  #     title: Awards
  #     username: me
  # - block: languages
  #   content:
  #     title: Languages
  #     username: me
---