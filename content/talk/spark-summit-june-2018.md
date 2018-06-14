+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Deploying and Monitoring Heterogeneous Machine Learning Applications with Clipper"
time_start = 2018-06-06T11:00:00
time_end = 2018-06-06T11:40:00
abstract = "Machine learning is being deployed in a growing number of applications which demand real-time, accurate, and robust predictions under heavy serving loads. However, most machine learning frameworks and systems only address model training and not deployment. Clipper is an open-source, general-purpose model-serving system that addresses these challenges. Interposing between applications that consume predictions and the machine-learning models that produce predictions, Clipper simplifies the model deployment process by adopting a modular serving architecture and isolating models in their own containers, allowing them to be evaluated using the same runtime environment as that used during training. Clipper’s modular architecture provides simple mechanisms for scaling out models to meet increased throughput demands and performing fine-grained physical resource allocation for each model. Further, by abstracting models behind a uniform serving interface, Clipper allows developers to compose many machine-learning models within a single application to support increasingly common techniques such as ensemble methods, multi-armed bandit algorithms, and prediction cascades. In this talk I will provide an overview of the Clipper serving system and discuss how to get started using Clipper to serve Apache Spark and TensorFlow models on Kubernetes. I will then discuss some recent work on statistical performance monitoring for machine learning models."
abstract_short = ""
event = "Spark Summit 2018"
event_url = "https://databricks.com/session/deploying-and-monitoring-heterogeneous-machine-learning-applications-with-clipper"
location = "San Francisco, CA"
draft = false

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["clipper"]

# Links (optional).
url_pdf = ""
url_slides = "files/slides/clipper@spark_summit_6_6_2018.pptx"
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


