+++
# A podcasts section. This section displays recent posts from `content/podcast/`.
widget                = "pages"           # See https://sourcethemes.com/academic/docs/page-builder/
headless              = true              # This file represents a page section.
active                = true              # Activate this widget? true/false
weight                = 40                # Order that this section will appear.

title = "Podcast: live.a.little"
subtitle              = """The podcast is called live.a.little and here you'll find the latest episodes. I have two series: meaning and science.

Find all podcasts at <strong>[this page](/presumably/)</strong> as well as a description of the different series."""

[content]
  page_type           = "podcast"         # Page type to display. E.g. post, talk, or publication.
  count               = 0                 # Choose how much pages you would like to display (0 = all pages)
  offset              = 0                 # Choose how many pages you would like to offset by
  order               = "desc"            # Page order. Descending (desc) or ascending (asc) date.

  [content.filters]                       # Filter posts by a taxonomy term.
    tag               = ""
    category          = ""
    publication_type  = ""
    author            = ""
    exclude_featured  = false
  
[design]
  view                = 2                 # layout types: 1 = List, 2 = Compact, 3 = Card, 4 = Citation (publication only)
  
[design.background]
  # color             = "navy"            # Background color.
  # gradient_start    = "DeepSkyBlue"     # Background gradient.
  # gradient_end      = "SkyBlue"         # Background gradient.
  # image             = "background.jpg"  # Name of image in `static/img/`.
  # image_darken      = 0.6               # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # text_color_light  = true              # Text color (true=light or false=dark).
  
[advanced]
 css_style            = ""                # Custom CSS. 
 css_class            = ""                # CSS class.
+++


