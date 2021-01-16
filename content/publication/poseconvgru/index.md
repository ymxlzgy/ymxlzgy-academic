---
title: "PoseConvGRU: A Monocular Approach for Visual Ego-motion Estimation by Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Liu
- Linjian Zhang
- Yong Liu
- et al

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-01-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Pubilished in *Pattern Recognition*
publication_short:  Pubilished in *Pattern Recognition*

abstract:  Visual ego-motion estimation is one of the longstanding problems which estimates the movement of cameras from images. Learning based ego-motion estimation methods have seen an increasing attention since its desirable properties of robustness to image noise and camera calibration independence. In this work, we propose a data-driven approach of learning based visual ego-motion estimation for a monocular camera. We use an end-to-end learning approach in allowing the model to learn a map from input image pairs to the corresponding ego-motion, which is parameterized as 6-DoF transformation matrix. We introduce a two-module Long-term Recurrent Convolutional Neural Networks called PoseConvGRU. The feature-encoding module encodes the short-term motion feature in an image pair, while the memory-propagating module captures the long-term motion feature in the consecutive image pairs. The visual memory is implemented with convolutional gated recurrent units, which allows propagating information over time. At each time step, two consecutive RGB images are stacked together to form a 6-channel tensor for feature-encoding module to learn how to extract motion information and estimate poses. The sequence of output maps is then passed through the memory-propagating module to generate the relative transformation pose of each image pair. In addition, we have designed a series of data augmentation methods to avoid the overfitting problem and improve the performance of the model when facing challengeable scenarios such as high-speed or reverse driving. We evaluate the performance of our proposed approach on the KITTI Visual Odometry benchmark and Malaga 2013 Dataset. The experiments show a competitive performance of the proposed method to the state-of-the-art monocular geometric and learning methods and encourage further exploration of learning-based methods for the purpose of estimating camera ego-motion even though geometrical methods demonstrate promising results.

# Summary. An optional shortened abstract.
summary: Pubilished in *Pattern Recognition*.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S003132031930487X'
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
  caption: 'The structure of whole framework presents a mirror-like symmetric construction.'
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
