# graph-rcnn.pytorch
Pytorch code for our ECCV 2018 paper ["Graph R-CNN for Scene Graph Generation"](https://arxiv.org/pdf/1808.00191.pdf)

<div style="color:#0000FF" align="center">
<img src="figures/teaser_fig.png" width="850"/>
</div>

<!-- :balloon: 2019-06-04: Okaaay, time to reimplement Graph R-CNN on pytorch 1.0 and release a new benchmark for scene graph generation. It will also integrate other models like IMP, MSDN and Neural Motif Network. Stay tuned!

:balloon: 2019-06-16: Plan is a bit delayed by ICCV rebuttal, but still on track. Stay tuned! -->

:balloon: 2019-07-04: Object detection baseline model ready.

## Introduction

This is the new implementation of scene graph generation model, including not only our own graph r-cnn, but also some other representative models including IMP, MSDN, and Neural Motif.

## Checklist

- [x] Faster R-CNN Baseline
- [ ] Scene Graph Generation Baseline
- [ ] Iterative Message Passing (IMP)
- [ ] Multi-level Scene Description Network (MSDN)
- [ ] Neural Motif
- [ ] Graph R-CNN
