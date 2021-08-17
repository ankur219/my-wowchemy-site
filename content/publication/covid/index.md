---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CT Image Synthesis Using Weakly Supervised Segmentation and Geometric Inter-Label Relations For COVID
Image Analysis"
authors: [Dwarikanath Mahapatra, Ankur Singh, Behzad Bozorgtabar]
date: 2020-07-15T12:50:11+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-15T12:50:11+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "Under Submission at MeDIA"
publication_short: ""

abstract: "While medical image segmentation is an important task for
computer aided diagnosis, the high expertise requirement for pixelwise
manual annotations makes it a challenging and time consuming task. Since
conventional data augmentations do not fully represent the underlying
distribution of the training set, the trained models have varying
performance when tested on images captured from different sources. Most
prior work on image synthesis for data augmentation ignore the
interleaved geometric relationship between different anatomical labels.
We propose improvements over previous GAN-based medical image synthesis
methods by learning the relationship between different anatomical labels.
We use a weakly supervised segmentation method to obtain pixel level
semantic label map of images which is used learn the intrinsic
relationship of geometry and shape across semantic labels. Latent space
variable sampling results in diverse generated images from a base image
and improves robustness. We use the synthetic images from our method to
train networks for segmenting COVID-19 infected areas from lung CT
images. The proposed method outperforms state-of-the-art segmentation
methods on a public dataset. Ablation studies also demonstrate benefits
of integrating geometry and diversity."

# Summary. An optional shortened abstract.
summary: ""

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

url_pdf: https://drive.google.com/file/d/1Jl8uORdcbuxNFf-lLPJkJZquhzVcvo-x/view
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
