---
title: "Misam: Machine Learning Assisted Dataflow Selection in Accelerators for Sparse Matrix Multiplication"
authors:
- Sanjali Yadav
-  admin
- Bahar Asgari
date: "2025-10-18T00:00:00Z"
doi: "10.1145/3725843.3756126"

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

abstract: The performance of Sparse Matrix-Matrix Multiplication (SpGEMM), a foundational operation in scientific computing and machine learning, is highly sensitive to the diverse and dynamic sparsity patterns of its input matrices. While specialized hardware accelerators improve efficiency, their reliance on fixed dataflows, each optimized for a narrow sparsity regime, results in suboptimal performance on real-world workloads. Even recent flexible accelerators that support multiple dataflows face two critical limitations (1) the lack of a fast and principled mechanism for runtime dataflow selection, and (2) the area overhead and hardware underutilization incurred to provide that flexibility. We present Misam, a machine learning framework that addresses these challenges to enable adaptive and hardware-efficient SpGEMM acceleration. Misam employs a lightweight decision tree to dynamically predict the optimal hardware configuration from matrix features. To overcome hardware underutilization, Misam leverages FPGA reconfigurability to deploy specialized, resource-efficient bitstreams on demand. This process is governed by an intelligent reconfiguration engine that evaluates whether the anticipated performance gain justifies the overhead of switching hardware configurations. Misam’s dynamic approach yields up to a 10.76 × speedup by judiciously reconfiguring. Misam demonstrates that a synergistic combination of machine learning-based prediction and judicious hardware reconfiguration can achieve high performance across a wide spectrum of sparsity patterns, bridging the gap between specialized efficiency and general-purpose adaptability.

# Summary. An optional shortened abstract.


tags:
- Sparse Matrix-Matrix Multiplication
- Hardware Accelerators
- Reconfigurable Computing
- Machine Learning
- Computer Architecture
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3725843.3756126
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

