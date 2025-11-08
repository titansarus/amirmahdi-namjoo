---
title: "Chasoň: Supporting Cross HBM Channel Data Migration to Enable Efficient Sparse Algebraic Acceleration"
authors:
- Ubaid Bakhtiar
-  admin
- Bahar Asgari
date: "2025-10-18T00:00:00Z"
doi: "10.1145/3725843.3756086"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 58th IEEE/ACM International Symposium on Microarchitecture (MICRO 2025)"
publication_short: ""

abstract: High bandwidth memory (HBM) equipped sparse accelerators are emerging as a new class of accelerators that offer concurrent accesses to data and parallel execution to mitigate the memory bound behavior of sparse kernels. However, because of their underlying non-zero scheduling scheme, state-of-the-art HBM-based sparse accelerators (e.g., Serpens) suffer from high resource underutilization causing suboptimal performance, and inefficiency. To solve this challenge, we propose Chasoň, an HBM-based streaming accelerator for sparse kernels, specifically sparse matrix vector multiplication. Chasoň supports our novel non-zero scheduling scheme called Cross-HBM Channel out-of-order (OoO) Scheduling (CrHCS) to enable data migration across HBM channels and mitigate resource underutilization. We implement Chasoň on AMD Alveo U55C, achieving 301MHz clock frequency and evaluate it based on SuiteSparse and SNAP matrix collections. Chasoň improves the resource utilization and achieves up to 8 × , 20.33 × , 11.65 × , and 2.67 × performance improvement and 2.03 × , 34.72 × , 19.48 × , and 14.61 × better energy efficiency over Serpens, Nvidia RTX 4090, Nvidia RTX 6000 Ada, and Intel Core i9-11980HK, respectively. The source code of Chasoň is available at https://github.com/UbaidHunts/Chason.

# Summary. An optional shortened abstract.


tags:
- HBM
- sparse matrix vector multiplication
- sparse accelerators
- computer architecture
- sparse computing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3725843.3756086
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


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
---

