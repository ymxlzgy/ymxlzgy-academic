---
title: "FlowMOT: 3D Multi-Object Tracking by Scene Flow Association"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Guangyao Zhai
- Xin Kong
- Jinhao Cui
- Yong Liu
- Zhen Yang

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-11-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted to *IEEE Robotics and Automation Letters*
publication_short: Submitted to *IEEE Robotics and Automation Letters*

abstract:  Most end-to-end Multi-Object Tracking (MOT) methods face the problems of low accuracy and poor generalization ability. Although traditional filter-based methods can achieve better results, they are difficult to be endowed with optimal hyperparameters and often fail in varying scenarios. To alleviate these drawbacks, we propose a LiDAR-based 3D MOT framework named FlowMOT, which integrates point-wise motion information into the traditional matching algorithm, enhancing the robustness of the data association. We firstly utilize a scene flow estimation network to obtain implicit motion information between two adjacent frames and calculate the predicted detection for each old tracklet in the previous frame. Then we use Hungarian algorithm to generate optimal matching relations with the ID propagation strategy to finish the tracking task. Experiments on KITTI MOT dataset show that our approach outperforms recent end-to-end methods and achieves competitive performance with the state-of-the-art filter-based method. In addition, ours can work steadily in the various speed scenes where the filter-based methods may fail.

# Summary. An optional shortened abstract.
summary: Submitted to  *IEEE Robotics and Automation Letters (RA-L)*.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.07541.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=VNloCZFwkr4&t=6s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A glimpse of FlowMOT results in sequence 01. Red 1 and
Green 2 stand for the same chosen car in two adjacent frames. Blue
arrows represent the point-wise scene flow belonging to the car.'
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

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/VNloCZFwkr4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>