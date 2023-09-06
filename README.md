# GIS
Graph based Identification of Sybils

We have been conducting research individually and some as a community into approaches to apply Deep Learning for Sybil Detection.  In September of 2023 a community member started a residence working with Funding the Commons on this project.
This repository is intended to track our progress, including our research and also our work to build and refine deep learning models for these purposes.  

 This is a useful survey of GNNs:  https://arxiv.org/ftp/arxiv/papers/1812/1812.08434.pdf

![overview](https://github.com/OpenDataforWeb3/GIS/assets/8564403/e9a52b79-2488-4160-abc8-e3b716717fa3)

Compared to that diagram, we ALSO want to employ transfer learning to create a foundation-like model that can be fine-tuned as needed. 

This youtube from the DeepFindr channel does an excellent job summarizing approaches to using GNNs for Fraud Detection:
https://www.youtube.com/watch?v=MZGuz-o7Fl0

We believe that the correct description of the necessary approach is:
- Temporal
- Heterogeneous
- Dynamic
- Inductive and large
- Unsupervised - for the most part
- And the data is sparse and imbalanced as there are relatively few Sybils
  
The above survey links to a list of published GNN papers having to do with fraud:

[https://github.com/thunlp/gnnpapers](https://github.com/safe-graph/graph-fraud-detection-papers)

Temporal graph networks are an area of active research, with the first workshops on the subject given at NIPS in 2022. 

https://sites.google.com/view/tglworkshop2022/home

An early 2023 survey of the field is available here:

https://towardsdatascience.com/temporal-graph-learning-in-2023-d28d1640dbf2

There is a Canadian Government funded research program using ML on Blockchains here which includes some potentially useful data sets:

https://www.chartalist.org/index.php

There are at least a couple of approaches to building useful models from the bottom up:
- TGN like models
- CAW and other walk models

And then there are approaches seeking to encode graphs in lower dimensional space - such as via Laplacian Change Point Detection.  These can be considered top down.

As of September 2023 we are working to test and deploy the Bert4Eth model, which, as the name indicates, uses a transformer approach to learn representations of users on Ethereum.
The Bert4Eth github has much more information:  https://github.com/git-disl/BERT4ETH

We would like to thank Funding the Commons for their support and the authors of the Bert4Eth paper who have been very kind in providing us with some initial guidance.  

We welcome participation of all sorts.  We will need to KYC any collaborators who access our lists of Sybils which were gathered carefully by ourselves and others including Gitcoin. 
