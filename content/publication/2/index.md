---
title: "Probabilistic Projective Association and Semantic Guided Relocalization for Dense Reconstruction"

authors:
- Sheng Yang
- admin
- Yan-Pei Cao
- Yu-Kun Lai
- Shi-min Hu

date: "2019-05-24"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-24"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICRA 2019"
publication_short: ""

abstract: We present a real-time dense mapping system which uses the predicted 2D semantic labels for optimizing the geometric quality of reconstruction. With a combination of Convolutional Neural Networks (CNNs) for 2D labeling and a Simultaneous Localization and Mapping (SLAM) system for camera trajectory estimation, recent approaches have succeeded in incrementally fusing and labeling 3D scenes. However, the geometric quality of the reconstruction can be further improved by incorporating such semantic prediction results, which is not sufficiently exploited by existing methods. In this paper, we propose to use semantic information to improve two crucial modules in the reconstruction pipeline, namely tracking and loop detection, for obtaining mutual benefits in geometric reconstruction and semantic recognition. Specifically for tracking, we use a novel probabilistic projective association approach to efficiently pick out candidate correspondences, where the confidence of these correspondences is quantified concerning similarities on all available short-term invariant features. For the loop detection, we incorporate these semantic labels into the original encoding through Randomized Ferns to generate a more comprehensive representation for retrieving candidate loop frames. Evaluations on a publicly available synthetic dataset have shown the effectiveness of our approach that considers such semantic hints as a reliable feature for achieving higher geometric quality

# Summary. An optional shortened abstract.
summary: "ICRA 2019"

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://orca-mwe.cf.ac.uk/120190/7/ppDenseReconstruction_ICRA2019.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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
slides: ""
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} 

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).-->