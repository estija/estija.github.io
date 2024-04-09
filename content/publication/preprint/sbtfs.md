---
title: "Simplicity Bias of Transformers to Learn Low Sensitivity Functions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Bhavya Vasudeva
- Deqing Fu
- Tianyi Zhou
- Elliott Kau
- Youqi Huang
- Vatsal Sharan

# Author notes (optional)
author_notes: 
- Equal Contribution
- Equal Contribution

date: "2024-03-11"
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

abstract: Transformers achieve state-of-the-art accuracy and robustness results across many tasks, but an understanding of the inductive biases that they have and how those biases are different from other neural network architectures remains elusive. Various neural network architectures such as fully connected networks have been found to have a simplicity bias towards simple functions of the data; one version of this simplicity bias is a spectral bias to simple functions in the Fourier space. In this work, we identify the notion of sensitivity of the model to random changes in the input as a notion of simplicity bias which provides a unified metric to explain the simplicity and spectral bias of Transformers across different data modalities. We show that Transformers have lower sensitivity than alternative architectures, such as LSTMs, MLPs and CNNs across both vision and language tasks. We also show that sensitivity bias correlates with improved robustness; furthermore, it can also be used as an efficient intervention to further improve the robustness of Transformers.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.06925.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
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