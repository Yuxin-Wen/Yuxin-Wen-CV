---
title: "Geometry-Aware Generation of Adversarial Point Clouds"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin 
- Jiehong Lin
- Ke Chen 
- C. L. Philip Chen
- Kui Jia

# Author notes (optional)
author_notes:

date: "2020-12-15T00:00:00Z"
doi: "10.1109/TPAMI.2020.3044712"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: *TPAMI*

abstract: Machine learning models have been shown to be vulnerable to adversarial examples. While most of the existing methods for adversarial attack and defense work on the 2D image domain, a few recent attempts have been made to extend them to 3D point
cloud data. However, adversarial results obtained by these methods typically contain point outliers, which are both noticeable and easy to defend against using the simple techniques of outlier removal. Motivated by the different mechanisms by which humans perceive 2D images and 3D shapes, in this paper we propose the new design of geometry-aware objectives, whose solutions favor (the discrete versions of) the desired surface properties of smoothness and fairness. To generate adversarial point clouds, we use a targeted attack misclassification loss that supports continuous pursuit of increasingly malicious signals. Regularizing the targeted attack loss with our proposed geometry-aware objectives results in our proposed method, Geometry-Aware Adversarial Attack ($GeoA^{3}$). The results of $GeoA^{3}$ tend to be more harmful, arguably harder to defend against, and of the key adversarial characterization of being imperceptible to humans. While the main focus of this paper is to learn to generate adversarial point clouds, we also present a simple but effective algorithm termed $Geo_{+}A^{3}-IterNormPro$, with Iterative Normal Projection (IterNorPro) that solves a new objective function $Geo_{+}A^{3}$, towards surface-level adversarial attacks via generation of adversarial point clouds. We quantitatively evaluate our methods on both synthetic and physical objects in terms of attack success rate and geometric regularity. For a qualitative evaluation, we conduct subjective studies by collecting human preferences from Amazon Mechanical Turk. Comparative results in comprehensive experiments confirm the advantages of our proposed methods.

# Summary. An optional shortened abstract.
summary: 

tags: [Adversarial example]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9294112'
url_code: 'https://github.com/Yuxin-Wen/GeoA3'
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
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

