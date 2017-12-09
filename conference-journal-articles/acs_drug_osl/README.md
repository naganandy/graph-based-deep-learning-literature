#  Low Data Drug Discovery with One-Shot Learning

bibtex
```
@article{DBLP:journals/corr/Altae-TranRPP16,
  author    = {Han Altae{-}Tran and
               Bharath Ramsundar and
               Aneesh S. Pappu and
               Vijay S. Pande},
  title     = {Low Data Drug Discovery with One-shot Learning},
  journal   = {CoRR},
  year      = {2016}
}
```
links
- [arXiv](https://arxiv.org/abs/1611.03199)
- [acs](http://pubs.acs.org/doi/abs/10.1021/acscentsci.6b00367)
- [code](https://github.com/deepchem/deepchem)

summary
- the authors propose a non-parametric deep learning architecture for [one-shot drug discovery applications](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic1.png?raw=true)
- the model [builds on](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic2.png?raw=true) matching nets and uses molecular [gcns](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic4.png?raw=true) ([graph convolutions](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic5.png?raw=true)) with [pooling, gathering](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic6.png?raw=true) and [IR-LSTMS](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic3.png?raw=true)
- the model [significantly improves](https://github.com/naganandy/geometric-deep-learning-literature/blob/master/conference-journal-articles/acs_drug_osl/pic7.png?raw=true) distance metric learning for low-data molecular deep learning
