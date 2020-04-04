+++
# A Projects section.
widget                = "portfolio"       # See https://sourcethemes.com/academic/docs/page-builder/
headless              = true              # This file represents a page section.
active                = true              # Activate this widget? true/false
weight                = 45                # Order that this section will appear.
title                 = "PROJECTS"
subtitle              = "Gallery of different projects both personal and professional."

[content]
  page_type           = "project"         # Page type to display. E.g. project.
  filter_default      = 0                 # Default filter (e.g. 0 corresponds to the first `[[filter_button]]`).
  
  [[content.filter_button]]
    name              = "All"             # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
    tag               = "*"               # To show all items, set `tag` to *.
    
  [[content.filter_button]]
  name                = "Professional"
  tag                 = "Professional"    # To filter by a specific tag, set `tag` to an existing tag name.
  
  [[content.filter_button]]
  name                = "Personal"
  tag                 = "Personal"

[design]
  columns             = "2"               # Choose how many columns the section has. Valid values: 1 or 2.
  view                = 3                 # layout types: 1 = List, 2 = Compact, 3 = Card, 5 = Showcase
  flip_alt_rows       = false             # For Showcase view, flip alternate rows?

[design.background]
  # color             = "navy"            # Background color. Any HTML color name or Hex value is valid.
  # gradient_start    = "DeepSkyBlue"     # Background gradient.
  # gradient_end      = "SkyBlue"         # Background gradient.
  # image             = "background.jpg"  # Name of image in `static/img/`.
  # image_darken      = 0.6               # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # text_color_light  = true              # Text color (true=light or false=dark).
  
[advanced]
 css_style            = ""                # Custom CSS. 
 css_class            = ""                # CSS class.
+++
