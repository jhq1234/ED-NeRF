# ED-NeRF: Efficient Text-Guided Editing of 3D Scene using Latent Space NeRF (ICLR 2024)

This repository contains the official pytorch implementation of [ED-NeRF](#).
<br/> <br/>
[![Project Website](https://img.shields.io/badge/Project-Website-orange)](https://jhq1234.github.io/ed-nerf.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-2312.00845-b31b1b.svg)](https://arxiv.org/abs/2310.02712)

## 📘 Abstract
<b><font color="red">ED-NeRF</font> is the NeRF editing that is based on latent space NeRF and Diffusion Models.<br>
<font color="red">ED-NeRF</font> only requires a text prompt to edit the target region of a 3D scene from NeRF.<br>
:o: Pretrained Stable Diffusion |
:o: Only latent space training |
:x: RGB NeRF training</b>

<details><summary>Full abstract</summary>


> In this work, we introduce an efficient text-guided editing NeRF with zero-shot setting using diffusion model and latent space NeRF. Recently, there has been a significant advancement in text-to-image diffusion models, leading to groundbreaking performance in 2D image generation. These advancements have been extended to 3D models, enabling the generation of novel 3D objects from textual descriptions. This has evolved into NeRF editing methods, which allow the manipulation of existing 3D objects through textual conditioning. However, existing NeRF editing techniques have faced limitations in their performance due to slow training speeds and the use of loss functions that do not adequately consider editing. To address this, here we present a novel 3D NeRF editing approach dubbed ED-NeRF by successfully embedding real-world scenes into the latent space of the latent diffusion model (LDM) through a unique refinement layer. This approach enables us to obtain a NeRF backbone that is not only faster but also more amenable to editing compared to traditional image space NeRF editing. Furthermore, we propose an improved loss function tailored for editing by migrating the delta denoising score (DDS) distillation loss, originally used in 2D image editing to the three-dimensional domain. This novel loss function surpasses the well-known score distillation sampling (SDS) loss in terms of suitability for editing purposes. Our experimental results demonstrate that ED-NeRF achieves faster editing speed while producing improved output quality compared to state-of-the-art 3D editing models.
</details>

## :memo: News
* [12/12/2023] The paper is currently under review process. We plan to make the code public once the process is done, since there could be not minor modifications.
  <br> (Apologies for the late release, but please stay tuned!)
