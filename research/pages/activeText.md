## [Mitchell Bosley](http://mbosley.github.io/), [Saki Kuzushima](https://ksaki.github.io/), [Ted Enamorado](https://www.tedenamorado.com/), and Yuki Shiraito. "Improving Probabilistic Models in Text Classification via Active Learning" _American Political Science Review_ (Forthcoming).

- [Manuscript](../files/active.pdf)

- [Supplementary Information](../files/active_si.pdf)

- [Supplementary Information (Dataverse-only)](../files/active_si_sim.pdf)

- [R package "activeText"](https://github.com/activetext/activeText)

- [arXiv](http://arxiv.org/abs/2202.02629)

## Abstract
Social scientists often classify text documents to use the resulting labels as an outcome or a predictor in empirical research.
Automated text classification has become a standard tool, since it requires less human coding.
However, scholars still need many human-labeled documents for training.
To reduce labeling costs, we propose a new algorithm for text classification that combines a probabilistic model with active learning.
The probabilistic model uses both labeled and unlabeled data, and active learning concentrates labeling efforts on difficult documents to classify.
Our validation study shows that with few labeled data the classification performance of our algorithm is comparable to state-of-the-art methods at a fraction of the computational cost.
We replicate the results of two published articles with only a small fraction of the original labeled data used in those studies, and provide open-source software to implement our method.
