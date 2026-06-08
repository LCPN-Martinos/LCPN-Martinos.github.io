---
title: Cortical reconstruction and anatomical parcellation of high-resolution multi-modal postmortem ex vivo MRI of the human infant brain

event: Check out Pulkit's work on reconstruction and parcellation in ex vivo MRI of infant brains
event_url: https://www.biorxiv.org/content/10.64898/2026.05.07.722301v1.full

location: Houston, Texas
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: "Read Pulkit's preprint that covers his recent work with high-res multi-modal postmortem ex vivo MRI" 
abstract: "High-resolution postmortem (ex vivo) magnetic resonance imaging enables detailed examination of brain anatomy at spatial scales not achievable in vivo and provides a unique opportunity to link morphometric measurements with the underlying pathology. Despite these advantages, robust computational tools for automated anatomical segmentation and cortical surface reconstruction remain limited, particularly in postmortem infant brains. Incomplete myelination, thinner cortical ribbons, small-scale neuroanatomy, as well as an evolving tissue contrast combined with fixation-induced signal alterations and variability in postmortem preparation make standard neuroimaging pipelines unusable for postmortem infant MRI. In this work, we introduce a one-of-its-kind multi-modal high-resolution postmortem infant MRI dataset and a unified computational framework that combines deep learning-based volumetric segmentation with surface-based cortical reconstruction and anatomical parcellation in native subject space resolution. To address the pronounced domain shift inherent to postmortem MRI, we develop a postmortem-specific synthetic data generation engine (PostSynth) that explicitly models fixation-driven postmortem imaging characteristics. In particular, we incorporate postmortem-specific altered gray-white matter contrast, laminar cortical intensity heterogeneity, specimen-specific bias fields, and background signal characteristics associated with immersion media: phenomena not typically observed in in vivo data or captured by generic contrast-agnostic synthesis methods. We benchmark our framework against a set of widely used contrast-agnostic and foundational brain segmentation models, demonstrating improved anatomical consistency and segmentation performance in high-resolution postmortem infant data. The code is publicly available as part of the purple-mri package."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-09'
date_end: '2026-03-18'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2026-05-09'

authors: ['']
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:

share: false
---
Read the full preprint here: https://www.biorxiv.org/content/10.64898/2026.05.07.722301v1.full

## Abstract

High-resolution postmortem (ex vivo) magnetic resonance imaging enables detailed examination of brain anatomy at spatial scales not achievable in vivo and provides a unique opportunity to link morphometric measurements with the underlying pathology. Despite these advantages, robust computational tools for automated anatomical segmentation and cortical surface reconstruction remain limited, particularly in postmortem infant brains. Incomplete myelination, thinner cortical ribbons, small-scale neuroanatomy, as well as an evolving tissue contrast combined with fixation-induced signal alterations and variability in postmortem preparation make standard neuroimaging pipelines unusable for postmortem infant MRI. In this work, we introduce a one-of-its-kind multi-modal high-resolution postmortem infant MRI dataset and a unified computational framework that combines deep learning-based volumetric segmentation with surface-based cortical reconstruction and anatomical parcellation in native subject space resolution. To address the pronounced domain shift inherent to postmortem MRI, we develop a postmortem-specific synthetic data generation engine (PostSynth) that explicitly models fixation-driven postmortem imaging characteristics. In particular, we incorporate postmortem-specific altered gray-white matter contrast, laminar cortical intensity heterogeneity, specimen-specific bias fields, and background signal characteristics associated with immersion media: phenomena not typically observed in in vivo data or captured by generic contrast-agnostic synthesis methods. We benchmark our framework against a set of widely used contrast-agnostic and foundational brain segmentation models, demonstrating improved anatomical consistency and segmentation performance in high-resolution postmortem infant data. The code is publicly available as part of the purple-mri package.