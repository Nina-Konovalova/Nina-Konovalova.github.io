---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Nina Konovalova, a Research Engineer currently working at AIRI. Over the past 4 years, I've been working in machine learning and deep learning area, specializing in Computer Vision, with a particular focus on generative models and 3D Computer Vision algorithms. Additionally I and currently working as academic lead in [Deep Learning School](https://dls.samcs.ru/).

## Research Interests
My research interests are focused on the exploration of generative models, with a special emphasis on diffusion models and their application, in particular controllable generation, editing and interpretibility.

## Papers

<details>
  <summary><strong><a href="https://arxiv.org/abs/2406.15020"  target="_blank">A3D: Does Diffusion Dream about 3D Alignment?</a></strong> -- ICLR 2025 accepted</summary>
  <p>This work is focused on text-to-3D aligned objects generation. Given a set of text prompts, we aim to generate a collection of objects with semantically corresponding parts aligned across them. In order to achieve the alignment of the corresponding parts of the generated objects, we propose to embed these objects into a common latent space and optimize the continuous transitions between these objects. We enforce two kinds of properties of these transitions: smoothness of the transition and plausibility of the intermediate objects along the transition. We demonstrate that both of these properties are essential for good alignment. We provide several practical scenarios that benefit from alignment between the objects, including 3D editing and object hybridization, and experimentally demonstrate the effectiveness of our method.</p>
</details>

<details>
  <summary><strong><a href="https://arxiv.org/abs/2409.15010"  target="_blank">DepthART: Monocular Depth Estimation as Autoregressive Refinement Task</a></strong> -- IJCAI 2025 accepted</summary>
  <p> Following the visual autoregressive modeling paradigm, we introduce the first autoregressive depth estimation model based on the visual autoregressive transformer. Our primary contribution is DepthART – a novel training method formulated as Depth Autoregressive Refinement Task. Unlike the original VAR training procedure, which employs static targets,our method utilizes a dynamic target formulation that enables model self-refinement and incorporates multi-modal guidance during training. Specifically, we use model predictions as inputs instead of ground truth token maps during training, framing the objective as residual minimization. Our experiments demonstrate that the proposed training approach significantly outperforms visual autoregressive modeling via next-scale prediction in the depth estimation task. The Visual Autoregressive Transformer trained with our approach on Hypersim achieves superior results on a set of unseen benchmarks compared to other generative and discriminative baselines.</p>
</details>

<details>
  <summary><strong><a href="https://arxiv.org/abs/2507.02321"  target="_blank">Heeding the Inner Voice: Aligning ControlNet Training via Intermediate Features Feedback</a></strong></summary>
  <p>We suggest InnerControl-- a training strategy that enforces spatial consistency across all diffusion steps. Specifically, we train lightweight control prediction probes — small convolutional networks — to reconstruct input control signals (e.g., edges, depth) from intermediate UNet features at every denoising step. We prove the efficiency of such models to extract signals even from very noisy latents and utilize these models to generate pseudo ground truth controls during training. Suggested approach enables alignment loss that minimizes the difference between predicted and target condition throughout the whole diffusion process. Our experiments demonstrate that our method improves control alignment and fidelity of generation. By integrating this loss with established training techniques (e.g., ControlNet++), we achieve high performance across different condition methods such as edge and depth conditions.</p>
</details>




## Other Interests
Beyond my main work, I've been actively involved in educational projects. I have been working as a math teacher in different schools, creating lectures and seminars for Machine Learning and Computer Vision. Additionally, I have a [channel](t.me/reading_ai/) where I share insights into state-of-the-art technologies in AI. 
