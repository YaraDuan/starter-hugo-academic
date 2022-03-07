---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DisARM: Displacement Aware Relation Module for 3D Detection"
authors: 
- admin
- Chenyang Zhu
- Yuqing Lan
- Renjiao Yi
- Xinwang Liu
- Kai Xu

date: 2022-03-07T20:14:04+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-07T20:14:04+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "CVPR2022"
publication_short: ""

abstract: "We introduce Displacement Aware Relation Module (DisARM), a novel neural network module for enhancing the performance of 3D object detection in point cloud scenes. The core idea of our method is that contextual information is critical to tell the difference when the instance geometry is incomplete or featureless. We find that relations between proposals provides a good representation to describe the context. However, adopting relations between all the object or patch proposals for detection is inefficient, and an imbalanced combination of local and global relations
brings extra noise that could mislead the training. Rather than working with all relations, we found that training with relations only between the most representative ones, or anchors, can significantly boost the detection performance. A good anchor should be semantic-aware with no ambiguity and independent with other anchors as well. To find the anchors, we first perform a preliminary relation anchor module with an objectness-aware sampling approach and then devise a displacement based module for weighing the relation importance for a better utilization of contextual information. This light-weight relation module leads to significantly higher accuracy of object instance detection when being plugged into the state-of-the-art detectors. Evaluations on the public benchmarks of real-world scenes show that our method achieves the state-of-the-art performance on both SUN RGB-D and ScanNet V2."

# Summary. An optional shortened abstract.
summary: "CVPR 2022"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/pdf/2203.01152.pdf'
url_code: 'https://github.com/YaraDuan/DisARM'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
