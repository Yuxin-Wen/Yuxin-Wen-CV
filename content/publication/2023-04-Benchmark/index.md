---
title: "Surface reconstruction from point clouds: A survey and a benchmark"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Huangzhang Jin
- admin
- Zihao Wang
- Jinjuan Ren
- Kui Jia

# Author notes (optional)
author_notes: 
- "Equal contribution"
- "Equal contribution"
- 
date: "2022-04-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Pattern Analysis and Machine Intelligence
publication_short: TPAMI

abstract: Reconstruction of a continuous surface of two-dimensional manifold from its raw, discrete point cloud observation is a long-standing problem in computer vision and graphics research. The problem is technically ill-posed, and becomes more difficult considering that various sensing imperfections would appear in the point clouds obtained by practical depth scanning. In literature, a rich set of methods has been proposed, and reviews of existing methods are also provided. However, existing reviews are short of thorough investigations on a common benchmark. The present paper aims to review and benchmark existing methods in the new era of deep learning surface reconstruction. To this end, we contribute a large-scale benchmarking dataset consisting of both synthetic and real-scanned data; the benchmark includes object- and scene-level surfaces and takes into account various sensing imperfections that are commonly encountered in practical depth scanning. We conduct thorough empirical studies by comparing existing methods on the constructed benchmark, and pay special attention on robustness of existing methods against various scanning imperfections; we also study how different methods generalize in terms of reconstructing complex surface shapes. Our studies help identity the best conditions under which different methods work, and suggest some empirical findings. For example, while deep learning methods are increasingly popular in the research community, our systematic studies suggest that, surprisingly, a few classical methods perform even better in terms of both robustness and generalization; our studies also suggest that the practical challenges of misalignment of point sets from multi-view scanning, missing of surface points, and point outliers remain unsolved by all the existing surface reconstruction methods. We expect that the benchmark and our studies would be valuable both for practitioners and as a guidance for new innovations in future research. We make the benchmark publicly accessible at https://Gorilla-Lab-SCUT.github.io/SurfaceReconstructionBenchmark.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), Accepted, 2024


tags: ["3D reconstruction"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2205.02413'
url_code: 'https://github.com/Gorilla-Lab-SCUT/SCUTSurface-code'
url_dataset: 'https://mailscuteducn-my.sharepoint.com/personal/201730254453_mail_scut_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F201730254453%5Fmail%5Fscut%5Fedu%5Fcn%2FDocuments%2FScutSurfaceData&ga=1'
url_poster: ''
url_project: 'https://Gorilla-Lab-SCUT.github.io/SurfaceReconstructionBenchmark'
url_slides: ''
url_source: ''
url_video: ''

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

