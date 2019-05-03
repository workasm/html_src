+++
# Project title.
title = "XSurface Dupin Cyclides"
math = true
share = false
profile = false

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "A collection of rendered Duping Cyclide surfaces with algebraic arrangements"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
# tags = ["Deep Learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
#  Focal point (optional)
#   Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Bottom"

[header]
  image = "cgal_logo.png"
 # caption = "Image credit: [**Academic**](https://github.com/gcushen/hugo-academic/)"

+++

This project presents a set of curves rendered on the surface of a Dupin Cyclide. It was done together with my colleges from the [Max-Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/algorithms-complexity).
My part was essentially the rendering of plane algebraic curces (based on my Masters's thesis) and OpenGL rendering of the surfaces. The rendered Dupin Cyclides looked so much cool that they were printed in the MPII calendar and also became a permanent logo of the "Algorithms and Complexity" research group. See also the [publication list](#publication-list) below.

{{< gallery album="images" >}}


### Publication list

1. A. Eigenwillig, M. Kerber: Exact and efficient 2D-arrangements of arbitrary algebraic curves. In: SODA 2008. [ACM](https://dl.acm.org/citation.cfm?id=1347096)
2. A. Eigenwillig, M. Kerber, N. Wolpert: Fast and exact geometric analysis of real algebraic plane curves. In: ISSAC 2007. [DOI](https://doi.org/10.1145/1277548.1277570)
3. K. Mehlhorn, A. Eigenwillig, L. Kettner, W. Krandick, S. Schmitt, N. Wolpert: A Descartes Algorithms for Polynomials with Bit-Stream Coefficients. In: Reliable Implementation of Real Number Algorithms, 2005. [DOI](https://doi.org/10.1007/11555964_12)
4. E. Berberich, M. Kerber: Exact arrangements on tori and Dupin cyclides. In: SPM 2008. [DOI](https://doi.org/10.1145/1364901.1364912)
5. E. Berberich, M. Kerber, M. Sagraloff: Exact geometric-topological analysis of algebraic surfaces. In: SCG 2008. [DOI](https://doi.org/10.1145/1377676.1377703)
6. E. Berberich, M. Sagraloff: A generic and flexible framework for the geometrical and topological analysis of (algebraic) surfaces. In: SMP 2008. [DOI] (https://doi.org/10.1145/1364901.1364925)
7. E. Berberich: Robust and efficient software for problems in 2.5-dimensional non-linear geometry: algorithms and implementations. PhD Thesis, 2008. [DOI](https://dx.doi.org/10.22028/D291-25937)
8. P. Emeliyanenko, E. Berberich, M. Sagraloff: Visualizing Arcs of Implicit Algebraic Curves, Exactly and Fast. In: ISCV 2009. [DOI](https://doi.org/10.1007/978-3-642-10331-5_57)

