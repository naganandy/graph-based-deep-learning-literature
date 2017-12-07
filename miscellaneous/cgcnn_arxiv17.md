#  Crystal Graph Convolutional Neural Networks for Accurate and Interpretable Prediction of Material Properties

citation
```
@article{cgcnn_arxiv17,
  author    = {Xie, Tian and C. Grossman, Jeffrey},
  title     = {Crystal Graph Convolutional Neural Networks for Accurate and Interpretable Prediction of Material Properties},
  journal   = {arXiv preprint},
  year      = {2017}
}
```

links
- [arXiv](https://arxiv.org/abs/1710.10324)

authors
- Tian Xie, Massachusetts Institute of Technology
- Jeffrey C. Grossman, Massachusetts Institute of Technology

summary

- traditional ML methods for materials design require manually constructed feature vectors/complex transformations
- authors [construct](https://i.imgur.com/wxApCY2.png) crystal graphs and use [cnns](https://s17.postimg.org/rz77ahzyn/di2.png) on these graphs ([nodes, edges](https://s17.postimg.org/e5iulnx5b/di3.png) have [features](https://s17.postimg.org/c2d0rbmlr/di4.png)) to learn [material properties](https://s17.postimg.org/e6xdskvzz/di5.png)
- the method achieves same accuracy as [DFT](https://en.wikipedia.org/wiki/Density_functional_theory) (ground truth) for properties of crystals, the framework is interpretable too
