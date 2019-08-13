+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 30000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
#height = ""
#height = "calc(100vh - 70px)"
height = "600px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Algorithms for Protein Conformational Sampling"
  content = "I have developed algorithms, inspired from the field of robot motion planning, to successfully model low-energy conformations of protein and protein-ligand systems in a scalable manner."
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "pmhc_pocket.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  #cta_label = "Get Academic"
  #cta_url = "https://sourcethemes.com/academic/"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  title = "Adaptive Sampling for Simulation of Proteins"
  content = "Sampling rare events with Molecular Dynamics can be accelerated with adaptive sampling methods, which use machine learning to automatically determine a bias that can speed up the exploration of the simulation. I have experience with the analysis of these methods, and I am currently applying them to study peptide binding with MHCs."
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "TICA_FEL.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Machine Learning on Structural Data"
  content = "I am currently developing a deep Convolutional Neural Network to predict binding affinity of peptide-MHC complexes based on structures produced from APE-Gen. In collaboration with Daniel Bao (University of Houston). Feature image credits: Aphex34 (Wikimedia Commons)"
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "cnn.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
