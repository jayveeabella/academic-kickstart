---
title: "APE-Gen: A Fast Method for Generating Ensembles of Bound Peptide-MHC Conformations"
authors:
- admin
- Dinler Antunes
- Cecilia Clementi
- Lydia Kavraki
date: "2019-01-01T00:00:00Z"
doi: "10.3390/molecules24050881"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Molecules, 24*(5)"
publication_short: ""

abstract: The Class I Major Histocompatibility Complex (MHC) is a central protein in
      immunology as it binds to intracellular peptides and displays them at the cell surface for
      recognition by T-cells. The structural analysis of bound peptide-MHC complexes (pMHCs) holds
      the promise of interpretable and general binding prediction (i.e., testing whether a given
      peptide binds to a given MHC). However, structural analysis is limited in part by the
      difficulty in modelling pMHCs given the size and flexibility of the peptides that can be
      presented by MHCs. This article describes APE-Gen (Anchored Peptide-MHC Ensemble Generator),
      a fast method for generating ensembles of bound pMHC conformations. APE-Gen generates an
      ensemble of bound conformations by iterated rounds of (i) anchoring the ends of a given
      peptide near known pockets in the binding site of the MHC, (ii) sampling peptide backbone
      conformations with loop modelling, and then (iii) performing energy minimization to fix
      steric clashes, accumulating conformations at each round. APE-Gen takes only minutes on a
      standard desktop to generate tens of bound conformations, and we show the ability of APE-Gen
      to sample conformations found in X-ray crystallography even when only sequence information
      is used as input. APE-Gen has the potential to be useful for its scalability (i.e.,
      modelling thousands of pMHCs or even non-canonical longer peptides) and for its use as a
      flexible search tool. We demonstrate an example for studying cross-reactivity.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#summary: asfd

tags:
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: http://www.mdpi.com/1420-3049/24/5/881
url_code: 'https://github.com/KavrakiLab/APE-Gen'
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

