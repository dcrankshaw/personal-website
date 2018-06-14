+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Deploying and monitoring interactive machine learning applications with Clipper"
time_start = 2018-03-07T11:50:00
time_end = 2018-03-07T12:30:00
abstract = "Machine learning is being deployed in a growing number of applications that demand real-time, accurate, and robust predictions under heavy serving loads. However, most machine learning frameworks and systems only address model training, not deployment. Clipper is an open source, general-purpose model-serving system that addresses these challenges. Interposing between applications that consume predictions and the machine learning models that produce predictions, Clipper simplifies the model deployment process by adopting a modular serving architecture and isolating models in their own containers, allowing them to be evaluated using the same runtime environment as that used during training. Clipper’s modular architecture provides simple mechanisms for scaling out models to meet increased throughput demands and performing fine-grained physical resource allocation for each model. Further, by abstracting models behind a uniform serving interface, Clipper allows developers to compose many machine learning models within a single application to support increasingly common techniques such as ensemble methods, multiarmed bandit algorithms, and prediction cascades. Dan Crankshaw offers an overview of the Clipper serving system and explains how to use it to serve Apache Spark and TensorFlow models on Kubernetes. Dan concludes by discussing some recent work on statistical performance monitoring for machine learning models."
abstract_short = ""
event = "Strata Data Conference 2018"
event_url = "https://conferences.oreilly.com/strata/strata-ca/public/schedule/detail/64418"
location = "San Jose, CA"
draft = false

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["clipper"]

# Links (optional).
url_pdf = ""
url_slides = "files/slides/clipper@strata_san_jose_3_7_2018.pptx"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


