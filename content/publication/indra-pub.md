+++
title = "Inverted Indices for Particle Tracking in Petascale Cosmological Simulations"
date = "2013-07-29"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Daniel Crankshaw**", "Randal Burns", "Bridget Falck", "Tamás Budavári", "Alexander S. Szalay", "Jie Wang"]

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
publication = "In *International Conference on Scientific and Statistical Database Management (SSDBM)*."
publication_short = "In *SSDBM*"

# Abstract and optional shortened version.
abstract = "We describe the challenges arising from tracking dark matter particles in state of the art cosmological simulations. We are in the process of running the Indra suite of simulations, with an aggregate count of more than 35 trillion particles and 1.1PB of total raw data volume. However, it is not enough just to store the particle positions and velocities in an efficient manner -- analyses also need to be able to track individual particles efficiently through the temporal history of the simulation. The required inverted indices can easily have raw sizes comparable to the original simulation. We explore various strategies on how to create an efficient index for such data, using additional insight from the physical properties of the particle motions for a greatly compressed data representation. The basic particle data are stored in a relational database in course-grained containers corresponding to leaves of a fixed depth oct-tree labeled by their Peano-Hilbert index. Within each container the individual objects are sorted by their Lagrangian identifier. Thus each particle has a multi-level address: the PH key of the container and the index of the particle within the sorted array (the slot). Given the nature of the cosmological simulations and choice of the PH-box sizes, in consecutive snapshots particles can only cross into spatially adjacent boxes. Also, the slot number of a particle in adjacent snapshots is adjusted up or down by typically a small number. As a result, a special version of delta encoding over the multi-tier address already results in a dramatic reduction of data that needs to be stored. We follow next with an efficient bit-compression, adapting to the statistical properties of the two-part addresses, achieving a final compression ratio better than a factor of 9. The final size of the full inverted index is projected to be 22.5 TB for a petabyte ensemble of simulations."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = [""]

# Links (optional).
url_pdf = "files/papers/indra-ssdbm.pdf"

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

