---
title: "Orthogonal Deep Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuai Li 
- Kui Jia
- admin 
- Tongliang Liu 
- Dacheng Tao

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-10-21T00:00:00Z"
doi: "10.1109/TPAMI.2019.2948352"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Pattern Analysis and Machine Intelligence
publication_short: TPAMI

abstract: In this paper, we introduce the algorithms of Orthogonal Deep Neural Networks (OrthDNNs) to connect with recent interest of spectrally regularized deep learning methods. OrthDNNs are theoretically motivated by generalization analysis of modern DNNs, with the aim to find solution properties of network weights that guarantee better generalization. To this end, we first prove that DNNs are of local isometry on data distributions of practical interest; by using a new covering of the sample space and introducing the local isometry property of DNNs into generalization analysis, we establish a new generalization error bound that is both scale- and range-sensitive to singular value spectrum of each of networks’ weight matrices. We prove that the optimal bound w.r.t. the degree of isometry is attained when each weight matrix has a spectrum of equal singular values, among which orthogonal weight matrix or a non-square one with orthonormal rows or columns is the most straightforward choice, suggesting the algorithms of OrthDNNs. We present both algorithms of strict and approximate OrthDNNs, and for the later ones we propose a simple yet effective algorithm called Singular Value Bounding (SVB), which performs as well as strict OrthDNNs, but at a much lower computational cost. We also propose Bounded Batch Normalization (BBN) to make compatible use of batch normalization with OrthDNNs. We conduct extensive comparative studies by using modern architectures on benchmark image classification. Experiments show the efficacy of OrthDNNs.

# Summary. An optional shortened abstract.
summary: 

tags: ["Generalization"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8877742'
url_code: 'https://github.com/Yuxin-Wen/OrthDNNs'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
# links:
# - name: new/we media Link
#   url:https://posts.careerengine.us/p/5ea18543a42719600f0f43b5


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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

