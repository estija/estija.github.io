---
title: "Implicit Bias and Fast Convergence Rates for Self-attention"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Bhavya Vasudeva
- Puneesh Deora
- Christos Thrampoulidis

# Author notes (optional)
author_notes: 
- Equal Contribution
- Equal Contribution

date: "2024-02-08"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: BGPT Workshop@ICLR'24; Under review
publication_short: 

abstract: Self-attention, the core mechanism of transformers, distinguishes them from traditional neural networks and drives their outstanding performance. Towards developing the fundamental optimization principles of self-attention, we investigate the implicit bias of gradient descent (GD) in training a self-attention layer with fixed linear decoder in binary classification. Drawing inspiration from the study of GD in linear logistic regression over separable data, recent work demonstrates that as the number of iterations t approaches infinity, the key-query matrix Wt converges locally (with respect to the initialization direction) to a hard-margin SVM solution Wmm. Our work enhances this result in four aspects. Firstly, we identify non-trivial data settings for which convergence is provably global, thus shedding light on the optimization landscape. Secondly, we provide the first finite-time convergence rate for Wt to Wmm, along with quantifying the rate of sparsification in the attention map. Thirdly, through an analysis of normalized GD and Polyak step-size, we demonstrate analytically that adaptive step-size rules can accelerate the convergence of self-attention. Additionally, we remove the restriction of prior work on a fixed linear decoder. Our results reinforce the implicit-bias perspective of self-attention and strengthen its connections to implicit-bias in linear logistic regression, despite the intricate non-convex nature of the former.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2402.05738.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/15F2mCDRmyErZi4oREsbArKk3_pjASmZ6/view?usp=share_link'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---