# Awesome Neural Radiance Fields [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome neural radiance fields papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

**If you are interested in adding your paper, feel free to submit a pull request folloing the instruction here.**

## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Talks](#talks)

## Survey
- [NeRF Explosion 2020](https://dellaert.github.io/NeRF/), Dellaert et al.

## Papers

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L204-L208) <!---Mildenhall20eccv_nerf-->
- [NeRF++: Analyzing and Improving Neural Radiance Fields](https://arxiv.org/abs/2010.07492), Zhang et al., Arxiv 2020 | [github](https://github.com/Kai-46/nerfplusplus) | [bibtex](./NeRF-and-Beyond.bib#L398-L403) <!---Zhang20arxiv_nerf++-->
- [DeRF: Decomposed Radiance Fields](https://arxiv.org/abs/2011.12490), Rebain et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L252-L257) <!---Rebain20arxiv_derf-->
- [NeRD: Neural Reflectance Decomposition from Image Collections](https://markboss.me/publication/2021-nerd/), Boss et al., Arxiv 2020 | [github](https://github.com/cgtuebingen/NeRD-Neural-Reflectance-Decomposition) | [bibtex](./NeRF-and-Beyond.bib#L27-L32) <!---Boss20arxiv_NeRD-->

#### Faster Inference
- [Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., NeurIPS 2020 | [github](https://github.com/facebookresearch/NSVF) | [bibtex](./NeRF-and-Beyond.bib#L168-L173) <!---liu20neurips_sparse_nerf-->
- [AutoInt: Automatic Integration for Fast Neural Volume Rendering](https://arxiv.org/abs/2012.01714), Lindell et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L154-L159) <!---Lindell20arxiv_AutoInt-->

#### Unconstrained Images
- [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L183-L188) <!---MartinBrualla20arxiv_nerfw-->

#### Deformable
- [Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L238-L243) <!---Park20arxiv_nerfies-->
- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://www.albertpumarola.com/research/D-NeRF/index.html), Pumarola et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L245-L250) <!---Pumarola20arxiv_D_NeRF-->
- [Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://gafniguy.github.io/4D-Facial-Avatars/), Gafni et al., Arxiv 2020 | [bibtex](./citations/4d-avatar.txt) <!---Gafni20arxiv_DNRF-->
- [Non-Rigid Neural Radiance Fields: Reconstruction and Novel View Synthesis of a Deforming Scene from Monocular Video](https://gvv.mpi-inf.mpg.de/projects/nonrigid_nerf/), Tretschk et al., Arxiv 2020 | [github](https://github.com/facebookresearch/nonrigid_nerf) | [bibtex](citations/nr-nerf.txt) <!---tretschk20arxiv_nr_nerf-->

#### Video
- [Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes](http://www.cs.cornell.edu/~zl548/NSFF/), Li et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L147-L152) <!---Li20arxiv_nsff-->
- [Space-time Neural Irradiance Fields for Free-Viewpoint Video](https://video-nerf.github.io/), Xian et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L357-L362) <!---Xian20arxiv_stnif-->
- [Neural Radiance Flow for 4D View Synthesis and Video Processing](https://yilundu.github.io/nerflow/), Du et al., Arxiv 2020 | [bibtex](citations/nerflow.txt) <!---du20arxiv_nerflow-->
- [Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans](https://zju3dv.github.io/neuralbody/), Peng et al., Arxiv 2020 | [bibtex](citations/neuralbody.txt) <!---Peng20arxiv_neuralbody-->

#### Generalization
- [GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis](https://arxiv.org/abs/2007.02442), Schwarz et al., NeurIPS 2020 | [github](https://github.com/autonomousvision/graf)  | [bibtex](./NeRF-and-Beyond.bib#L295-L300) <!---Schwarz20arxiv_graf-->
- [GRF: Learning a General Radiance Field for 3D Scene Representation and Rendering](https://arxiv.org/abs/2010.04595), Trevithick and Yang, Arxiv 2020 | [github](https://github.com/alextrevithick/GRF) | [bibtex](./NeRF-and-Beyond.bib#L343-L348) <!---Trevithick20arxiv_GRF-->
- [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/abs/2012.02190), Yu et al., Arxiv 2020 | [github](https://github.com/sxyu/pixel-nerf) | [bibtex](./NeRF-and-Beyond.bib#L391-L396) <!---Yu20arxiv_pixelNeRF-->
- [Learned Initializations for Optimizing Coordinate-Based Neural Representations](https://arxiv.org/abs/2012.02189), Tancik et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L323-L328) <!---Tancik20arxiv_meta-->
- [pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis](https://marcoamonteiro.github.io/pi-GAN-website/), Chan et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L47-L52) <!---Chan20arxiv_piGAN-->
- [Portrait Neural Radiance Fields from a Single Image](https://portrait-nerf.github.io/), Gao et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L111-L116) <!---Gao20arxiv_pNeRF-->

#### Pose Estimation
- [iNeRF: Inverting Neural Radiance Fields for Pose Estimation](http://yenchenlin.me/inerf/), Yen-Chen et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L378-L383) <!---YenChen20arxiv_iNeRF-->

#### Lighting
- [NeRV: Neural Reflectance and Visibility Fields for Relighting and View Synthesis](https://people.eecs.berkeley.edu/~pratul/nerv/), Srinivasan et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L316-L321) <!---Srinivasan20arxiv_NeRV-->

#### Compositionality
- [GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields](https://arxiv.org/abs/2011.12100), Niemeyer et al., Arxiv 2020, [bibtex](./NeRF-and-Beyond.bib#L210-L215) <!---Niemeyer20arxiv_GIRAFFE-->
- [Object-Centric Neural Scene Rendering](https://shellguo.com/osf/), Guo et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L125-L130) <!---Guo20arxiv_OSF-->
- [Learning Compositional Radiance Fields of Dynamic Human Heads](https://ziyanw1.github.io/hybrid_nerf/), Wang et al., Arxiv 2020 | [bibtex](./citations/hybrid-nerf.txt) <!---Wang20arxiv_hybrid_NeRF-->


## Talks
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=LCTYRqW-ne8&t=10190s), Ben Mildenhall
- [Understanding and Extending Neural Radiance Fields](https://www.youtube.com/watch?v=nRyOzHpcr4Q&feature=emb_logo&ab_channel=cvprtum), Barron et al.
- [Towards Photorealism (2nd half)](https://youtu.be/Rd0nBO6--bM?t=1992), Vladlen Koltun
- [Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=dPWLybp4LL0), Matthew Tancik

## License 
MIT
