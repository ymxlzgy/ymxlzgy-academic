---
title: "PASS3D: Precise and Accelerated Semantic Segmentation for 3D PointCloud"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xin Kong
- admin
- Baoquan Zhong
- Yong Liu

date: "2019-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Published in *2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
publication_short: Published in *IROS 2019*

abstract: "In  this  paper,  we  propose  PASS3D  to  achieve point-wise   semantic   segmentation   for   3D   point   cloud.   Our framework  combines  the  effciency  of  traditional  geometric methods  with  robustness  of  deep  learning  methods,  consisting of  two  stages:  At  stage-1,  our  accelerated  cluster  proposal algorithm will generate refined cluster proposals by segmenting point clouds without ground, capable of generating less redundant  proposals  with  higher  recall  in  an  extremely  short  time; stage-2  we  will  amplify  and  further  process  these  proposals by  a  neural  network  to  estimate  semantic  label  for  each  pointand  meanwhile  propose  a  novel  data  augmentation  method  toenhance the network's recognition capability for all categories especially   for   non-rigid   objects.   Evaluated   on   KITTI   raw dataset, PASS3D stands out against the state-of-the-art on some results, making itself competent to 3D perception in autonomous driving system."

# Summary. An optional shortened abstract.
summary: Published in *2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8968296'
url_code: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=cukEqDuP_Qw'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'The  PASS3D  architecture  for  point-wise  semantic  segmentation.'
  focal_point: "0"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/cukEqDuP_Qw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>