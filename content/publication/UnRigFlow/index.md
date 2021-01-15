---
title: "Unsupervised Learning of Scene Flow EstimationFusing with Local Rigidity"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Liang Liu
- Guangyao Zhai
- Wenlong Ye
- Yong Liu

date: "2019-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Published in *Twenty-Eighth International Joint Conference on Artificial Intelligence (IJCAI-19)*
publication_short: Published in *IJCAI 2019*

abstract: "Scene  flow  estimation  in  the  dynamic  scene  remains a challenging task.   Computing  scene flowby  a combination  of  2D  optical  flow  and  depth has  shown  to  be  considerably  faster  with  acceptable performance.  In this work, we present a unified framework for joint unsupervised learning of stereo  depth  and  optical  flow  with  explicit  local rigidity to estimate scene flow. We estimate camera motion  directly  by  a  Perspective-n-Point  methodfrom the optical flow and depth predictions,  with RANSAC outlier rejection scheme. In order to disambiguate the object motion and the camera motion in the scene, we distinguish the rigid region by the reproject error and the photometric similarity. By joint learning with the local rigidity, both depth and optical networks can be refined.   This framework  boosts  all  four  tasks:   depth,  optical  flow, camera motion estimation, and object motion segmentation.   Through the evaluation on the KITTI benchmark, we show that the proposed framework achieves  state-of-the-art  results  amongst  unsupervised methods.  Our models and code are available at https://github.com/lliuz/unrigidflow."

# Summary. An optional shortened abstract.
summary: Published in the *Twenty-Eighth International Joint Conference on Artificial Intelligence (IJCAI 2019)*
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ijcai.org/Proceedings/2019/0123.pdf'
url_code: ' https://github.com/lliuz/unrigidflow'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "0"
  preview_only: 



---
