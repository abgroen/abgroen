+++
# Slider widget.
widget            = "slider"     # See https://sourcethemes.com/academic/docs/page-builder/
headless          = true         # This file represents a page section.
active            = false        # Activate this widget? true/false
weight            = 1            # Order that this section will appear.
interval          = false        # Slide interval. Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
height            = ""           # Slide height (optional). E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.

[[item]]          # Slides. Duplicate an `[[item]]` block to add more slides.
  title           = "Hello"
  content         = "I am center aligned :smile:"
  align           = "center"     # Choose `center`, `left`, or `right`.
  overlay_color   = "#666"       # Overlay a color or image (optional). An HTML color value. 
  overlay_img     = "headers/bubbles-wide.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter  = 0.5  # Darken the image. Value in range 0-1.
  cta_label       = "Get Academic"    # Call to action button (optional).
  cta_url         = "https://sourcethemes.com/academic/"
  cta_icon_pack   = "fas"
  cta_icon        = "graduation-cap"

[[item]]
  title           = "Left"
  content         = "I am left aligned :smile:"
  align           = "left"
  overlay_color   = "#555"        # An HTML color value.
  overlay_img     = ""            # Image path relative to your `static/img/` folder.
  overlay_filter  = 0.5           # Darken the image. Value in range 0-1.

[[item]]
  title           = "Right"
  content         = "I am right aligned :smile:"
  align           = "right"
  overlay_color   = "#333"        # An HTML color value.
  overlay_img     = ""            # Image path relative to your `static/img/` folder.
  overlay_filter  = 0.5           # Darken the image. Value in range 0-1.
+++
