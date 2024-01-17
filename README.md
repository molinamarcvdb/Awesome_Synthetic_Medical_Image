# Awesome Synthetic Medical Image

Welcome to the Synthetic Medical Imaging Repository – a comprehensive resource hub dedicated to the fascinating and rapidly evolving field of synthetic medical imaging. This repository is a side project of my master's thesis and aims to serve as a one-stop destination for researchers, developers, and enthusiasts in the field.

## About This Repository

In this repository, you will find an extensive collection of significant literature and valuable GitHub repositories focused on synthetic medical imaging. Whether you are a seasoned researcher or a newcomer to the field, this resource is designed to provide you with a thorough understanding of current trends, methodologies, and breakthroughs in synthetic medical imaging.

Each category in this repository is meticulously curated, guiding you through the extensive field of synthetic medical imaging, from foundational concepts to the nuances of advanced modeling techniques.

## Foundational Concepts and Theoretical Background
1. [**Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision**](https://arxiv.org/abs/2310.18689)  Bobby Azad, Reza Azad, Sania Eskandari, Afshin Bozorgpour, Amirhossein Kazerouni, Islem Rekik, Dorit Merhof (2023)
2. [**A Comprehensive Survey of Deep Learning Research on Medical Image Analysis with Focus on Transfer Learning.**](https://www.sciencedirect.com/science/article/abs/pii/S0899707122002856) SEMA ATASEVER, NUH AZGINOGLU, DUYGU SINANC TERZI, RAMAZAN TERZI (2022).
3. [**Overcoming barriers to data sharing with medical image generation: a comprehensive evaluation**](https://www.nature.com/articles/s41746-021-00507-3) August DuMont Schütte, Jürgen Hetzel, Sergios Gatidis, Tobias Hepp, Benedikt Dietz, Stefan Bauer & Patrick Schwab. npj Digital Medicine volume 4, Article number: 141 (2021).
4. [**Federated learning and differential privacy for medical image analysis**](https://www.nature.com/articles/s41598-022-05539-7) Mohammed Adnan, Shivam Kalra, Jesse C. Cresswell, Graham W. Taylor & Hamid R. Tizhoosh. Scientific Reports volume 12, Article number: 1953 (2022).


## Models
### GANs
1. [**Generative Adversarial Networks**](https://arxiv.org/abs/1406.2661) Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. Submitted on 10 Jun 2014.
2. [**Hierarchical Amortized GAN for 3D High Resolution Medical Image Synthesis**](https://ieeexplore.ieee.org/abstract/document/9770375) Li Sun, Junxiang Chen, Yanwu Xu, Mingming Gong, Ke Yu, Kayhan Batmanghelich *IEEE Journal of Biomedical and Health Informatics, Volume: 26, Issue: 8*  Publisher: IEEE [[**GitHub**]](https://github.com/batmanlab/HA-GAN/tree/master)
3. [**GANs for Medical Image Synthesis: An Empirical Study.**](https://www.mdpi.com/2313-433X/9/3/69)
   Skandarani, Y., Jodoin, P.-M., & Lalande, A. (2023). *J. Imaging*, 9(3), 69. University of Bourgogne Franche-Comte, University of Sherbrooke, University Hospital of Dijon.
4. [**Medical Image Synthesis for Data Augmentation and Anonymization using Generative Adversarial Networks.**](https://arxiv.org/abs/1807.10225)
   Shin, H.-C., Tenenholtz, N. A., Rogers, J. K., Schwarz, C. G., Senjem, M. L., Gunter, J. L., Andriole, K., & Michalski, M. (2018).
5. [**StudioGAN: A Taxonomy and Benchmark of GANs for Image Synthesis**](https://arxiv.org/abs/2206.09479) Minguk Kang, Joonghyuk Shin, Jaesik Park (2022)
7. [**3D cGAN based cross-modality MR image synthesis for brain tumor segmentation**](https://ieeexplore.ieee.org/abstract/document/8363653) Biting Yu, Luping Zhou, Lei Wang, Jurgen Fripp, Pierrick Bourgeat , IEEE

### Diffusion Models
1. [**Denoising Diffusion Probabilistic Models**](https://arxiv.org/abs/2006.11239) Jonathan Ho, Ajay Jain, Pieter Abbeel. Submitted on 19 Jun 2020 (v1), last revised 16 Dec 2020 (this version, v2).
2. [**Diffusion Models in Medical Imaging: A Comprehensive Survey.**](https://www.sciencedirect.com/science/article/abs/pii/S1361841523001068) Kazerouni, A., Aghdam, E. K., Heidari, M., Azad, R., Fayyaz, M., Hacihaliloglu, I., & Merhof, D. (2023).
3. [Medical Diffusion: Denoising Diffusion Probabilistic Models for 3D Medical Image Generation](https://www.nature.com/articles/s41598-023-34341-2) Firas Khader, Gustav Mueller-Franzes, Soroosh Tayebi Arasteh, Tianyu Han, Christoph Haarburger, Maximilian Schulze-Hagen, Philipp Schad, Sandy Engelhardt, Bettina Baessler, Sebastian Foersch, Johannes Stegmaier, Christiane Kuhl, Sven Nebelung, Jakob Nikolas Kather, Daniel Truhn (2022). [Github](https://github.com/FirasGit/medicaldiffusion)
4. [**Investigating Data Memorization in 3D Latent Diffusion Models for Medical Image Synthesis.**](https://arxiv.org/abs/2307.01148) Salman Ul Hassan Dar, Arman Ghanaat, Jannik Kahmann, Isabelle Ayx, Theano Papavassiliu, Stefan O. Schoenberg, Sandy Engelhardt (2023).
5. [**Conversion of the Mayo LDCT Data to Synthetic Equivalent through the Diffusion Model for Training Denoising Networks with a Theoretically Perfect Privacy.**](https://arxiv.org/abs/2301.06604) Yongyi Shi, Ge Wang (2023).
6. [**EMIT-Diff: Enhancing Medical Image Segmentation via Text-Guided Diffusion Model.**](https://arxiv.org/abs/2310.12868) Zheyuan Zhang, Lanhong Yao, Bin Wang, Debesh Jha, Elif Keles, Alpay Medetalibeyoglu, Ulas Bagci (2023).
### Comparisons
1. [**Diffusion Probabilistic Models beat GANs on Medical Images**](https://arxiv.org/abs/2212.07501) Gustav Müller-Franzes, Jan Moritz Niehues, Firas Khader, Soroosh Tayebi Arasteh, Christoph Haarburger, Christiane Kuhl, Tianci Wang, Tianyu Han, Sven Nebelung, Jakob Nikolas Kather, Daniel Truhn [14th Dec., 2022] [arXiv, 2022]
2. [**Beware of Diffusion Models for Synthesizing Medical Images -- A Comparison with GANs in Terms of Memorizing Brain MRI and Chest X-Ray Images.**](https://arxiv.org/abs/2305.07644) Muhammad Usman Akbar, Wuhao Wang, Anders Eklund (2023).


## Open-Source Medical imaging datasets
1. [**The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions**](https://arxiv.org/abs/1803.10417) Philipp Tschandl, Cliff Rosendahl, Harald Kittler.

## Implementation Guides and Tutorials

## Contributing

We encourage contributions from all who are interested in synthetic medical imaging. If you have suggestions for additional resources, including literature, repositories, or tools, please submit a pull request or open an issue for discussion.

---

Thank you for visiting this repository. Let's drive forward the future of synthetic medical imaging together!

