+++
# A section created with the Blank widget.
widget = "chart"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 22  # Order that this section will appear.

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Chart3"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
   columns = "2"
  format = "2" 
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  # padding = ["0px", "0px", "0px", "0px"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
 [chart]
 
 json="../json/testData5.json"
 
id = "myChart3"
 chart_label = "Source Rank"
 backgroundColor = "rgba(255,207,47,0.6)"
 borderColor = "rgba(255,207,47)"
 borderWidth = "2"
 yGridLines = "false"
 xGridLines = "false"
 type = ""
 data = "e:1,f:2,g:3"

+++
test3
