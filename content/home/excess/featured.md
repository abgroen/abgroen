+++
widget                  = "featured"                  # See https://sourcethemes.com/academic/docs/page-builder/
headless                = true                        # This file represents a page section.
active                  = false                       # Activate this widget? true/false
weight                  = 80                          # Order that this section will appear.
title                   = "Featured Publications"     # Displays  `content/publication/` with `featured = true`.
subtitle                = ""

[content]
  page_type             = "publication"               # Page type to display. E.g. post, talk, or publication.  
  count                 = 0                           # Choose how much pages you would like to display (0 = all pages)
  order                 = "desc"                      # Page order. Descending (desc) or ascending (asc) date.
  link_to_archive       = false                       # Show a "See all pages" link underneath the featured content?
  [content.filters]                                   # Filter posts by a taxonomy term.
    tag                 = ""
    category            = ""
    publication_type    = ""
    author              = ""
  
[design]
  view                  = 3                           # layout types: 1 = List, 2 = Compact, 3 = Card, 4 = Citation (publication only)
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # color                = "navy"                      # Background color
  # gradient_start       = "DeepSkyBlue"               # Background gradient.
  # gradient_end         = "SkyBlue"                   # Background gradient.
  # image                = "background.jpg"            # Name of image in `static/img/`.
  # image_darken         = 0.6                         # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # text_color_light     = true                        # Text color (true=light or false=dark).
  
[advanced]
 css_style                = ""                         # Custom CSS.
 css_class                = ""                         # CSS class.
+++
