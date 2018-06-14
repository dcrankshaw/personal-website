+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Model serving and management at scale using open-source tools"
time_start = 2018-09-11T09:00:00
time_end = 2018-09-11T12:30:00
abstract = ""
abstract_short = ""
event = "Strata Data Conference"
event_url = "https://conferences.oreilly.com/strata/strata-ny/public/schedule/detail/69861"
location = "New York, New York"
draft = false

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["clipper"]

# Links (optional).
url_pdf = ""
url_slides = ""
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

Machine learning is being deployed in a growing number of applications which demand real-time, accurate, and robust predictions under heavy serving loads. Supporting these applications comes with its set of challenges, requiring the integration of machine learning software with other systems including user-facing application code, live databases, and high-volume data streams. To address these challenges, there has emerged a new class of systems, the prediction-serving system, for deploying machine learning models at inference time.

While the field of model serving is still new, there are already several prediction-serving systems that address different deployment challenges and span different points in the design space, including such systems as TensorFlow-Serving, Clipper, MXNet Model Server, AWS SageMaker, and Microsoft Azure’s Machine Learning Studio. Some are designed for a specific use case or machine learning framework while others attempt to be more general. They vary in their performance, scalability, fault-tolerance, and support for specialized hardware such as GPUs and TPUs. They vary in their ability to support more complex machine learning applications, including support for A/B testing, online exploration, or model composition. And they include open-source systems, cloud-services, and proprietary products. In the first part of this tutorial, I will provide an overview of the challenges and tradeoffs involved in prediction-serving, both for those attempting to find the best existing system for their application as well as for those planning on building their own prediction-server.

Next, I will provide a deep-dive on Clipper, an open-source, low-latency, general-purpose prediction-serving system we have been building in the RISE Lab. Clipper interposes between applications that consume predictions and the machine-learning models that produce predictions. By adopting a modular serving architecture and isolating models in their own containers, Clipper simplifies the model deployment process and allows models to be evaluated using the same runtime environment as that used during training. Clipper’s modular architecture provides simple mechanisms for scaling out models to meet increased throughput demands. And it leverages Kubernetes to provide fault-tolerance and fine-grained physical resource allocation on a per-model basis. Further, by abstracting models behind a uniform serving interface, Clipper allows developers to compose many machine-learning models within a single application to support increasingly common techniques such as ensemble methods, multi-armed bandit algorithms, and model composition. I will also present a case study of an industrial Clipper deployment and discuss our experience transforming a research prototype into an active, open source system.

In the final part of this tutorial, I will run a hands-on workshop for developing and deploying your first machine learning application using Clipper. You will learn the Clipper API and how to perform some common tasks such as deploy and rollback a model and scale out an application, and then get the opportunity to develop a custom machine learning application deploy it for use it in a web application.
