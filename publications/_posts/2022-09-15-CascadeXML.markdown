---
title:  "CascadeXML: Transformers for End-to-end Multi-resolution Training in Extreme Classification"
date:   2022-03-10
image: /publications/images/CascadeXML.png
authors: "<strong>Siddhant Kharbanda</strong>, Atmadeep Banerjee, Erik Schultheis, Rohit Babbar"
venue: "NeurIPS"
# bib: |
#   @article{Doe2021,
#     author = {Doe J.},
#     journal = {A journal of imaginary research},
#     title = {Another title of the publication},
#     year = {2021}
#   }
paper: https://arxiv.org/abs/2211.00640
code: https://github.com/xmc-aalto/cascadexml
video: https://www.youtube.com/watch?v=GnB9E5zvY_E&t=88s
---
CascadeXML is an end-to-end transformer fine-tuning algorithm which aligns the intermediate layers to the multiple resolutions of a hierarchical label tree to perform multi-label classification over millions labels in a beam-search fashion, via multi-resolution dynamic hard negative mining, outperforming Amazon's PECOS Framework by 4-6% across 5 public benchmarks while cutting GPU requirements and inference time by half.

