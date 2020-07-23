---
title: "Maintaining and Enhancing Diversity of Sampled Protein Conformations in
      Robotics-Inspired Methods"
authors:
- admin
- Mark Moll
- Lydia Kavraki
date: "2018-01-01T00:00:00Z"
doi: "10.1089/cmb.2017.0164"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational Biology, 25*(1)"
publication_short: ""

abstract: The ability to efficiently sample structurally diverse protein conformations allows
      one to gain a high-level view of a protein's energy landscape. Algorithms from robot motion
      planning have been used for conformational sampling and promote diversity by keeping track
      of ``coverage'' in conformational space based on the local sampling density. However, large
      proteins present special challenges. In particular, larger systems require running many
      concurrent instances of these algorithms, but these algorithms can quickly become memory
      intensive because they typically keep previously sampled conformations in memory to maintain
      coverage estimates. Additionally, many of these algorithms depend on defining useful
      perturbation strategies for exploring the conformational space, which is a very difficult
      task for large proteins because such systems are typically more constrained and exhibit
      complex motions. In this paper, we introduce two methodologies for maintaining and enhancing
      diversity in robotics-inspired conformational sampling. The first method leverages the use
      of a low-dimensional projection to define a global coverage grid that maintains coverage
      across concurrent runs of sampling. The second method is an automatic definition of a
      perturbation strategy through readily available flexibility information derived from
      B-factors, secondary structure, and rigidity analysis. Our results show a significant
      increase in the diversity of the conformations sampled for proteins consisting of up to 500
      residues. The methodologies presented in this paper may be vital components for the
      scalability of robotics-inspired approaches.

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

