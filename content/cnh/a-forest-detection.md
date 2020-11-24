+++
widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 5  # Order that this section will appear.

title = "Forest detection using remote sensing"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

##Forest detection using remote sensing

We employ multitemporal remote sensing analysis to infer the net effect of the CCFP and the PWF forest policies in Tiantangzhai township, Anhui, China. Our results indicate that between 2002 and 2013, substantial land cover changes took place following the implementation of these two programs compared with the decade before. Overall, natural forests increased by 14% from 2002 to 2013, while the area of cropland declined by 9%. This increase in total forest cover likewise resulted in a decline in landscape-wide fragmentation as natural forests received protection and CCFP forest stands were established. CCFP forest stands located in proximity to managing households and occurring in favorable topographic positions experienced accelerated canopy structural development.

{{< figure src="tcaptransform.png" title="The canopy closure line (CCL) is defined based on canopy closure points in the brightness–greenness (B–G) space of the Tasseled Cap transformation." >}}

In addition to findings concerning the change in the quantity of forest cover extent based on Landsat time series change detection analysis over the entire 20-year period and landscape structural analysis comparing the effect with and without the inclusion of CCFP forests by 2013, we establish three new remotely sensed forest development indexes to assess the quality of those new forests. Specifically, we developed the CCI, the MI, and the SSI to quantify remotely sensed forest canopy development characteristics based on pixel proximity to the CCL in the B–G space of the Tasseled Cap transformation. Results indicate that temporal trends in CI and SSI values over the entire study area exhibit a decline from 1992 to 2002, followed by an increase with the advent of the CCFP and PWF. These findings indicate net forest canopy development in the study area characterized by an increase in canopy density in younger forests as well as increasing canopy complexity in mature forests. Taken together, these results demonstrate the utility of the CI, MI, and SSI forest development indexes for tracking landscape-scale successional processes and confirm our hypothesis that the study area exhibited signs of increasing quantity (areal extent) and quality (canopy development) of forest cover following the implementation of the CCFP and PWF forest policies.
