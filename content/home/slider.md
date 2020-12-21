---
active: true
weight: 10
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 2000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 500px

item:
  - title: ''
    content: ''
    # Choose `center`, `left`, or `right` alignment.
    align: center
    size: cover
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: 1.png  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    # cta_label: Download my app
    # cta_url: 'https://example.org'
    # cta_icon_pack: fas
    # cta_icon: graduation-cap
  - overlay_img: '2.png'
    overlay_filter: 0.5
  - overlay_img: '3.png'
    overlay_filter: 0.5  
---