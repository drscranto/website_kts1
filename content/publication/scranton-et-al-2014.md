+++
title = "A Bayesian approach to parameter estimation for a population model"
date = 2014-05-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K Scranton", "J Knape", "P de Valpine"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Ecology*"
publication_short = "In *Ecology*"

# Abstract and optional shortened version.
abstract = "Complex population processes may require equally complex models, which can lead to analytically intractable estimation problems. Approximate Bayesian computation (ABC) is a computational tool for parameter estimation in situations where likelihoods cannot be computed. Instead of using likelihoods, ABC methods quantify the similarities between an observed data set and repeated simulations from a model. A practical obstacle to implementing an ABC algorithm is selecting summary statistics and distance metrics that accurately capture the main features of the data. We demonstrate the application of a sequential Monte Carlo ABC sampler (ABC SMC) to parameter estimation of a general stochastic stage‐structured population model with ongoing reproduction and heterogeneity in development and mortality. Individual variation in demographic traits has considerable consequences for population dynamics in many systems, but including it in a population model by explicitly allowing stage durations to follow a realistic distribution creates a complex model. We applied the ABC SMC to fit the model to a simulated representative data set with known underlying parameters to evaluate the performance of the algorithm. We also introduced a systematic method for selecting summary statistics and distance metrics, using simulated data and receiver operating characteristic (ROC) curves from classification theory. Evaluations suggest that the approach is promising for model inference in our example of realistic stage‐structured population models."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = "https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/13-1065.1"
# url_preprint = "#"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "scranton2014-1.png"
caption = "Illustration of distance functions"

+++

