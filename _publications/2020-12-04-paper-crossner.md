---
title: "CrossNER: Evaluating Cross-Domain Named Entity Recognition"
collection: publications
permalink: /publication/2020-12-04-paper-crossner
excerpt: ''
date: 2020-12-04
venue: 'AAAI-2021'
paperurl: 'https://arxiv.org/abs/2012.04373'
authors: 'Zihan Liu, Yan Xu, Tiezheng Yu, Wenliang Dai, Ziwei Ji, Samuel Cahyawijaya, Andrea Madotto, Pascale Fung'
paper: https://arxiv.org/abs/2012.04373
code: https://github.com/zliucr/CrossNER
citation: 'Liu, Z., Xu, Y., Yu, T., Dai, W., Ji, Z., Cahyawijaya, S., ... & Fung, P. (2020). CrossNER: Evaluating Cross-Domain Named Entity Recognition. arXiv preprint arXiv:2012.04373.'
show_year: true
---
Cross-domain named entity recognition (NER) models are able to cope with the scarcity issue of NER samples in target domains. However, most of the existing NER benchmarks lack domain-specialized entity types or do not focus on a certain domain, leading to a less effective cross-domain evaluation. To address these obstacles, we introduce a cross-domain NER dataset (CrossNER), a fully-labeled collection of NER data spanning over five diverse domains with specialized entity categories for different domains. Additionally, we also provide a domain-related corpus since using it to continue pre-training language models (\textit{domain-adaptive pre-training}) is effective for the domain adaptation. We then conduct comprehensive experiments to explore the effectiveness of leveraging different levels of the domain corpus and pre-training strategies to do domain-adaptive pre-training for the cross-domain task. Results show that focusing on the fractional corpus containing domain-specialized entities and utilizing a more challenging pre-training strategy in domain-adaptive pre-training are beneficial for the NER domain adaptation, and our proposed method can consistently outperform existing cross-domain NER baselines. Nevertheless, experiments also illustrate the challenge of this cross-domain NER task. We hope that our dataset and baselines will catalyze research in the NER domain adaptation area.

