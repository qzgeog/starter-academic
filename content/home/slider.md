---

# Slider widget.
widget: slider  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true  # This file represents a page section.
active: true    # Activate this widget? true/false
weight: 1       # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 4000

# Slide height (optional).
# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen. # calc(150%)
height: '700px; background-position:center; background-repeat: no-repeat; background-size: cover'

# Slides.
# Duplicate an "item:" block to add more slides.

item:
  - title: Coupled Human and Natural Systems
    content: 'land use change, forest conservation, labor migration, livelihoods...'
    align: center  # Choose `center`, `left`, or `right` alignment.
    
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#ECF0F1'  # An HTML color value. '#666'
    overlay_img: slider1_village.jpg  # Image path relative to your `static/media/` folder. headers/bubbles-wide.jpg
    overlay_filter: 0  # Darken the image. Value in range 0-1.
    
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Detailed Info
    cta_url: 'https://www.qzgeog.com/project/proj1318-cnh-cs/'
    cta_icon_pack: fas
    cta_icon: dove

  - title: AI for Earth System Dynamics
    content: 'Agricultural practices, cropland dynamics, terrestrial surface ...'
    align: center
    
    overlay_color: '#7B7D7D'  # '#666'
    overlay_img: slider2_maize.jpg
    overlay_filter: 0
    
    cta_label: Detailed Info
    cta_url: 'https://www.qzgeog.com/project/proj2022-ai4earth/'
    cta_icon_pack: fab
    cta_icon: envira

  - title: Agent-Based Modeling
    content: 'Complex interactions among social agents and ecological entities...'
    align: center
    
    overlay_color: '#ECF0F1'  # '#333'
    overlay_img: slider3_computer.jpg
    overlay_filter: 0
    
    cta_label: Detailed Info
    cta_url: 'https://www.qzgeog.com/abm/'
    cta_icon_pack: fas
    cta_icon: house-user

---


