# 🌊 Underwater Image Enhancement Methods (Curated List)

This repository summarizes popular underwater image enhancement methods, categorized into:

- ✅ Physical Model-Based Methods
- 🎨 Non-Physical Model-Based Methods
- 🤖 Deep Learning-Based Methods

Each method includes a brief description, original paper link, and official code repository (if available).

---

## ✅ 1. Physical Model-Based Methods

| Method | Description | Paper | Code |
|--------|-------------|-------|------|
| **DCP** (Dark Channel Prior) | Removes haze using dark channel statistics | [He et al., 2009](https://doi.org/10.1109/CVPR.2009.5206515) | [GitHub](https://github.com/935063148/DCP_Deblurring) |
| **UDCP** (Underwater DCP) | Modified DCP for underwater images | [Drews et al., 2013](https://ieeexplore.ieee.org/document/6612951) | [GitHub](https://github.com/CSANLab/Underwater-Image-Enhancement) |
| **Red Channel** | Estimates depth via red attenuation | [Galdran et al., 2015](https://doi.org/10.1109/OCEANS.2015.7404412) | [GitHub](https://github.com/polimi-ispl/Underwater-Image-Enhancement-red-channel) |

---

## 🎨 2. Non-Physical Model-Based Methods

| Method | Description | Paper | Code |
|--------|-------------|-------|------|
| **MSRCR** | Retinex-based multi-scale enhancement | [Rahman et al.](https://www.researchgate.net/publication/228475971_Multiscale_Retinex_for_Color_Image_Enhancement) | [GitHub](https://github.com/dongb5/MSRCR-Enhancement) |
| **CLAHE** | Local histogram equalization for contrast | — | [GitHub](https://github.com/opencv/opencv/blob/master/modules/imgproc/src/clahe.cpp) |
| **Fusion-Based** | Image fusion of contrast, saturation, etc. | [Ancuti et al., 2012](https://doi.org/10.1109/TIP.2012.2195092) | [Project](http://www.ivlab.cs.ucl.ac.uk/underwater/index.html) / [GitHub](https://github.com/kanasimi/UnderwaterImageEnhancementFusion) |

---

## 🤖 3. Deep Learning-Based Methods

| Method | Description | Paper | Code |
|--------|-------------|-------|------|
| **UWCNN** | CNN trained on synthetic underwater images | [Li et al., 2019](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_Underwater_Image_Enhancement_via_Deep_Residual_Groups_CVPR_2019_paper.html) | [GitHub](https://github.com/xujingcheng/UWCNN) |
| **Water-Net** | Fusion-based deep model with attention | [Li et al., 2019](https://ieeexplore.ieee.org/document/8856158) | [GitHub](https://github.com/xujingcheng/Water-Net) |
| **U-Color** | Two-stage color correction + refinement network | [Islam et al., 2020](https://arxiv.org/abs/2007.08602) | [GitHub](https://github.com/hasibzunair/ucolor) |
| **Uformer** | Transformer-based low-light enhancement model | [Wang et al., 2022](https://arxiv.org/abs/2106.03106) | [GitHub](https://github.com/ZhendongWang6/Uformer) |

---

## 📌 Contributing

If you know other great methods, feel free to open an issue or pull request!

## ⭐ Star History

![Star History Chart](https://api.star-history.com/svg?repos=yourusername/underwater-image-enhancement-list&type=Date)


