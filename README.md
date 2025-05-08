# AudioCLIP Explained

This repository contains a single Jupyter notebook that serves as a concise, blog-style walkthrough of the **AudioCLIP** model — a powerful extension of the CLIP architecture to support **audio, text, and image** modalities in a unified framework.

The notebook covers:

- A clear explanation of the **AudioCLIP architecture**, including CLIP and ESResNeXt components
- How **contrastive learning** enables cross-modal alignment
- An overview of the **trainable time-frequency transformation** using complex B-spline wavelets
- Details on the **data processing and augmentation pipeline**
- A breakdown of the **loss functions**, evaluation metrics like **P@1**, **R@1**, and **mAP**
- Analysis and summaries of key **results tables** from the original paper
- A readable **conclusion and reference section**

## Reference

The notebook is based on the original paper:

> Guzhov, A., Raue, F., Hees, J., Dengel, A.  
> *AudioCLIP: Extending CLIP to Image, Text and Audio*  
> arXiv:2106.13043v1 (2021)
