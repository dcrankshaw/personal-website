+++
title = "IDK Cascades: Fast Deep Learning by Learning not to Overthink"
date = "2017-09-13"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Xin Wang", "Yujia Luo", "**Daniel Crankshaw**", "Alexey Tumanov", "Fisher Yu", "Joseph E. Gonzalez"]

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
abstract = "Advances in deep learning have led to substantial increases in prediction accuracy but have been accompanied by increases in the cost of rendering predictions. We conjecture that for a majority of real-world inputs, the recent advances in deep learning have created models that effectively *over-think* on simple inputs. In this paper we revisit the question of how to effectively build model cascades to reduce prediction costs. While classic cascade techniques primarily leverage class asymmetry to reduce cost, we extend this approach to arbitrary multi-class prediction tasks. We introduce the *I Don't Know* (IDK) prediction cascades framework, a general framework for composing a set of pre-trained models to accelerate inference without a loss in prediction accuracy. We propose two search based methods for constructing cascades as well as a new cost-aware objective within this framework. We evaluate these techniques on a range of both benchmark and real-world datasets and demonstrate that prediction cascades can reduce computation by 37%, resulting in up to 1.6x speedups in image classification tasks over state-of-the-art models without a loss in accuracy. Furthermore, on a driving motion prediction task evaluated on a large scale autonomous driving dataset, prediction cascades achieved 95% accuracy when combined with human experts, while requiring human intervention on less than 30% of the queries."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["clipper"]

# Links (optional).
url_preprint = "https://arxiv.org/abs/1706.00885"

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

