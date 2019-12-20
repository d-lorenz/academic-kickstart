---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Vmsbase"
summary: "VMSbase is an R package devised to manage, process and visualize information about fishing vessels activity (provided by the vessel monitoring system - VMS) and catches/landings (as reported in the logbooks). VMSbase is primarily conceived to be user-friendly; to this end, a suite of state-of-the-art analyses is accessible via a graphical interface. In addition, the package uses a database platform allowing large datasets to be stored, managed and processed vey efficiently. Methodologies include data cleaning, that is removal of redundant or evidently erroneous records, and data enhancing, that is interpolation and merging with external data sources. In particular, VMSbase is able to estimate sea bottom depth for single VMS pings using an on-line connection to the National Oceanic and Atmospheric Administration (NOAA) database. It also allows VMS pings to be assigned to whatever geographic partitioning has been selected by users. Standard analyses comprise: 1) métier identification (using a modified CLARA clustering approach on Logbook data or Artificial Neural Networks on VMS data); 2) linkage between VMS and Logbook records, with the former organized into fishing trips; 3) discrimination between steaming and fishing points; 4) computation of spatial effort with respect to user-selected grids; 5) calculation of standard fishing effort indicators within Data Collection Framework; 6) a variety of mapping tools, including an interface for Google viewer; 7) estimation of trawled area. Here we report a sample workflow for the accessory sample datasets (available with the package) in order to explore the potentialities of VMSbase. In addition, the results of some performance tests on two large datasets (1×105 and 1×106 VMS signals, respectively) are reported to inform about the time required for the analyses. The results, although merely illustrative, indicate that VMSbase can represent a step forward in extracting and enhancing information from VMS/logbook data for fisheries studies."
authors: []
tags: []
categories: []
date: 2019-12-20T11:26:16+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
