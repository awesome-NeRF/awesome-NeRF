# Awesome Neural Radiance Fields [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome neural radiance fields papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).


#### [How to submit a pull request?](https://github.com/yenchenlin/awesome-NeRF/blob/main/how-to-PR.md)

## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Talks](#talks)

## Survey
- [Neural Volume Rendering: NeRF And Beyond](https://arxiv.org/abs/2101.05204), Dellaert and Yen-Chen, Arxiv 2020 | [blog](https://dellaert.github.io/NeRF/) | [github](https://raw.githubusercontent.com/yenchenlin/awesome-NeRF/main/NeRF-and-Beyond.bib) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nerf-survey.txt)

## Papers
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173) <!---Mildenhall20eccv_nerf-->

#### Faster Inference
- [Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., NeurIPS 2020 | [github](https://github.com/facebookresearch/NSVF) | [bibtex](./NeRF-and-Beyond.bib#L135-L141) <!---Liu20neurips_sparse_nerf-->
- [AutoInt: Automatic Integration for Fast Neural Volume Rendering](http://www.computationalimaging.org/publications/automatic-integration/), Lindell et al., CVPR 2021 | [github](https://github.com/computational-imaging/automatic-integration) | [bibtex](./NeRF-and-Beyond.bib#L127-L133) <!---Lindell20arxiv_AutoInt-->
- [DeRF: Decomposed Radiance Fields](https://arxiv.org/abs/2011.12490), Rebain et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L222-L228) <!---Rebain20arxiv_derf-->
- [DONeRF: Towards Real-Time Rendering of Compact Neural Radiance Fields using Depth Oracle Networks](https://depthoraclenerf.github.io/), Neff et al., CGF 2021 | [bibtex](./citations/donerf.txt) <!---neff2021donerf-->
- [FastNeRF: High-Fidelity Neural Rendering at 200FPS](https://arxiv.org/abs/2103.10380), Garbin et al., Arxiv 2021 | [bibtex](./citations/fastnerf.txt) <!---Garbin21arxiv_FastNeRF-->
- [KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs ](https://arxiv.org/abs/2103.13744), Reiser et al., ICCV 2021 | [github](https://github.com/creiser/kilonerf) | [bibtex](./citations/kilonerf.txt) <!---reiser2021kilonerf-->
- [PlenOctrees for Real-time Rendering of Neural Radiance Fields](https://alexyu.net/plenoctrees/), Yu et al., Arxiv 2021 | [github](https://github.com/sxyu/volrend) | [bibtex](./citations/plenoctrees.txt) <!---yu2021plenoctrees-->
- [Mixture of Volumetric Primitives for Efficient Neural Rendering](https://arxiv.org/abs/2103.01954), Lombardi et al., SIGGRAPH 2021 | [bibtex](./citations/mixture.txt)
- [Light Field Networks: Neural Scene Representations with Single-Evaluation Rendering](https://vsitzmann.github.io/lfns/), Sitzmann et al., Arxiv 2021 | [bibtex](./citations/lfn.txt)

#### Faster Training
- [Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://arxiv.org/pdf/2107.02791.pdf), Deng et al., Arxiv 2021 | [github](https://github.com/dunbar12138/DSNeRF) | [bibtex](./citations/dsnerf.txt)
- [Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://arxiv.org/abs/2111.11215.pdf), Sun et al., Arxiv 2021 | [github](https://github.com/sunset1995/DirectVoxGO) | [bibtex](./citations/DirectVoxGO.txt) <!---sun2021direct-->

#### Unconstrained Images
- [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L152-L158) <!---MartinBrualla20arxiv_nerfw-->
- [Ha-NeRF:laughing:: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., Arxiv 2021 | [github](https://github.com/rover-xingyu/Ha-NeRF) | [bibtex](./citations/Ha-NeRF.txt) <!---chen2021hallucinated-->

#### Deformable
- [Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., Arxiv 2020 | [github](https://github.com/google/nerfies) | [bibtex](./NeRF-and-Beyond.bib#L206-L212) <!---Park20arxiv_nerfies-->
- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://www.albertpumarola.com/research/D-NeRF/index.html), Pumarola et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L214-L220) <!---Pumarola20arxiv_D_NeRF-->
- [Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://gafniguy.github.io/4D-Facial-Avatars/), Gafni et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L87-L93) <!---Gafni20arxiv_DNRF-->
- [Non-Rigid Neural Radiance Fields: Reconstruction and Novel View Synthesis of a Deforming Scene from Monocular Video](https://gvv.mpi-inf.mpg.de/projects/nonrigid_nerf/), Tretschk et al., Arxiv 2020 | [github](https://github.com/facebookresearch/nonrigid_nerf) | [bibtex](./NeRF-and-Beyond.bib#L283-L289) <!---Tretschk20arxiv_NR-NeRF-->
- [PVA: Pixel-aligned Volumetric Avatars](https://volumetric-avatars.github.io/), Raj et al., CVPR 2021 | [bibtex](./citations/pva.txt)
- [Neural Articulated Radiance Field](https://github.com/nogu-atsu/NARF), Noguchi et al., Arxiv 2021 | [bibtex](./citations/narf.txt)
- [CLA-NeRF: Category-Level Articulated Neural Radiance Field](https://arxiv.org/abs/2202.00181), Tseng et al., ICRA 2022 | [bibtex](./citations/cla-nerf.txt)
- [Animatable Neural Radiance Fields for Human Body Modeling](https://zju3dv.github.io/animatable_nerf/), Peng et al., Arxiv 2021 | [bibtex](citations/animatable_nerf.txt) <!---Peng21arxiv_animatable_nerf-->
- [A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields](https://hypernerf.github.io/), Park et al., Arxiv 2021 | [bibtex](./citations/hypernerf.txt)
- [Animatable Neural Radiance Fields from Monocular RGB Videos](https://arxiv.org/abs/2106.13629), Chen et al., Arxiv 2021 | [github](https://github.com/JanaldoChen/Anim-NeRF) | [bibtex](citations/anim_nerf.txt)
- [Neural Actor: Neural Free-view Synthesis of Human Actors with Pose Control](https://vcai.mpi-inf.mpg.de/projects/NeuralActor/), Liu et al., SIGGRAPH Asia 2021 | [bibtex](./citations/neuralactor.txt)

#### Video
- [Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes](http://www.cs.cornell.edu/~zl548/NSFF/), Li et al., CVPR 2021 | [github](https://github.com/zhengqili/Neural-Scene-Flow-Fields) | [bibtex](./NeRF-and-Beyond.bib#L119-L125) <!---Li20arxiv_nsff-->
- [Space-time Neural Irradiance Fields for Free-Viewpoint Video](https://video-nerf.github.io/), Xian et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L299-L305) <!---Xian20arxiv_stnif-->
- [Neural Radiance Flow for 4D View Synthesis and Video Processing](https://yilundu.github.io/nerflow/), Du et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L79-L85) <!---Du20arxiv_nerflow-->
- [Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans](https://zju3dv.github.io/neuralbody/), Peng et al., CVPR 2021 | [bibtex](citations/neuralbody.txt) <!---Peng20arxiv_neuralbody-->
- [Neural 3D Video Synthesis](https://neural-3d-video.github.io/), Li et al., Arxiv 2021 | [bibtex](./citations/3d-video.txt)
- [Dynamic View Synthesis from Dynamic Monocular Video](https://free-view-video.github.io/), Gao et al., ICCV 2021 | [bibtex](./citations/dvs_dmv.txt)

#### Generalization
- [GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis](https://arxiv.org/abs/2007.02442), Schwarz et al., NeurIPS 2020 | [github](https://github.com/autonomousvision/graf)  | [bibtex](./NeRF-and-Beyond.bib#L237-L243) <!---Schwarz20neurips_graf-->
- [GRF: Learning a General Radiance Field for 3D Scene Representation and Rendering](https://arxiv.org/abs/2010.04595), Trevithick and Yang, Arxiv 2020 | [github](https://github.com/alextrevithick/GRF) | [bibtex](./NeRF-and-Beyond.bib#L291-L297) <!---Trevithick20arxiv_GRF-->
- [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/abs/2012.02190), Yu et al., CVPR 2021 | [github](https://github.com/sxyu/pixel-nerf) | [bibtex](./NeRF-and-Beyond.bib#L329-L335) <!---Yu20arxiv_pixelNeRF-->
- [Learned Initializations for Optimizing Coordinate-Based Neural Representations](https://arxiv.org/abs/2012.02189), Tancik et al., CVPR 2021 | [github](https://github.com/tancik/learnit) | [bibtex](./NeRF-and-Beyond.bib#L268-L274) <!---Tancik20arxiv_meta-->
- [pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis](https://marcoamonteiro.github.io/pi-GAN-website/), Chan et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L24-L30) <!---Chan20arxiv_piGAN-->
- [Portrait Neural Radiance Fields from a Single Image](https://portrait-nerf.github.io/), Gao et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L95-L101) <!---Gao20arxiv_pNeRF-->
- [ShaRF: Shape-conditioned Radiance Fields from a Single View](https://arxiv.org/pdf/2102.08860.pdf), Rematas et al., ICML 2021 | [bibtex](./citations/sharf.txt)
- [IBRNet: Learning Multi-View Image-Based Rendering](https://ibrnet.github.io/static/paper.pdf), Wang et al., CVPR 2021 | [github](https://github.com/googleinterns/IBRNet) | [bibtex](./citations/ibr.txt)
- [CAMPARI: Camera-Aware Decomposed Generative Neural Radiance Fields](https://arxiv.org/pdf/2103.17269.pdf), Niemeyer & Geiger, Arxiv 2021 | [bibtex](./citations/CAMPARI.txt)
- [NeRF-VAE: A Geometry Aware 3D Scene Generative Model](https://arxiv.org/pdf/2104.00587.pdf), Kosiorek et al., Arxiv 2021 | [bibtex](./citations/nerf-vae.txt)
- [Unconstrained Scene Generation with Locally Conditioned Radiance Fields](https://apple.github.io/ml-gsn/), DeVries et al., Arxiv 2021 | [bibtex](./citations/gsn.txt)
- [MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://apchenstu.github.io/mvsnerf/), Chen et al., ICCV 2021 | [github](https://github.com/apchenstu/mvsnerf) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/mvsnerf.txt)
- [Stereo Radiance Fields (SRF): Learning View Synthesis from Sparse Views of Novel Scenes](https://virtualhumans.mpi-inf.mpg.de/srf/), Chibane et al., CVPR 2021 | [bibtex](./citations/srf.txt)
- [Neural Rays for Occlusion-aware Image-based Rendering](https://liuyuan-pal.github.io/NeuRay/), Liu et al., Arxiv 2021 | [bibtex](./citations/neuray.txt)
- [Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis](https://www.ajayj.com/dietnerf), Matthew Tancik et al., Arxiv 2021 | [bibtex](./citations/DietNeRF.txt)
- [MINE: Towards Continuous Depth MPI with NeRF for Novel View Synthesis](https://vincentfung13.github.io/projects/mine/), Jiaxin Li et al., ICCV 2021 | [github](https://github.com/vincentfung13/MINE) | [bibtex](./citations/MINE.txt)
- [TöRF: Time-of-Flight Radiance Fields for Dynamic Scene View Synthesis](https://imaging.cs.cmu.edu/torf/), Benjamin Attal et al., NeurIPS 2021 | [bibtex](./citations/turf.txt)
- [CodeNeRF: Disentangled Neural Radiance Fields for Object Categories](https://sites.google.com/view/wbjang/home/codenerf), Jang et al., ICCV 2021 | [bibtex](./citations/CodeNeRF.txt)
- [StyleNeRF: A Style-based 3D-Aware Generator for High-resolution Image Synthesis](http://jiataogu.me/style_nerf/), Gu et al., Arxiv 2021 | [bibtex](./citations/stylenerf.txt)
- [NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://bmild.github.io/rawnerf/), Ben Mildenhall et al, arXiv 2021 | [bibtex](./citations/rawnerf.txt)

#### Pose Estimation
- [iNeRF: Inverting Neural Radiance Fields for Pose Estimation](http://yenchenlin.me/inerf/), Yen-Chen et al. IROS 2021 | [bibtex](./NeRF-and-Beyond.bib#L321-L327) <!---YenChen20arxiv_iNeRF-->
- [A-NeRF: Surface-free Human 3D Pose Refinement via Neural Rendering](https://lemonatsu.github.io/ANeRF-Surface-free-Pose-Refinement/), Su et al. Arxiv 2021 | [bibtex](./citations/a-nerf.txt) <!---Su21arxiv_A_NeRF-->
- [NeRF--: Neural Radiance Fields Without Known Camera Parameters](http://nerfmm.active.vision/), Wang et al., Arxiv 2021 | [github](https://github.com/ActiveVisionLab/nerfmm) | [bibtex](./citations/nerf--.txt) <!---Wang21arxiv_nerfmm-->
- [iMAP: Implicit Mapping and Positioning in Real-Time](https://edgarsucar.github.io/iMAP/), Sucar et al., ICCV 2021 | [bibtex](./citations/imap.txt)
- [NICE-SLAM: Neural Implicit Scalable Encoding for SLAM](https://pengsongyou.github.io/nice-slam), Zhu et al., Arxiv 2021 | [bibtex](./citations/nice-slam.txt)
- [GNeRF: GAN-based Neural Radiance Field without Posed Camera](https://arxiv.org/abs/2103.15606), Meng et al., Arxiv 2021 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/gnerf.txt)
- [BARF: Bundle-Adjusting Neural Radiance Fields](https://chenhsuanlin.bitbucket.io/bundle-adjusting-NeRF/), Lin et al., ICCV 2021 | [bibtex](./citations/barf.txt)
- [Self-Calibrating Neural Radiance Fields](https://postech-cvlab.github.io/SCNeRF/), Jeong et al., ICCV 2021 | [github](https://github.com/POSTECH-CVLab/SCNeRF) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/SCNeRF.txt)

#### Lighting
- [NeRD: Neural Reflectance Decomposition from Image Collections](https://markboss.me/publication/2021-nerd/), Boss et al., Arxiv 2020 | [github](https://github.com/cgtuebingen/NeRD-Neural-Reflectance-Decomposition) | [bibtex](./NeRF-and-Beyond.bib#L9-L15) <!---Boss20arxiv_NeRD-->
- [NeRV: Neural Reflectance and Visibility Fields for Relighting and View Synthesis](https://people.eecs.berkeley.edu/~pratul/nerv/), Srinivasan et al. CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L260-L266) <!---Srinivasan20arxiv_NeRV-->
- [NeX: Real-time View Synthesis with Neural Basis Expansion](https://nex-mpi.github.io/), Wizadwongsa et al. Arxiv 2021 | [github](https://github.com/nex-mpi/nex-code) | [bibtex](./citations/nex.txt)
- [NeRFactor: Neural Factorization of Shape and Reflectance Under an Unknown Illumination](http://people.csail.mit.edu/xiuming/projects/nerfactor/), Zhang et al. Arxiv 2021 | [github](https://github.com/google/nerfactor) | [bibtex](./citations/nerfactor.txt)

#### Compositionality
- [NeRF++: Analyzing and Improving Neural Radiance Fields](https://arxiv.org/abs/2010.07492), Zhang et al., Arxiv 2020 | [github](https://github.com/Kai-46/nerfplusplus) | [bibtex](./NeRF-and-Beyond.bib#L345-L351) <!---Zhang20arxiv_nerf++-->
- [GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields](https://arxiv.org/abs/2011.12100), Niemeyer et al., CVPR 2021, [bibtex](./NeRF-and-Beyond.bib#L175-L181) <!---Niemeyer20arxiv_GIRAFFE-->
- [Object-Centric Neural Scene Rendering](https://shellguo.com/osf/), Guo et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L111-L117) <!---Guo20arxiv_OSF-->
- [Learning Compositional Radiance Fields of Dynamic Human Heads](https://ziyanw1.github.io/hybrid_nerf/), Wang et al., Arxiv 2020 | [bibtex](./citations/hybrid-nerf.txt) <!---Wang20arxiv_hybrid_NeRF-->
- [Neural Scene Graphs for Dynamic Scenes](https://light.princeton.edu/neural-scene-graphs/), Ost et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L353-L358) <!---Ost20arxiv_NeuralSceneGraphs-->
- [Unsupervised Discovery of Object Radiance Fields](https://kovenyu.com/uorf/), Yu et al., Arxiv 2021 | [bibtex](./citations/uorf.txt) 
- [Learning Object-Compositional Neural Radiance Field for Editable Scene Rendering](https://zju3dv.github.io/object_nerf/), Yang et al., ICCV 2021 | [github](https://github.com/zju3dv/object_nerf) | [bibtex](./citations/object-nerf.txt) <!---yang2021objectnerf-->

#### Scene Labelling and Understanding
- [In-Place Scene Labelling and Understanding with Implicit Scene Representation](https://shuaifengzhi.com/Semantic-NeRF/), Zhi et al., Arxiv 2021 | [bibtex](./citations/semantic-nerf.txt)

#### Editing 
- [Editing Conditional Radiance Fields](http://editnerf.csail.mit.edu/), Liu et al., Arxiv 2021 | [github](https://github.com/stevliu/editnerf) | [bibtex](./citations/editnerf.txt)
- [Editable Free-viewpoint Video Using a Layered Neural Representation](https://jiakai-zhang.github.io/st-nerf/), Zhang et al., SIGGRAPH 2021 | [github](https://github.com/DarlingHang/st-nerf) | [bibtex](./citations/st-nerf.txt)

#### Object Category Modeling
- [FiG-NeRF: Figure Ground Neural Radiance Fields for 3D Object Category Modelling](https://fig-nerf.github.io/), Xie et al., Arxiv 2021 | [bibtex](./citations/fig-nerf.txt)
- [NeRF-Tex: Neural Reflectance Field Textures](https://developer.nvidia.com/blog/nvidia-research-nerf-tex-neural-reflectance-field-textures/), Baatz et al., EGSR 2021 | [bibtex](./citations/nerf-tex.txt)

#### Multi-scale
- [Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields](https://jonbarron.info/mipnerf/), Barron et al., Arxiv 2021 | [github](https://github.com/google/mipnerf) | [bibtex](./citations/mip-nerf.txt)

#### Model Reconstruction
- [UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction](https://arxiv.org/abs/2104.10078), Oechsle et al., ICCV 2021 | [bibtex](./citations/unisurf.txt)
- [NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction](https://arxiv.org/abs/2106.10689), Wang et al., NeurIPS 2021 | [github](https://github.com/Totoro97/NeuS) | [bibtex](./citations/neus.txt)
- [Volume Rendering of Neural Implicit Surfaces](https://arxiv.org/abs/2106.12052), Yariv et al., NeurIPS 2021 | [github](https://github.com/ventusff/neurecon) | [bibtex](./citations/volsdf.txt)
- [Neural 3D Scene Reconstruction with the Manhattan-world Assumption](https://arxiv.org/pdf/2205.02836.pdf), Guo et al., CVPR 2022 | [github](https://github.com/zju3dv/manhattan_sdf) | [bibtex](./citations/manhattan_sdf.txt)

#### Depth Estimation
- [NerfingMVS: Guided Optimization of Neural Radiance Fields for Indoor Multi-view Stereo](https://weiyithu.github.io/NerfingMVS/), Wei et al., ICCV 2021 | [bibtex](./citations/NerfingMVS.txt)

#### Robotics
- [3D Neural Scene Representations for Visuomotor Control](https://3d-representation-learning.github.io/nerf-dy/), Li et al., CoRL 2021 Oral | [bibtex](./citations/nerf-dy.txt)
- [Vision-Only Robot Navigation in a Neural Radiance World](https://arxiv.org/abs/2110.00168), Adamkiewicz et al., RA-L 2022 Vol.7 No.2 | [bibtex](./citations/vision-only.txt)

## Talks
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=LCTYRqW-ne8&t=10190s), Ben Mildenhall
- [Understanding and Extending Neural Radiance Fields](https://www.youtube.com/watch?v=nRyOzHpcr4Q&feature=emb_logo&ab_channel=cvprtum), Barron et al.
- [Towards Photorealism (2nd half)](https://youtu.be/Rd0nBO6--bM?t=1992), Vladlen Koltun
- [Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=dPWLybp4LL0), Matthew Tancik

## Implementations
#### Tensorflow
- [NeRF](https://github.com/bmild/nerf), Mildenhall et al., 2020 | [bibtex](./NeRF-and-Beyond.bib#L168-L173)

#### PyTorch
- [NeRF-PyTorch](https://github.com/yenchenlin/nerf-pytorch), Yen-Chen Lin, 2020 | [bibtex](./citations/pytorch-nerf.txt)
- [NeRF-PyTorch-Lighting](https://github.com/kwea123/nerf_pl), [@kwea123](https://github.com/kwea123), 2020
- [NeRF-W](https://github.com/kwea123/nerf_pl/tree/nerfw), [@kwea123](https://github.com/kwea123), 2021
- [NeRF-PyTorch3D](https://github.com/facebookresearch/pytorch3d/tree/master/projects/nerf), [@facebookresearch](https://github.com/facebookresearch), 2020

#### Jax
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf), Deng et al., 2020 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/NeRF-and-Beyond.bib#L55-L60)
- [Mip-NeRF](https://github.com/google/mipnerf), [@google](https://github.com/google), 2021 | [bibtex](./citations/mipnerf.txt)

## License 
MIT
