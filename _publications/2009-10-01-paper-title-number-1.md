---
title: "DVFL-Net: A Lightweight Distilled Video Focal Modulation Network for Spatio-Temporal Action Recognition"
collection: preprint
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-07-16
venue: 'arXiv'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.arxiv.org/abs/2507.12426'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

The landscape of video recognition has undergone a significant transformation, shifting from traditional Convolutional Neural Networks (CNNs) to Transformer-based architectures in order to achieve better accuracy. While CNNs, especially 3D variants, have excelled in capturing spatiotemporal dynamics for action recognition, recent developments in Transformer models, with their self-attention mechanisms, have proven highly effective in modeling long-range dependencies across space and time. Despite their state-of-the-art performance on prominent video recognition benchmarks, the computational demands of Transformers, particularly in processing dense video data, remain a significant hurdle. To address these challenges, we introduce a lightweight Video Focal Modulation Network named DVFL-Net, which distills the spatio-temporal knowledge from a large pre-trained teacher to nano student model, making it well-suited for on-device applications. By leveraging knowledge distillation and spatial-temporal feature extraction, our model significantly reduces computational overhead (approximately 7×) while maintaining high performance on video recognition tasks. We combine the forward Kullback–Leibler (KL) divergence and spatio-temporal focal modulation to distill the local and global spatio-temporal context from the Video-FocalNet Base (teacher) to our proposed nano VFL-Net (student) model. We extensively evaluate our DVFL-Net, both with and without forward KL divergence, against recent state-of-the-art HAR approaches on UCF50, UCF101, HMDB51, SSV2 and Kinetics-400 datasets. Further, we conducted a detailed ablation study in forward KL divergence settings and report the obtained observations. The obtained results confirm the superiority of the distilled VFL-Net (i.e., DVFL-Net) over existing methods, highlighting its optimal tradeoff between performance and computational efficiency, including reduced memory usage and lower GFLOPs, making it a highly efficient solution for HAR tasks.
