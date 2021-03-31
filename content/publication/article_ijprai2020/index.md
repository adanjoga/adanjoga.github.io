---
title: "Detection of fiber defects using keypoints and deep learning"
authors:
- Dirk Siegmund
- admin
- Et al.
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-08-22T00:00:00Z"
doi: "10.1142/S0218001421500166"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Pattern Recognition and Artificial Intelligence"
publication_short: ""

abstract: "Due to the deforming and dynamically changing textile fibers, the quality assurance of cleaned industrial textiles is still a mostly manual task. Usually, textiles need to be spread flat, in order to detect defects using computer vision inspection methods. Already known methods for detecting defects on such inhomogeneous, voluminous surfaces use mainly supervised methods based on deep neural networks and require lots of labeled training data. 


In contrast, we present a novel unsupervised method, based on SURF keypoints, that does not require any training data. We propose using their location, number and orientation in order to group them into geographically close clusters. Keypoint clusters also indicate the exact position of the defect at the same time. We furthermore compared our approach to supervised methods using deep learning. The presented processing pipeline shows how normalization and classification methods need to be combined, in order to reliably detect fiber defects such as cuts and holes. We evaluate the performance of our system in real-world settings with images of piles of textiles, taken in stereo vision. Our results show that our novel unsupervised classification method using keypoint clustering achieves comparable results to other supervised methods."

# Summary. An optional shortened abstract.
summary: We present a novel unsupervised method for detecting defects on textile fibers, based on SURF keypoints, that does not require any training data.

tags:
- Clustering
featured: false

# links:
# - name: ''
#   url: ''
url_pdf: ''
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
  caption: 'Image credit: [**Elsevier**](https://www.sciencedirect.com/science/article/abs/pii/S1568494615007772)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
<!---
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

-->