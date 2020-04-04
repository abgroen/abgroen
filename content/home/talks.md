+++
# A Recent and Upcoming Talks section. This section displays talks from `content/talk/`.
widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 70  # Order that this section will appear.
title = "Recent & Upcoming Talks"
subtitle = ""

[content]
  page_type     = "talk"      # Page type to display. E.g. post, talk, or publication.
  count         = 5           # Choose how much pages you would like to display (0 = all pages)
  offset        = 0           # Choose how many pages you would like to offset by
  order         = "desc"      # Page order. Descending (desc) or ascending (asc) date.

  [content.filters]   # Filter posts by a taxonomy term.
    tag               = ""
    category          = ""
    publication_type  = ""
    author            = ""
    exclude_featured  = false
    exclude_past      = false
    exclude_future    = false
    
[design]
  view                = 2                 # layout types: 1 = List, 2 = Compact, 3 = Card, 4 = Citation (publication only)
  
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
