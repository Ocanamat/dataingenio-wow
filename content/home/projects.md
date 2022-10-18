---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: projects
subtitle: ready to deploy & enjoy

content:
  # Page type to display. E.g. project.
  page_type: project

  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
  

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   Citation (4) For classic APA or MLA styled publication lists. Optionally, edit the value of citation_style in params.yaml to APA or MLA
  #   5 = Showcase
<<<<<<< HEAD
  #   masonry
  view: masonry
=======
  view: showcase
>>>>>>> 1d5363bdae4dd4242e2bb81c3a3a3dec532c52fe

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
  spacing: 
    padding: ["20px", "0", "20px", "0"]
---