+++
title = "Clipper: A Low-Latency Online Prediction Serving System"
date = "2017-03-27"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Daniel Crankshaw**", "Xin Wang", "Giulio Zhou", "Michael J. Franklin", "Joseph E. Gonzalez", "Ion Stoica"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Usenix Symposium on Networked Systems Design and Implementation (NSDI)*."
publication_short = "In *NSDI*"

# Abstract and optional shortened version.
abstract = "Machine learning is being deployed in a growing number of applications which demand real-time, accurate, and robust predictions under heavy query load. However, most machine learning frameworks and systems only address model training and not deployment. In this paper, we introduce Clipper, a general-purpose low-latency prediction serving system. Interposing between end-user applications and a wide range of machine learning frameworks, Clipper introduces a modular architecture to simplify model deployment across frameworks and applications. Furthermore, by introducing caching, batching, and adaptive model selection techniques, Clipper reduces prediction latency and improves prediction throughput, accuracy, and robustness without modifying the underlying machine learning frameworks. We evaluate Clipper on four common machine learning benchmark datasets and demonstrate its ability to meet the latency, accuracy, and throughput demands of online serving applications. Finally, we compare Clipper to the Tensorflow Serving system and demonstrate that we are able to achieve comparable throughput and latency while enabling model composition and online learning to improve accuracy and render more robust predictions."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["clipper"]

# Links (optional).
url_pdf = "https://www.usenix.org/system/files/conference/nsdi17/nsdi17-crankshaw.pdf"
url_slides = "https://www.usenix.org/sites/default/files/conference/protected-files/nsdi17_slides_crankshaw.pdf"
url_video = "https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/crankshaw"
url_code = "https://github.com/amplab/clipper-v0"
url_project = "http://clipper.ai"

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

