## [Mitchell Bosley](http://mbosley.github.io/), [Saki Kuzushima](https://ksaki.github.io/), [Ted Enamorado](https://www.tedenamorado.com/), and Yuki Shiraito. "Improving Probabilistic Models in Text Classification via Active Learning" _American Political Science Review_ (Conditionally accepted).

- [Manuscript](./files/active.pdf)

- [Supplementary Information](./files/active_si.pdf)

- [R package "activeText"](https://github.com/activetext/activeText)

- [arXiv](http://arxiv.org/abs/2202.02629)

## Abstract
Social scientists often classify text documents to use the resulting labels as an outcome or a predictor in empirical research. Automated text classification has become a standard tool, since it requires less human coding. However, scholars still need many human-labeled documents to train automated classifiers. To reduce labeling costs, we propose a new algorithm for text classification that combines a probabilistic model with active learning. The probabilistic model uses both labeled and unlabeled data, and active learning concentrates labeling efforts on difficult documents to classify. Our validation study shows that the classification performance of our algorithm is comparable to state-of-the-art methods at a fraction of the computational cost. Moreover, we replicate two recently published articles and reach the same substantive conclusions with only a small proportion of the original labeled data used in those studies. We provide _activeText_, an open-source software to implement our method.
