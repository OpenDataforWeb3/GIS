# GIS
Graph based Identification of Sybils

Much more about our intended approach can be found at in this write-up: https://docs.google.com/document/d/1aliAgjct6dZ5ZZdBEwbykJJRgxyMhx_d8Bd99WKLJAg/edit?usp=sharing

And this is a useful survey of GNNs:  https://arxiv.org/ftp/arxiv/papers/1812/1812.08434.pdf

![overview](https://github.com/OpenDataforWeb3/GIS/assets/8564403/e9a52b79-2488-4160-abc8-e3b716717fa3)

Compared to that diagram, we ALSO want to employ transfer learning to create a foundation-like model that can be fine-tuned as needed.  The foundation model should have extremely expressive embeddings so that it best informs the pattern or motif final model.

We believe that the correct description of the necessary GNN is:
- Temporal
- Heterogeneous
- Dynamic
- Inductive and large
- Unsupervised - for the most part
- And the data is sparse and imbalanced as there are relatively few Sybils
  
The above survey links to a list of published papers that was updated until last year that can be useful as well:

https://github.com/thunlp/gnnpapers

Temporal graph networks are an area of active research, with the first workshops on the subject given at NIPS in 2022. 

https://sites.google.com/view/tglworkshop2022/home

An early 2023 survey of the field is available here:

https://towardsdatascience.com/temporal-graph-learning-in-2023-d28d1640dbf2

There is a Canadian Government funded research program using ML on Blockchains here which includes some potentially useful data sets:

https://www.chartalist.org/index.php
