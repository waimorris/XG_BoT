This is a PyTorch implementation of the paper [XG-BoT](https://arxiv.org/pdf/2207.09088.pdf).

Abstract

In this paper, we propose XG-BoT, an explainable deep graph neural network model for botnet node detection. The proposed model comprises a botnet detector and an explainer for automatic forensics. The XG-BoT detector can effectively detect malicious botnet nodes in large-scale networks. Specifically, it utilizes a grouped reversible residual connection with a graph isomorphism network to learn expressive node representations from botnet communication graphs. The explainer, based on the GNNExplainer and saliency map in XG-BoT, can perform automatic network forensics by highlighting suspicious network flows and related botnet nodes. We evaluated XG-BoT using real-world, large-scale botnet network graph datasets. Overall, XG-BoT outperforms state-of-the-art approaches in terms of key evaluation metrics. Additionally, we demonstrate that the XG-BoT explainers can generate useful explanations for automatic network forensics.



## Prerequisites

- [Pytorch](http://pytorch.org/)
- [DGL](https://www.dgl.ai/)
- [PyoD](https://pyod.readthedocs.io/en/latest/)


### If you think this work is helpful, please cite
```latex
@article{lo2023xg,
  title={XG-BoT: An explainable deep graph neural network for botnet detection and forensics},
  author={Lo, Wai Weng and Kulatilleke, Gayan and Sarhan, Mohanad and Layeghy, Siamak and Portmann, Marius},
  journal={Internet of Things},
  volume={22},
  pages={100747},
  year={2023},
  publisher={Elsevier}
}
```
