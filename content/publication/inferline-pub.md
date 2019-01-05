+++
title = "InferLine: ML Inference Pipeline Composition"
date = "2018-12-15"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Daniel Crankshaw**", "Gur-Eyal Sela", "Corey Zumar", "Xiangxi Mo", "Joseph E. Gonzalez", "Ion Stoica", "Alexey Tumanov"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "The dominant cost in production machine learning workloads is not training individual models but serving predictions from increasingly complex prediction pipelines spanning multiple models, machine learning frameworks, and parallel hardware accelerators. Due to the complex interaction between model configurations and parallel hardware, prediction pipelines are challenging to provision and costly to execute when serving interactive latency-sensitive applications. This challenge is exacerbated by the unpredictable dynamics of bursty workloads. In this paper we introduce InferLine, a system which efficiently provisions and executes ML inference pipelines subject to end-to-end latency constraints by proactively optimizing and reactively controlling per-model configuration in a fine-grained fashion. Unpredictable changes in the serving workload are dynamically and cost-optimally accommodated with minimal service level degradation. InferLine introduces (1) automated model profiling and pipeline lineage extraction, (2) a fine-grain, cost-minimizing pipeline configuration planner, and (3) a fine-grain reactive controller. InferLine is able to configure and deploy prediction pipelines across a wide range of workload patterns and latency goals. It outperforms coarse-grained configuration alternatives by up 7.6x in cost while achieving up to 32x lower SLO miss rate on real workloads and generalizes across state-of-the-art model serving frameworks."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_preprint = "https://arxiv.org/abs/1812.01776"
url_slides = ""
url_video = ""
url_code = ""
url_project = ""

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = ""
# caption = ""

+++

