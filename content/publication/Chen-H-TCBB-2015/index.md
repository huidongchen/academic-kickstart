---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DPNuc: Identifying Nucleosome Positions Based on the Dirichlet Process Mixture Model"
authors: [Huidong Chen, Jihong Guan and Shuigeng Zhou]
date: 2015-05-25
doi: "10.1109/TCBB.2015.2430350"

# Schedule page publish date (NOT publication's date).
publishDate: 2015-05-25

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Computational Biology and Bioinformatics "
publication_short: "IEEE/ACM Trans Comput Biol Bioinform"

abstract: "Nucleosomes and the free linker DNA between them assemble the chromatin. Nucleosome positioning plays an important role in gene transcription regulation, DNA replication and repair, alternative splicing, and so on. With the rapid development of ChIP-seq, it is possible to computationally detect the positions of nucleosomes on chromosomes. However, existing methods cannot provide accurate and detailed information about the detected nucleosomes, especially for the nucleosomes with complex configurations where overlaps and noise exist. Meanwhile, they usually require some prior knowledge of nucleosomes as input, such as the size or the number of the unknown nucleosomes, which may significantly influence the detection results. In this paper, we propose a novel approach DPNuc for identifying nucleosome positions based on the Dirichlet process mixture model. In our method, Markov chain Monte Carlo (MCMC) simulations are employed to determine the mixture model with no need of prior knowledge about nucleosomes. Compared with three existing methods, our approach can provide more detailed information of the detected nucleosomes and can more reasonably reveal the real configurations of the chromosomes; especially, our approach performs better in the complex overlapping situations. By mapping the detected nucleosomes to a synthetic benchmark nucleosome map and two existing benchmark nucleosome maps, it is shown that our approach achieves a better performance in identifying nucleosome positions and gets a higher F -score. Finally, we show that our approach can more reliably detect the size distribution of nucleosomes."

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

url_pdf: https://ieeexplore.ieee.org/document/7112520
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
