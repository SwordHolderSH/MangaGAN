# MangGAN
MangaGAN: Unpaired Photo-to-Manga Translation Based on The Methodology of Manga Drawing
The paper "***MangaGAN: Unpaired Photo-to-Manga Translation Based on The Methodology of Manga Drawing***" has been accepted by AAAI 2021. If the paper is useful for your research, please cite
```
@inproceedings{su2021mangagan,
  title={Mangagan: Unpaired photo-to-manga translation based on the methodology of manga drawing},
  author={Su, Hao and Niu, Jianwei and Liu, Xuefeng and Li, Qingfeng and Cui, Jiahe and Wan, Ji},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={35},
  number={3},
  pages={2611--2619},
  year={2021}
}
```
## Introduction

Manga is a world popular comic form originated in Japan, which typically employs black-and-white stroke lines and geometric exaggeration to describe humans' appearances, poses, and actions. In this paper, we propose MangaGAN, the first method based on Generative Adversarial Network (GAN) for unpaired photo-to-manga translation. Inspired by the drawing process of experienced manga artists, MangaGAN generates geometric features and converts each facial region into the manga domain with a tailored multi-GANs architecture. For training MangaGAN, we collect a new data-set from a popular manga work with extensive features. To produce high-quality manga faces, we propose a structural smoothing loss to smooth stroke-lines and avoid noisy pixels, and a similarity preserving module to improve the similarity between domains of photo and manga. Extensive experiments show that MangaGAN can produce high-quality manga faces preserving both the facial similarity and manga style, and outperforms other reference methods.

## Demos
<div align=center><img src="https://github.com/SwordHolderSH/MangGAN/blob/main/outputs/image1.gif" width="500" /></div>

* The algorithm has been applied in the mobile application ***Remini***
<div align=center><img src="https://github.com/SwordHolderSH/MangGAN/blob/main/outputs/app.png" width="300" /></div>
<div align=center><img src="https://github.com/SwordHolderSH/MangGAN/blob/main/outputs/image3.gif" width="300" /></div>
