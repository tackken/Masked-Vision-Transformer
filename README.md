# Masked Vision Transformer for Predicting Macrovascular Invasion in Hepatocellular Carcinoma: Graph-based Association Analysis of Attention

We provides the implementation of a Masked Vision Transformer (ViT) framework for predicting macrovascular invasion (MVI) in hepatocellular carcinoma (HCC). We further propose a graph-based analysis method to interpret the spatial association of attention.

Project Page | Paper

- Dataset: [TCIA HCC-TACE-Seg](https://wiki.cancerimagingarchive.net/display/Public/HCC-TACE-Seg](https://www.cancerimagingarchive.net/collection/hcc-tace-seg/))
- Baseline Model: [ViT (Timm ver 1.0.12)](https://github.com/huggingface/pytorch-image-models/blob/main/timm/models/vision_transformer.py)

## Model Architecture

<img width="1073" alt="Model Architecture" src="https://github.com/user-attachments/assets/f4acd3e1-a788-41d2-9fdd-f31a9bb47e8c" />

---

## Graph-based Association Analysis

<img width="1142" alt="Attention Graph" src="https://github.com/user-attachments/assets/23d4589f-cce2-415b-9be7-ee1a15ff491a" />

<h3 align="center">
  We identified the attention heads that contributed to decision-making of the ViT model based on the morphological features of the liver.
</h3>
---

## Demo Video

<video src="https://github.com/user-attachments/assets/db8357e4-c19c-4484-8b91-5d21d9dd99d5" autoplay loop muted playsinline width="700">
Your browser does not support the video tag.
</video>

Code will be public available soon.

