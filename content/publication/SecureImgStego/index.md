---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "SecureImgStego: A Keyed Shuffling Encryption-based Deep Learning Model for Secure Image Steganography"
authors: [Trishna Chakraborty, admin, Hasan Murad, Sohrab Hossain, Shagufta Mehnaz]
date: 2021-05-17T15:01:01+06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-17T15:01:01+06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Steganography ensures secure transmission of digital messages, including image steganography where a secret image is hidden within a non-secret cover image. Deep learning-based methods in image steganography have recently gained popularity but are vulnerable to various attacks. An adversary with varying levels of access to the vanilla deep steganography model can train a surrogate model using another dataset and retrieve hidden images. Moreover, even when uncertain about the presence of hidden information, the adversary with access to the surrogate model can distinguish the carrier image from the unperturbed one. Our paper includes such attack demonstrations that confirm the inherent vulnerabilities present in deep learning-based steganography. Deep learning-based steganography lacks lossless transmission assurance, rendering sophisticated image encryption techniques unsuitable. Furthermore, key concatenation-based techniques for text data steganography fall short in the case of image data. In this paper, we introduce a simple yet effective keyed shuffling approach for encrypting secret images. We employ keyed pixel shuffling, multi-level block shuffling, and a combination of key concatenation and block shuffling, embedded within the model architecture. Our findings demonstrate that the block shuffling-based deep image steganography has negligible error overhead compared to conventional methods while providing effective security against adversaries with different levels of access to the model."

# Summary. An optional shortened abstract.
summary: "IEEE Computer and Network Security (CNS) 2023"

tags: ['deep learning', 'steganography', 'steganalysis', 'security']
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
- name: DOI
  url: https://doi.org/10.1109/CNS59707.2023.10288753
  icon_pack: fab
  icon: 

url_pdf: https://doi.org/10.1109/CNS59707.2023.10288753
url_code: https://github.com/Trishna-Chakraborty/DeepKeyStego
url_dataset:
url_poster:
url_project:
url_slides: "publication/secureimgstego/SecureImgStego_CNS2023_slide.pdf"
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
