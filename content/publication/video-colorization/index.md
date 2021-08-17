---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Video Colorization using CNNs and Keyframes extraction: An application in saving bandwidth"
authors: [Ankur Singh, Anurag Chanani, Harish Karnick]
date: 2019-07-15T11:03:49+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-15T13:03:49+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "CVIP"
publication_short: ""

abstract: "In this paper, we tackle the problem of colorization of grayscale videos to reduce bandwidth usage. For this task, we use some colored keyframes as reference images from the colored version of the grayscale video. We propose a model that extracts keyframes from a colored video and trains a Convolutional Neural Network from scratch on these colored frames. Through the extracted keyframes we get a good knowledge of the colors that have been used in the video which helps us in colorizing the grayscale version of the video efficiently. An application of the technique that we propose in this paper, is in saving bandwidth while sending raw colored videos that haven't gone through any compression. A raw colored video takes up around three times more memory size than its grayscale version. We can exploit this fact and send a grayscale video along with out trained model instead of a colored video. Later on, in this paper we show how this technique can help to save bandwidth usage to upto three times while transmitting raw colored videos"

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

url_pdf: https://drive.google.com/file/d/1sD0eEzjp1HC5A9mEEF-bR_1c5gDz-vVN/view
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
