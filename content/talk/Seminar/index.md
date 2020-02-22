---
title: Robustness of Variational Inference under Model Misspecification
event: Statistics and Probability Seminar
event_url: http://maths.dept.shef.ac.uk/maths/sem_semester_9.html
location: The University of Sheffield, UK
summary: 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-02-13"
all_day: true

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right
links:


url_pdf: ""
url_slides: https://github.com/ineskris/hail-workshop-2019/blob/master/Hail_workshop.pdf/
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---

In many complex scientific problems, we deal with a model that is misspecified relative to the data generating process, in the sense that there is no parameter setting that allows the model to perfectly replicate the data. We will review the recent paper Generalized Variational Inference (https://arxiv.org/pdf/1904.02063.pdf) and expose arguments for using VI under model misspecification. As an application, we will focus on the Hodgkin Huxley model of action potentials, and infer parameters from uncertain experimental measurements using a variational auto encoder method.
