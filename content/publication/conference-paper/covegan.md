---
title: "Co-VeGAN: Complex-Valued Generative Adversarial Network for Compressive Sensing MR Image Reconstruction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Bhavya Vasudeva
- Puneesh Deora
- Saumik Bhattacharya
- Pyari Mohan Pradhan

# Author notes (optional)
author_notes: 
- Equal Contribution
- Equal Contribution

date: "2020-09-24"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-24"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Winter Conference on Applications of Computer Vision
publication_short: WACV 2022

abstract: Compressive sensing (CS) is widely used to reduce the acquisition time of magnetic resonance imaging (MRI). Although state-of-the-art deep learning based methods have been able to obtain fast, high-quality reconstruction of CS-MR images, their main drawback is that they treat complex-valued MRI data as real-valued entities. Most methods either extract the magnitude from the complex-valued entities or concatenate them as two real-valued channels. In both the cases, the phase content, which links the real and imaginary parts of the complex-valued entities, is discarded. In order to address the fundamental problem of real-valued deep networks, i.e. their inability to process complex-valued data, we propose a novel framework based on a complex-valued generative adversarial network (Co-VeGAN). Our model can process complex-valued input, which enables it to perform high-quality reconstruction of the CS-MR images. Further, considering that phase is a crucial component of complex-valued entities, we propose a novel complex-valued activation function, which is sensitive to the phase of the input. Extensive evaluation of the proposed approach on different datasets using various sampling masks demonstrates that the proposed model significantly outperforms the existing CS-MRI reconstruction techniques in terms of peak signal-to-noise ratio as well as structural similarity index. Further, it uses significantly fewer trainable parameters to do so, as compared to the real-valued deep learning based methods. 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2002.10523'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1i-fQ1GDCxLI8cxy9fHScGkWUMG3ly06i/view?usp=sharing'
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



