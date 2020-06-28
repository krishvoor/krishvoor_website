+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Proofpoint on OpenShift Container Platform"
  content = "Running MongoDB and Node.js on Red Hat OpenShift Container Platform"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "node_mongo.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "IBM Developer"
  cta_url = "https://developer.ibm.com/tutorials/mongodb-nodejs-on-openshift/"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

[[item]]
  title = "Advantages of Running Openshift on IBM Power Systems"
  content = "Pack-em or Stack-em: Advantages of Running OpenShift on Power"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#111"  # An HTML color value.
  overlay_img = "openpower.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.6 # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Pack-em or Stack-em"
  cta_url = "https://youtu.be/4fJkiUR1JQo"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

+++
