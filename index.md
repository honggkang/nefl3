---
title: Home
layout: home
---
## NeFL: Nested Model Scaling for Federated Learning with System Heterogeneous Clients

<p style="text-align: center;">

[Honggu Kang], [Seohyeon Cha], [Jinwoo Shin], Jongmyeong Lee, [Joonhyuk Kang]

KAIST
</p>

### TL;DR
NeFL divides a model into submodels by widthwise or/and depthwise and aggregate the knowledge of submodels.

### Abstract
  Federated learning (FL) is a promising approach in distributed learning keeping privacy.
  However, during the training pipeline of FL, slow or incapable clients (i.e., stragglers) slow down the total training time and degrade performance. To mitigate the impact of stragglers, system heterogeneity, including heterogeneous computing and network bandwidth, has been addressed.
  Previous studies tackle the system heterogeneity by splitting a model into submodels, but with less degree-of-freedom in terms of model architecture. We propose {\it nested federated learning (NeFL)}, a generalized framework that efficiently divides a model into submodels using both depthwise and widthwise scaling. NeFL is implemented by interpreting forward propagation of models as solving ordinary differential equations (ODEs) with adaptive step sizes. To address the {\it inconsistency} that arises when training multiple submodels of different architecture, we decouple a few parameters from parameters being trained for each submodel.
  NeFL enables resource-constrained clients to effectively join the FL pipeline and the model to be trained with a larger amount of data. Through a series of experiments, we demonstrate that NeFL leads to significant performance gains, especially for the worst-case submodel.
  Furthermore, we demonstrate NeFL aligns with recent studies in FL, regarding pre-trained models of FL and the statistical heterogeneity.


----
[Honggu Kang]: https://honggkang.github.io/about/
[Seohyeon Cha]: https://seohyeon-cha.github.io/
[Jinwoo Shin]: https://alinlab.kaist.ac.kr/shin.html
[Joonhyuk Kang]: https://artlab.kaist.ac.kr/bbs/board.php?bo_table=sub1_1
