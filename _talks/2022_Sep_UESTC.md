---
title: "Privacy-Preserving Multimodal Sentiment Analysis"
collection: talks
type: "Talk"
permalink: /talks/2022_Sep_UESTC
venue: "University of Electronic Science and Technology of China"
date: 2022-09-15
location: "Chengdu Sichuan, China"
---

[Download slides here](http://honghuixuhenry.github.io/files/Talk_UESTC.pdf)

Multimodal sentiment analysis has been an indispensable fundamental component for many real applications. However, a severe threat of privacy leakage in the multimodal sentiment analysis has been overlooked by previous works. To fill this gap, we propose a Differentially Private Correlated Representation Learning (DPCRL) model to achieve privacy-preserving multimodal sentiment analysis by combining a correlated representation learning scheme with a differential privacy protection scheme. Our correlated representation learning scheme aims to achieve heterogeneous multimodal data transformation to meet the requirements of privacy-preserving multimodal sentiment analysis by learning the correlated and uncorrelated representations, where especially, a pre-determined correlation factor is employed to flexibly adjust the expected correlation among the correlated representations. The differential privacy protection scheme is used to obtain the disturbed correlated and uncorrelated representations by adding Laplace noise to for differential privacy. In particular, the correlation factor can help alleviate the side-effect of the added Laplace noise on the sentiment prediction performance. Finally, via conducting a series of real-data experiments, we validate that our proposed DPCRL model is superior to the state-of-the-arts for privacy-preserving multimodal sentiment analysis.
