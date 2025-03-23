<!--
 * @Descripttion: 该模块主要实现的功能是：
 * @version: 1.0
 * @Author: 强虎
 * @Date: 2025-03-23 10:04:54
 * @LastEditors: 强虎
 * @LastEditTime: 2025-03-23 19:52:23
 * Copyright (c) 2025 by ${git_name_email}, All Rights Reserved. 
 * 所有权属于四川大学电器工程学院PMCIRI
-->
# 🌊 Underwater Image Enhancement Methods (Curated List)

This repository summarizes popular underwater image enhancement methods, categorized into:

- ✅ Physical Model-Based Methods
- 🎨 Non-Physical Model-Based Methods
- 🤖 Deep Learning-Based Methods

Each method includes a brief description, original paper link, and official code repository (if available).

---

## ✅ 1. Physical Model-Based Methods

| Method |Journal    | Paper | Code |
|--------|-----------|------|------|
| **DCP** (Single Image Haze Removal Using Dark Channel Prior)|IEEE Transactions on Pattern Analysis and Machine Intelligence |[He et al., 2011]([10.1109/TPAMI.2010.168](https://ieeexplore.ieee.org/abstract/document/5567108)) | [GitHub](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration/tree/master/Underwater%20Image%20Color%20Restoration/DCP) |
| **UDCP** (Transmission Estimation in Underwater Single Images) | IEEE International Conference on Computer Vision Workshops|[Drews et al., 2013](https://ieeexplore.ieee.org/document/6755982) | [GitHub](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration/tree/master/Underwater%20Image%20Color%20Restoration/UDCP) |
| **ULAP** (A Rapid Scene Depth Estimation Model Based on Underwater Light Attenuation Prior for Underwater Image Restoration)| Advances in Multimedia Information Processing–PCM|[Song et al., 2018](https://link.springer.com/chapter/10.1007/978-3-030-00776-8_62) | [GitHub](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration/tree/master/Underwater%20Image%20Color%20Restoration/ULAP) |

---

## 🎨 2. Non-Physical Model-Based Methods

| Method | Journal | Paper | Code |
|--------|-------|-------|------|
| **Fusion-Based** (Enhancing underwater images and videos by fusion) | IEEE conference on computer vision and pattern recognition|[Ancuti et al., 2012](https://ieeexplore.ieee.org/document/6247661) | [GitHub](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration/tree/master/Underwater%20Image%20Enhancement/Fusion-Matlab) |
|**ACDC**(Underwater Image Enhancement by Attenuated Color Channel Correction and Detail Preserved Contrast Enhancement)|IEEE Journal of Oceanic Engineering|[Zhang et al., 2022](https://ieeexplore.ieee.org/document/9744022)|[Github](https://github.com/Li-Chongyi/JOE2021_ACDC)|
|**ACCE-D**(Enhancing underwater image via adaptive color and contrast enhancement, and denoising)|Engineering Applications of Artificial Intelligence|[Li et al., 2022](https://www.sciencedirect.com/science/article/abs/pii/S0952197622000549)|[Github](https://github.com/Hou-Guojia/ACCE-D)|


---

## 🤖 3. Deep Learning-Based Methods

| Method | Journal |Paper | Code |
|--------|-------|-------|------|
| **UWCNN**(Underwater Scene Prior Inspired Deep Underwater Image and Video Enhancement) | Pattern recognition|[Li et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S0031320319303401) | [GitHub](https://li-chongyi.github.io/proj_underwater_image_synthesis.html) |
| **Water-Net**(An Underwater Image Enhancement Benchmark Dataset and Beyond)|IEEE transactions on image processing| [Li et al., 2019](https://ieeexplore.ieee.org/document/8917818) | [GitHub](https://github.com/Li-Chongyi/Water-Net_Code) |
| **FUnIE-GAN** ( Fast Underwater Image Enhancement for Improved Visual Perception)|IEEE Robotics and Automation Letters|[Islam et al., 2020](https://ieeexplore.ieee.org/document/9001231)|[GitHub](https://github.com/xahidbuffon/funie-gan)|
| **U-Color**(Underwater Image Enhancement via Medium Transmission-Guided Multi-Color Space Embedding) | IEEE Transactions on Image Processing|[Li et al., 2021](https://ieeexplore.ieee.org/document/9426457) | [GitHub](https://github.com/Li-Chongyi/Ucolor) |
|**Shallow-UWnet**(Shallow-UWnet : Compressed Model for Underwater Image Enhancement)|AAAI Conference on Artificial Intelligence|[Naik et al., 2021](https://arxiv.org/abs/2101.02073)|[Github](https://github.com/mkartik/Shallow-UWnet)|
|**TCTL**(TCTL-Net: Template-Free Color Transfer Learning for Self-Attention Driven Underwater Image Enhancement)|IEEE Transactions on Circuits and Systems for Video Technology|[Li et al., 2023](https://ieeexplore.ieee.org/document/10298280)|[Github](https://ieeexplore.ieee.org/document/10298280)|
|**UIE-FSMC**(UIE-FSMC: Underwater Image Enhancement Based on Few-Shot Learning and Multi-Color Space)|IEEE Transactions on Circuits and Systems for Video Technology|[Qiao et al., 2023](https://ieeexplore.ieee.org/document/10064015)|None|
|**P2CNet**(Deep Color Compensation for Generalized Underwater Image Enhancement)|IEEE Transactions on Circuits and Systems for Video Technology|[Rao et al., 2023](https://ieeexplore.ieee.org/document/10220126)|[Github](https://github.com/Ray2OUC/P2CNet)|
|**LightEnhanceNet** (LiteEnhanceNet: A lightweight network for real-time single underwater image enhancement)|Expert Systems with Applications|[Zhao et al., 2024](https://www.sciencedirect.com/science/article/abs/pii/S0957417423030488)|[GitHub](https://github.com/zhangsong1213/LiteEnhanceNet)|
|**HCLR-Net** (HCLR-Net: Hybrid Contrastive Learning Regularization with Locally Randomized Perturbation for Underwater Image Enhancement)| International Journal of Computer Vision|[Zhou et al., 2024](https://link.springer.com/article/10.1007/s11263-024-01987-y)|[GitHub](https://github.com/zhoujingchun03/HCLR-Net)|
|**PAFPT**(Progressive aggregator with feature prompted transformer for underwater image enhancement)|Expert Systems with Applications|[Yang et al., 2025](https://www.sciencedirect.com/science/article/abs/pii/S0957417424024060)|None|
|**DNnet**(DNnet: A lightweight network for real-time 4K underwater image enhancement using dynamic range and average normalization)|Expert Systems with Applications|[Cao et al., 2025](https://www.sciencedirect.com/science/article/abs/pii/S0957417425001836)|[Github](https://github.com/Tian-Yu-CAO/DNnet-A-Lightweight-Network-For-Real-Time-4K-Underwater-Image-Enhancement)|
|**UDnet**(Adaptive deep learning framework for robust unsupervised underwater image enhancement)|Expert Systems with Applications|[Saleh et al., 2025](https://www.sciencedirect.com/science/article/pii/S0957417424031816)|[Github](https://github.com/alzayats/UDnet)|

---

## 📌 Contributing

If you know other great methods, feel free to open an issue or pull request!

## ⭐ Star History

![Star History Chart](https://api.star-history.com/svg?repos=yourusername/underwater-image-enhancement-list&type=Date)


