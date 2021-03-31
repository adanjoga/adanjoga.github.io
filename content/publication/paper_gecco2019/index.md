---
title: "Many-view clustering: an illustration using multiple dissimilarity measures"
authors:
- admin
- julia
- will
- mario

date: "2019-07-03T00:00:00Z"
doi: "10.1145/3319619.3323365"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *GECCO '19: Proceedings of the Genetic and Evolutionary Computation Conference Companion*"
publication_short:

abstract: "Multi-view problems generalize standard machine learning problems to situations in which data entities are described from multiple different perspectives, a situation that arises in many applications due to the consideration of multiple data sources or multiple metrics of dissimilarity between entities. Multi-view algorithms for data clustering offer the opportunity to fully consider and integrate this information during the clustering process, but current algorithms are often limited to the use of two views. 


Here, we describe the design of an evolutionary algorithm for the problem of multi-view data clustering. The use of a many-objective evolutionary algorithm addresses limitations of previous work, as the resulting method should be capable of scaling to settings with four or more views. We evaluate the performance of our proposed algorithm for a set of traditional benchmark datasets, where multiple views are derived using distinct measures of dissimilarity. Our results demonstrate the ability of our method to effectively deal with a many-view setting, as well as the performance boost obtained from the integration of complementary measures of dissimilarity for both synthetic and real-world datasets."

# Summary. An optional shortened abstract.
summary: Here we describe the design of an evolutionary algorithm for the problem of multi-view data clustering. The use of a many-objective evolutionary algorithm addresses limitations of previous work, as the resulting method should be capable of scaling to settings with four or more views.

tags:
- Clustering
- Evolutionary Algorithms
- Multi-objective Optimization
- Dissimilarity Measures 
featured: true

links:
- name: "Project"
  url: "project/mvcrepository-project/"
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- [mvcrepository-proyect]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
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