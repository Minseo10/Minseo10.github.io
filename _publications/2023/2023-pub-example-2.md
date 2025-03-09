---
title:          "ToMato: Accelerating ViT via Token Merging"
date:           2023-12-05 00:01:00 +0800
selected:       false
pub:            "The Institute of Electronics and Information Engineers Conference (IEIE)"
pub_date:       "2023"
abstract: >-
  ViT(Vision Transformer) shows outstanding performance in various vision tasks by splitting images into patches and passing them through transformer blocks. However, the large model size and computational cost of ViT result in high inference latency and hindered acceleration. To accelerate ViT efficiently, we introduce ToMato(Token Merging at Once), a simple framework that recursively merges tokens by comparing similarity to adjacent tokens at the first transformer block. Applying the ToMato to DeiTbase model, we find that this reduces latency by 22.19% while maintaining high Top-1 accuracy of 80.14%. 

cover:          /assets/images/covers/tomato.png
authors:
  - Sooyoung Kwon*
  - Minseo Kwon*
  - Hyojin Kim*
  - Jahyeong Sim#
links:
  Paper: https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11701260
  Code: https://github.com/Transformer04/ToMato
---
