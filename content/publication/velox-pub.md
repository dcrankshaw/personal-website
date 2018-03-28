+++
title = "The Missing Piece in Complex Analytics: Low Latency, Scalable Model Management and Serving with Velox"
date = "2015-01-04"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Daniel Crankshaw**", "Peter Bailis", "Joseph E. Gonzalez", "Haoyuan Li", "Zhao Zhang", "Michael J. Franklin", "Ali Ghodsi", "Michael I. Jordan", "Ion Stoica"]

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
publication = "In *Conference on Innovative Data Systems Research (CIDR)*."
publication_short = "In *CIDR*"

# Abstract and optional shortened version.
abstract = "To support complex data-intensive applications such as personalized recommendations, targeted advertising, and intelligent services, the data management community has focused heavily on the design of systems to support training complex models on large datasets. Unfortunately, the design of these systems largely ignores a critical component of the overall analytics process: the deployment and serving of models at scale. In this work, we present Velox, a new component of the Berkeley Data Analytics Stack. Velox is a data management system for facilitating the next steps in real-world, large-scale analytics pipelines: online model management, maintenance, and serving. Velox provides end-user applications and services with a low-latency, intuitive interface to models, transforming the raw statistical models currently trained using existing offline large-scale compute frameworks into full-blown, end-to-end data products capable of recommending products, targeting advertisements, and personalizing web content. To provide up-to-date results for these complex models, Velox also facilitates lightweight online model maintenance and selection (i.e., dynamic weighting). In this paper, we describe the challenges and architectural considerations required to achieve this functionality, including the abilities to span online and offline systems, to adaptively adjust model materialization strategies, and to exploit inherent statistical properties such as model error tolerance, all while operating at \"Big Data\" scale."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["velox"]

# Links (optional).
url_pdf = "files/papers/veloxms.pdf"
url_code = "https://github.com/amplab/velox-modelserver"

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

