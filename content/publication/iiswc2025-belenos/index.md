---
title: "Belenos: Bottleneck Evaluation to Link Biomechanics to Novel Computing Optimizations"
authors:
- Hana Chitsaz
- Johnson Umeike
- admin
- Babak N. Safa
- Bahar Asgari
date: "2025-09-19T00:00:00Z"
doi: "10.48550/arXiv.2510.15908"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE International Symposium on Workload Characterization (IISWC) 2025"
publication_short: ""

abstract: Finite element simulations are essential in biomechanics, enabling detailed modeling of tissues and organs. However, architectural inefficiencies in current hardware and software stacks limit performance and scalability, especially for iterative tasks like material parameter identification. As a result, workflows often sacrifice fidelity for tractability. Reconfigurable hardware, such as FPGAs, offers a promising path to domain-specific acceleration without the cost of ASICs, but its potential in biomechanics remains underexplored. This paper presents Belenos, a comprehensive workload characterization of finite element biomechanics using FEBio, a widely adopted simulator, gem5 sensitivity studies, and VTune analysis. VTune results reveal that smaller workloads experience moderate front-end stalls, typically around 13.1%, whereas larger workloads are dominated by significant back-end bottlenecks, with backend-bound cycles ranging from 59.9% to over 82.2%. Complementary gem5 sensitivity studies identify optimal hardware configurations for Domain-Specific Accelerators (DSA), showing that suboptimal pipeline, memory, or branch predictor settings can degrade performance by up to 37.1%. These findings underscore the need for architecture-aware co-design to efficiently support biomechanical simulation workloads.

# Summary. An optional shortened abstract.


tags:
- Finite Element Analysis
- Biomechanics
- Workload Characterization
- Reconfigurable Computing
- Domain-Specific Acceleration
- Computer Architecture
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2510.15908
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

