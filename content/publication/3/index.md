---
title: "Dynamic Facial Asset and Rig Generation from a Single Scan"

authors:
- admin
- Jiaman Li
- Yajie Zhao
- Mingming He
- Karl Bladin
- Hao Li
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-11-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-13"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGGRAPH Asia 2020"
publication_short: ""

abstract: The creation of high-fidelity computer-generated (CG) characters used in film and gaming requires intensive manual labor and a comprehensive set of facial assets to be captured with complex hardware, resulting in high cost and long production cycles. In order to simplify and accelerate this digitization process, we propose a framework for the automatic generation of high-quality dynamic facial assets, including rigs which can be readily deployed for artists to polish. Our framework takes a single scan as input to generate a set of personalized blendshapes, dynamic and physically-based textures, as well as secondary facial components (e.g., teeth and eyeballs). Built upon a facial database consisting of pore-level details, with over 4,000 scans of varying expressions and identities, we adopt a self-supervised neural network to learn personalized blendshapes from a set of template expressions. We also model the joint distribution between identities and expressions, enabling the inference of the full set of personalized blendshapes with dynamic appearances from a single neutral input scan. Our generated personalized face rig assets are seamlessly compatible with cutting-edge industry pipelines for facial animation and rendering. We demonstrate that our framework is robust and effective by inferring on a wide range of novel subjects, and illustrate compelling rendering results while animating faces with generated customized physically-based dynamic textures.

# Summary. An optional shortened abstract.
summary: "ACM Siggraph Asia 2020"

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2010.00560.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=VV655fi6tH4'

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