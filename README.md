# ConvMambaSR: Leveraging State-Space Models and CNNs in a Dual-Branch Architecture for Remote Sensing Imagery Super-Resolution

<div align="left">

[![paper](https://img.shields.io/badge/Remote%20Sens.%202024,%2016(17),%203254-3A7138)](https://doi.org/10.3390/rs16173254)&nbsp;
![visitors](https://visitor-badge.laobi.icu/badge?page_id=Doswin/ConvMambaSR)

</div>

## Training and Testing

Please use [BasicSR](https://github.com/XPixelGroup/BasicSR), it is an open-source image super-resolution toolbox based on PyTorch.
If you encounter any issues during use, please refer to [MambaIR](https://github.com/csguoh/MambaIR) — it is an excellent work and may provide helpful guidance.

## Citation 

If you find this work useful, please consider citing:

```bibtex
@Article{ConvMambaSR,
AUTHOR = {Zhu, Qiwei and Zhang, Guojing and Zou, Xuechao and Wang, Xiaoying and Huang, Jianqiang and Li, Xilai},
TITLE = {ConvMambaSR: Leveraging State-Space Models and CNNs in a Dual-Branch Architecture for Remote Sensing Imagery Super-Resolution},
JOURNAL = {Remote Sensing},
VOLUME = {16},
YEAR = {2024},
NUMBER = {17},
ARTICLE-NUMBER = {3254},
URL = {https://www.mdpi.com/2072-4292/16/17/3254},
ISSN = {2072-4292},
ABSTRACT = {Deep learning-based super-resolution (SR) techniques play a crucial role in enhancing the spatial resolution of images. However, remote sensing images present substantial challenges due to their diverse features, complex structures, and significant size variations in ground objects. Moreover, recovering lost details from low-resolution remote sensing images with complex and unknown degradations, such as downsampling, noise, and compression, remains a critical issue. To address these challenges, we propose ConvMambaSR, a novel super-resolution framework that integrates state-space models (SSMs) and Convolutional Neural Networks (CNNs). This framework is specifically designed to handle heterogeneous and complex ground features, as well as unknown degradations in remote sensing imagery. ConvMambaSR leverages SSMs to model global dependencies, activating more pixels in the super-resolution task. Concurrently, it employs CNNs to extract local detail features, enhancing the model’s ability to capture image textures and edges. Furthermore, we have developed a global–detail reconstruction module (GDRM) to integrate diverse levels of global and local information efficiently. We rigorously validated the proposed method on two distinct datasets, RSSCN7 and RSSRD-KQ, and benchmarked its performance against state-of-the-art SR models. Experiments show that our method achieves SOTA PSNR values of 26.06 and 24.29 on these datasets, respectively, and is visually superior, effectively addressing a variety of scenarios and significantly outperforming existing methods.},
DOI = {10.3390/rs16173254}
}
```

## Reference

Some of the codes in this repo are borrowed from:  
- [BasicSR](https://github.com/XPixelGroup/BasicSR)  
- [MambaIR](https://github.com/csguoh/MambaIR) 
- [SimAM](https://github.com/ZjjConan/SimAM)
- [SegNeXt](https://github.com/Visual-Attention-Network/SegNeXt)

Thanks to their great work.
