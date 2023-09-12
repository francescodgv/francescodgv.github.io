---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Praise the sun! I am currently a Research Associate at the University of Cambridge, working in [Pietro Lio](https://scholar.google.com/citations?user=3YrWf7EAAAAJ&hl=en&oi=ao)'s group on Geometric Deep Learning and Graph Neural Networks. Previously, I was an ML Researcher at Twitter Cortex working with 
[Michael Bronstein](https://scholar.google.co.uk/citations?user=UU3N6-UAAAAJ&hl=en). I finished my PhD in Mathematics at UCL with a [thesis](https://discovery.ucl.ac.uk/id/eprint/10133514/) on analysis of singularity formation of rotationally symmetric Ricci Flows. I am now interested in investigating Deep Learning through the lens of Geometry and Physics, with emphasis on graph structured data. 

My current lines of research include: (i) Understanding how information flows in message passing models and the associated phenomenon of over-squashing. I characterize the role played by the graph structure in the propagation of messages across "distant" nodes via local quantities such as curvature and global quantities such as access and commute time - our [first step](https://openreview.net/pdf?id=7UmjRGzp-A) in this direction got an [ICLR honorable mention](https://blog.iclr.cc/2022/04/20/announcing-the-iclr-2022-outstanding-paper-award-recipients/). A [more recent work](https://arxiv.org/abs/2302.02941) generalizes our analysis and proves that over-squashing occurs among nodes at high effective resistance. (ii) More recently, we have introduced a [novel paradigm](https://arxiv.org/abs/2306.03589) for studying the expressive power of message-passing models (on graphs and/or point clouds) that precisely depends on the ability to induce interactions (mixing) across different nodes (points). I believe this will be an important angle to investigate how deep learning architectures exchange messages and the limitations associated with a certain choice of computational graph (whether this is given to us from the data, or induced by us on set of points embedded in Euclidean space). (iii) Investigating how Graph Neural Networks "use" the underlying graph topology and to what extent we need to rely on the same input graph to exchange messages across layers. This direction falls into the field of graph-rewiring. Understanding the role played by the input topology to propagate information and whether we can in fact decouple the computational graph from the latter is also key to fully assess the potential capabilities of graph transformers, and more generally to develop new frameworks that are both expressive and more resilent to issues arising from the underlying graph topology. A [recent work](https://arxiv.org/abs/2305.08018) explores this direction introducing novel notions of delay and distance-aware skip connections to mitigate vanishing gradients issues and deal with long-range interactions. (iv) Studying Graph Neural Networks as multi-particles dynamics - [our work](https://arxiv.org/abs/2206.10991) explains how the common "channel-mixing" module can be interpreted as a pairwise potential and how by interacting with the graph Laplacian spectrum it learns to generate attractive or repulsive forces via its positive and neagtive eigenvalues respectively. 

**Contact**: fd405 (at) cam (dot) ac (dot) uk

## News

#### 2023

- August 2023: Keynote speaker at the Maths for GDL workshop, ICIAM 
- August 2023: Our work on understanding graph-convolutions through energies got accepted at TMLR
- June 2023: New paper out on characterising expressive power of message passing models through their mixing abilities
- June 2023: I'll be giving a talk in Berlin at the CECAM/Psi-k conference 
- April: Our [new framework](https://arxiv.org/abs/2305.08018) for message-passing with delay got accepted at ICML23
- April: Our [new theoretical work](https://arxiv.org/abs/2302.02941) on over-squashing got accepted at ICML23
- March: reviewer for ICML23
- February: [new paper](https://arxiv.org/abs/2302.02941) out!

#### 2022

- December: Invited panelist at LoG tutorial on Graph-rewiring and Fairness
- December: Keynote speaker at Neurips 2022 Workshop: New Frontiers on Graph Learning
- August: LoGaG reading group, invited talk
- August: MML seminar at UCLA, invited talk
- August: Stanford GNN Reading Group, invited talk
- August: I gave a long talk at the [Hammers and Nails 2022 Workshop](https://www.weizmann.ac.il/conferences/SRitp/Aug2022/) in Tel Aviv
- July: I have taught at the [First Italian School in Geometric Deep Learning](https://eapls.org/items/4007/)
- July: I have been a mentor at the [LOGML22](https://www.logml.ai/) - our project is about graph-rewiring using geometric exploration policies
- June: I have reviewed for NeurIPS 2022
- May: I have coauthored a [blogpost](https://towardsdatascience.com/neural-sheaf-diffusion-for-deep-learning-on-graphs-bfa200e6afa6) with Michael Bronstein and Cristian Bodnar on a recent about cellular sheaf theory for tackling heterophily in GNNs
- April: Our work on understanding over-squashing in GNNs through graph curvature has got an Outstanding Paper Honorable Mention at ICLR 2022!
- April: Aleksa Gordić made a [great video](https://youtu.be/zpDdvI95igc) about our [paper](https://openreview.net/pdf?id=7UmjRGzp-A) on bottlenecks and over-squashing in GNNs. This is highly recommended to anyone interested in understanding our work in quite some detail!
- March: I gave a talk at the Dagsthul seminar [Graph Embeddings: Theory meets Practice](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=22132)
- January: I have been invited to write my opinion on future perspetives of GNNs in a [blogpost](https://towardsdatascience.com/predictions-and-hopes-for-geometric-graph-ml-in-2022-aa3b8b79f5cc) authored by Michael Bronstein and Petar Veličković, featuring many prominent researchers in the field.

