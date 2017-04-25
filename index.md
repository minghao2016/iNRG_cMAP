---
layout: default
title: Home
---

# iNRG_cMap: iterative NetwoRk Guided connectivity Mapping

![alt tag](http://www.ebi.ac.uk/~iorio/PLoS_ONE_Submission/home_files/Screen%20Shot%202014-05-01%20at%201.58.48%20AM.jpg)

Drug repositioning, whereby a drug prescribed to treat a given disease is approved to treat a new one, has
gained increased interest in recent years. Various methods attempt to identify repositioning opportunities
by analysing signatures of changes in gene expression induced by drugs, generally as ‘black-box’ tools to
link compounds to transcriptional states in an unbiased manner. We have conceived iNRG_cMap (iterative NetwoRk Guided connectivity Mapping) a strategy that refines these unbiased approaches by making use of prior knowledge about the analysed compounds to compute refined transcriptional signatures of drug response. In this way spurious effects due to non-relevant
secondary drug effects are disentangled and the predictive power of the resulting refined signatures
enhanced. In Iorio et al. (PLoS ONE 2015) we present a proof of principle of this strategy in combination with experimental outcome validations through high-resolution cell biology assays. With this approach we predict that glipizide and
splitomicin perturb microtubules in human cells. In agreement, we find that these two drugs reduce
interphase microtubule growth rates and transiently increase the percentage of mitotic cells. Finally, we
have further verified our findings through the signature reversion paradigm (recently proposed in
computational drug-discovery) on independent dataset derived from a large drug screening study.
This repository contains all the code and data objects needed to reproduce the results presented in our paper and to run iNRG_cMap on user-defined cases.

Give a look to the [manual](https://github.com/francescojm/iNRG_cMap/blob/master/Manual.pdf) to start

### Citation:
Iorio, F., Shrestha, R.L., Levin, N., Boilot, V., Garnett, M.J., Saez-Rodriguez, J. and Draviam, V.M., 2015. **A semi-supervised approach for refining transcriptional signatures of drug response and repositioning predictions.** _PloS one_, 10(10), p.e0139446. [paper](https://doi.org/10.1371/journal.pone.0139446)

