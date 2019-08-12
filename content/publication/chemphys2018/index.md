---
title: "Quantitative Comparison of Adaptive Sampling Methods for Protein Dynamics"
authors:
- Eugen Hruska
- admin
- Feliks Nuske
- Lydia Kavraki
- Cecilia Clementi
date: "2018-12-01T00:00:00Z"
doi: "10.1063/1.5053582"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The Journal of Chemical Physics 149*(24)"
publication_short: ""

abstract: Adaptive sampling methods, often used in combination with Markov state models, are
      becoming increasingly popular for speeding up rare events in simulation such as molecular
      dynamics (MD) without biasing the system dynamics. Several adaptive sampling strategies have
      been proposed, but it is not clear which methods perform better for different physical
      systems. In this work, we present a systematic evaluation of selected adaptive sampling
      strategies on a wide selection of fast folding proteins. The adaptive sampling strategies
      were emulated using models constructed on already existing MD trajectories. We provide
      theoretical limits for the sampling speed-up and compare the performance of different
      strategies with and without using some a priori knowledge of the system. The results show
      that for different goals, different adaptive sampling strategies are optimal. In order to
      sample slow dynamical processes such as protein folding without a priori knowledge of the
      system, a strategy based on the identification of a set of metastable regions is
      consistently the most efficient, while a strategy based on the identification of microstates
      performs better if the goal is to explore newer regions of the conformational space.
      Interestingly, the maximum speed-up achievable for the adaptive sampling of slow processes
      increases for proteins with longer folding times, encouraging the application of these
      methods for the characterization of slower processes, beyond the fast-folding proteins
      considered here.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#summary: asfd

tags:
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: ""
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

