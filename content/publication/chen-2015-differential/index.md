---
title: "Differential Topic Models"
date: 2015-01-01
publishDate: 2019-12-29T23:55:04.500011Z
authors: ["Changyou Chen", "Wray Buntine", "Nan Ding", "Lexing Xie", "Lan Du"]
publication_types: ["2"]
abstract: "In applications we may want to compare different document collections: they could have shared content but also different and unique aspects in particular collections. This task has been called comparative text mining or cross-collection modeling. We present a differential topic model for this application that models both topic differences and similarities. For this we use hierarchical Bayesian nonparametric models. Moreover, we found it was important to properly model power-law phenomena in topic-word distributions and thus we used the full Pitman-Yor process rather than just a Dirichlet process. Furthermore, we propose the transformed Pitman-Yor process (TPYP) to incorporate prior knowledge such as vocabulary variations in different collections into the model. To deal with the non-conjugate issue between model prior and likelihood in the TPYP, we thus propose an efficient sampling algorithm using a data augmentation technique based on the multinomial theorem. Experimental results show the model discovers interesting aspects of different collections. We also show the proposed MCMC based algorithm achieves a dramatically reduced test perplexity compared to some existing topic models. Finally, we show our model outperforms the state-of-the-art for document classification/ideology prediction on a number of text collections."
featured: false
publication: "*IEEE Transactions on Pattern Analysis and Machine Intelligence*"
doi: "10.1109/TPAMI.2014.2313127"
---

