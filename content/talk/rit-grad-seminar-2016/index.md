+++
title = "Text mining with a Bayesian hidden topic Markov model"
date = "2018-11-01T00:00:00"
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2017-03-23T00:00:00
#time_end = 2030-06-01T15:00:00

authors = ["KT Wilcox"]

abstract = "Topic models are a state-of-the-art probabilistic approach to extracting structural information about discrete data and have been used with great success for text mining. A recent development in topic modeling, the Hidden Topic Markov Model (HTMM), incorporates hidden Markov models, resulting in more realistic topic assignments word sense disambiguation. This is a departure from the standard 'bag-of-words' assumption of the seminal Latent Dirichlet Allocation (LDA). An expectation-maximization (EM) algorithm was proposed by Gruber, Rosen-Zvi, and Weiss (2007), but a full derivation was never published. I will introduce topic modeling, motivate the use of the HTMM and consider how one can perform inference for HTMM by EM. Finally, I will sketch my current work to extend the Hidden Topic Markov Model (HTMM) framework into a Bayesian framework in order to develop a Gibbs sampler. Differences between LDA and HTMM will be demonstrated on a corpus of articles from the *Proceedings of the Annual Conference on Neural Information Processing Systems*."
abstract_short = ""

event = "Rochester Institute of Technology Applied Statistics Graduate Seminar"
event_url = ""

location = "Rochester, New York"

selected = false

projects = ["topic-model"]

tags = ["topic-model", "bayesian", "text-mining"]

url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = "Graphical model of the Hidden Topic Markov Model."

  # Focal point (optional)
    # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
    focal_point = "Smart"

+++
