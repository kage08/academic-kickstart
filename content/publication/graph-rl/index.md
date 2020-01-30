---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Influence maximization in unknown social networks: Learning Policies for Effective Graph Sampling"
authors: [admin, "Priyesh Vijayan", "Bryan Wilder", "Balaraman Ravindran", "Milind Tambe"]
date: 2020-05-30T23:24:32+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-30T23:24:32+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Autonomous Agents and Multiagent Systems 2020"
publication_short: "AAMAS 2020"

abstract: "A serious challenge when finding influential actors in real-world social networks is the lack of knowledge about the structure of the underlying network. Current state-of-the-art methods rely on hand-crafted sampling algorithms; these methods sample nodes and their neighbours in a carefully constructed order and choose opinion leaders from this discovered network to maximize influence spread in the (unknown) complete network. In this work, we propose a reinforcement learning framework for network discovery that automatically learns useful node and graph representations that encode important structural properties of the network. At training time, the method identifies portions of the network such that the nodes selected from this sampled subgraph can effectively influence nodes in the complete network. The realization of such transferable network structure based adaptable policies is attributed to the meticulous design of the framework that encodes relevant node and graph signatures driven by an appropriate reward scheme. We experiment with real-world social networks from four different domains and show that the policies learned by our RL agent provide a 10-36% improvement over the current state-of-the-art method. "

# Summary. An optional shortened abstract.
summary: "We propose a reinforcement learning framework for network discovery that automatically learns useful node and graph representations that encode important structural properties of the network. At training time, the method identifies portions of the network such that the nodes selected from this sampled subgraph can effectively influence nodes in the complete network. We experiment with real-world social networks from four different domains and show that the policies learned by our RL agent provide a 10-36% improvement over the current state-of-the-art method."

tags: ["DQN", "GCN", "Deepwalk", "Social Networks"]
categories: ["Reinforcement Learning", "Graph Representation Learning", "Deep Learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/1907.11625"
url_code: "https://github.com/kage08/graph_sample_rl"
url_dataset:
url_poster: "files/posters/InflMax.pdf"
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Training Pipeline"
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
