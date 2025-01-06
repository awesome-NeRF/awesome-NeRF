# Awesome Neural Radiance Fields [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome neural radiance fields papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).


#### [How to submit a pull request?](https://github.com/yenchenlin/awesome-NeRF/blob/main/how-to-PR.md)
#### [Want to help maintain the list?](https://github.com/awesome-NeRF/awesome-NeRF/issues/108#issuecomment-1350732470)


## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
- [Talks](#talks)
- [Implementations](#implementations)

## Survey
- [Semantically-aware Neural Radiance Fields for Visual Scene Understanding: A Comprehensive Review](https://arxiv.org/abs/2402.11141), Thang-Anh-Quan Nguyen*, Amine Bourki*, Màtyàs Macudzinski, Anthony Brunel, and Mohammed Bennamoun (*: Equal contribution), Arxiv 2024 | [github](https://github.com/abourki/SoTA-Semantically-aware-NeRFs) | [bibtex](citations/survey_semantically-awareNeRFs.txt)
- [BeyondPixels: A Comprehensive Review of the Evolution of Neural Radiance Fields](https://arxiv.org/abs/2306.03000), AKM Shahariar Azad Rabby and Chengcui Zhang, Arxiv 2023 | [bibtex](citations/BeyondPixels.txt)
- [Neural Volume Rendering: NeRF And Beyond](https://arxiv.org/abs/2101.05204), Dellaert and Yen-Chen, Arxiv 2020 | [blog](https://dellaert.github.io/NeRF/) | [github](https://raw.githubusercontent.com/yenchenlin/awesome-NeRF/main/NeRF-and-Beyond.bib) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nerf-survey.txt)
- [NeRF: Neural Radiance Field in 3D Vision, Introduction and Review](https://arxiv.org/abs/2210.00379), Kyle Gao, Yina Gao, Hongjie He, Dening Lu, Linlin Xu, Jonathan Li
- [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220), Muhammad Zubair Irshad, Mauro Comi, Yen-Chen Lin, Nick Heppert, Abhinav Valada, Zsolt Kira, Rares Ambrus, Johnathan Trembley

## Papers
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173) <!---Mildenhall20eccv_nerf-->


<details open>
<summary>Faster Inference</summary>

- [Learning Neural Transmittance for Efficient Rendering of Reflectance Fields](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Mohammad Shafiei et al., BMVC 2021 | [bibtex](./citations/NeuralTransmittance.txt)
- [Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., NeurIPS 2020 | [github](https://github.com/facebookresearch/NSVF) | [bibtex](./NeRF-and-Beyond.bib#L135-L141) <!---Liu20neurips_sparse_nerf-->
- [AutoInt: Automatic Integration for Fast Neural Volume Rendering](http://www.computationalimaging.org/publications/automatic-integration/), Lindell et al., CVPR 2021 | [github](https://github.com/computational-imaging/automatic-integration) | [bibtex](./NeRF-and-Beyond.bib#L127-L133) <!---Lindell20arxiv_AutoInt-->
- [DeRF: Decomposed Radiance Fields](https://arxiv.org/abs/2011.12490), Rebain et al. Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L222-L228) <!---Rebain20arxiv_derf-->
- [DONeRF: Towards Real-Time Rendering of Compact Neural Radiance Fields using Depth Oracle Networks](https://depthoraclenerf.github.io/), Neff et al., CGF 2021 | [github](https://github.com/facebookresearch/DONERF) | [bibtex](./citations/donerf.txt) <!---neff2021donerf-->
- [FastNeRF: High-Fidelity Neural Rendering at 200FPS](https://arxiv.org/abs/2103.10380), Garbin et al., Arxiv 2021 | [bibtex](./citations/fastnerf.txt) <!---Garbin21arxiv_FastNeRF-->
- [KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs ](https://arxiv.org/abs/2103.13744), Reiser et al., ICCV 2021 | [github](https://github.com/creiser/kilonerf) | [bibtex](./citations/kilonerf.txt) <!---reiser2021kilonerf-->
- [PlenOctrees for Real-time Rendering of Neural Radiance Fields](https://alexyu.net/plenoctrees/), Yu et al., Arxiv 2021 | [github](https://github.com/sxyu/volrend) | [bibtex](./citations/plenoctrees.txt) <!---yu2021plenoctrees-->
- [Mixture of Volumetric Primitives for Efficient Neural Rendering](https://arxiv.org/abs/2103.01954), Lombardi et al., SIGGRAPH 2021 | [bibtex](./citations/mixture.txt)
- [Light Field Networks: Neural Scene Representations with Single-Evaluation Rendering](https://vsitzmann.github.io/lfns/), Sitzmann et al., Arxiv 2021 | [github](https://github.com/vsitzmann/light-field-networks) | [bibtex](./citations/lfn.txt)
- [RT-NeRF: Real-Time On-Device Neural Radiance Fields Towards Immersive AR/VR Rendering](https://arxiv.org/abs/2212.01120), Li et al., ICCAD 2022 | [bibtex](./citations/rt-nerf.txt)
- [ENeRF: Efficient Neural Radiance Fields for Interactive Free-viewpoint Video](https://zju3dv.github.io/enerf/), Lin et al., SIGGRAPH 2022 | [github](https://github.com/zju3dv/ENeRF) | [bibtex](./citations/enerf.txt)
- [R2L: Distilling Neural Radiance Field to Neural Light Field for Efficient Novel View Synthesis](https://arxiv.org/abs/2203.17261), Wang et al., ECCV 2022 | [github](https://github.com/snap-research/R2L) | [bibtex](./citations/r2l.txt) <!---wang2022r2l-->
- [Real-Time Neural Light Field on Mobile Devices](https://arxiv.org/abs/2212.08057), Cao et al., Arxiv 2022 | [github](https://github.com/snap-research/MobileR2L) | [bibtext](./citations/r2l-mobile.txt) <!---cao2022mobiler2l-->
- [Hardware Acceleration of Neural Graphics](https://arxiv.org/pdf/2303.05735.pdf), Mubarik et al., ISCA 2023 | [bibtext](./citations/hw_accelaration.txt) <!---mubarik2023hardware-->
- [DyLiN: Making Light Field Networks Dynamic](https://dylin2023.github.io/), Yu et al., CVPR 2023 | [github](https://github.com/Heng14/DyLiN) | [bibtext](./citations/dylin.txt) <!---yu2023dylin-->
</details>


<details open>
<summary>Faster Training</summary>

- [Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://arxiv.org/pdf/2107.02791.pdf), Deng et al., Arxiv 2021 | [github](https://github.com/dunbar12138/DSNeRF) | [bibtex](./citations/dsnerf.txt)
- [Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://arxiv.org/abs/2111.11215.pdf), Sun et al., CVPR 2022 | [github](https://github.com/sunset1995/DirectVoxGO) | [bibtex](./citations/DirectVoxGO.txt) <!---sun2021direct-->
- [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/), Müller et al., SIGGRAPH 2022 | [github](https://github.com/NVlabs/instant-ngp) | [bibtex](./citations/instant-ngp.txt)
- [Plenoxels Radiance Fields without Neural Networks](https://alexyu.net/plenoxels/), Yu et al., CVPR 2022 | [github](https://github.com/sxyu/svox2) | [bibtex](./citations/plenoxels.txt)
- [TensoRF: Tensorial Radiance Fields](https://apchenstu.github.io/TensoRF/), Chen et al., ECCV 2022 | [github](https://github.com/apchenstu/TensoRF) | [bibtex](./citations/tensorf.txt)
- [BakedSDF: Meshing Neural SDFs for Real-Time View Synthesis](https://bakedsdf.github.io/), Yariv et al., Arxiv 2023 | [bibtex](./citations/bakedsdf.txt)
- [Lightning NeRF: Efficient Hybrid Scene Representation for Autonomous Driving](https://arxiv.org/pdf/2403.05907v1.pdf), Cao et al. ICRA 2024 | [github](https://github.com/VISION-SJTU/Lightning-NeRF) | [bibtex](./citations/lightning-nerf.txt)
</details>

<details open>
<summary>Compression</summary>

- [Variable Bitrate Neural Fields](https://nv-tlabs.github.io/vqad/), Takikawa et al., SIGGRAPH 2022 | [github](https://github.com/nv-tlabs/vqad) | [bibtex](./citations/Variable-bitrate-neural-fields.txt)
</details>

<details open>
<summary>Unconstrained Images</summary>

- [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L152-L158) <!---MartinBrualla20arxiv_nerfw-->
- [Ha-NeRF:laughing:: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., CVPR 2022 | [github](https://github.com/rover-xingyu/Ha-NeRF) | [bibtex](./citations/Ha-NeRF.txt) <!---chen2021hallucinated-->
- [HDR-Plenoxels: Self-Calibrating High Dynamic Range Radiance Fields](https://hdr-plenoxels.github.io/), Jun-seong et al., ECCV 2022 | [github](https://github.com/postech-ami/HDR-Plenoxels) | [bibtex](./citations/hdr-plenoxels.txt) <!---Jun-seong2022hdr-plenoxels-->
- [UP-NeRF: Unconstrained Pose-Prior-Free Neural Radiance Fields](https://mlvlab.github.io/upnerf/), In-jae et al., NeurIPS 2023 | [github](https://github.com/mlvlab/UP-NeRF) | [bibtex](./citations/upnerf.txt) <!---kim2023upnerf-->
</details>


<details open>
<summary>Deformable</summary>

- [Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., Arxiv 2020 | [github](https://github.com/google/nerfies) | [bibtex](./NeRF-and-Beyond.bib#L206-L212) <!---Park20arxiv_nerfies-->
- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://www.albertpumarola.com/research/D-NeRF/index.html), Pumarola et al., CVPR 2021 | [github](https://github.com/albertpumarola/D-NeRF) | [bibtex](./NeRF-and-Beyond.bib#L214-L220) <!---Pumarola20arxiv_D_NeRF-->
- [Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://gafniguy.github.io/4D-Facial-Avatars/), Gafni et al., CVPR 2021 | [github](https://github.com/gafniguy/4D-Facial-Avatars) | [bibtex](./NeRF-and-Beyond.bib#L87-L93) <!---Gafni20arxiv_DNRF-->
- [Non-Rigid Neural Radiance Fields: Reconstruction and Novel View Synthesis of a Deforming Scene from Monocular Video](https://gvv.mpi-inf.mpg.de/projects/nonrigid_nerf/), Tretschk et al., Arxiv 2020 | [github](https://github.com/facebookresearch/nonrigid_nerf) | [bibtex](./NeRF-and-Beyond.bib#L283-L289) <!---Tretschk20arxiv_NR-NeRF-->
- [PVA: Pixel-aligned Volumetric Avatars](https://volumetric-avatars.github.io/), Raj et al., CVPR 2021 | [bibtex](./citations/pva.txt)
- [Neural Articulated Radiance Field](https://github.com/nogu-atsu/NARF), Noguchi et al., Arxiv 2021 | [github](https://github.com/nogu-atsu/NARF) | [bibtex](./citations/narf.txt)
- [CLA-NeRF: Category-Level Articulated Neural Radiance Field](https://arxiv.org/abs/2202.00181), Tseng et al., ICRA 2022 | [bibtex](./citations/cla-nerf.txt)
- [Animatable Neural Radiance Fields for Modeling Dynamic Human Bodies](https://zju3dv.github.io/animatable_nerf/), Peng et al., ICCV 2021 | [github](https://github.com/zju3dv/animatable_nerf) | [bibtex](citations/animatable_nerf.txt) <!---Peng21arxiv_animatable_nerf-->
- [A Higher-Dimensional Representation for Topologically Varying Neural Radiance Fields](https://hypernerf.github.io/), Park et al., Arxiv 2021 | [github](https://github.com/google/hypernerf) | [bibtex](./citations/hypernerf.txt)
- [IBRNet: Learning Multi-View Image-Based Rendering](https://ibrnet.github.io/static/paper.pdf), Wang et al., CVPR 2021 | [github](https://github.com/googleinterns/IBRNet) | [bibtex](./citations/ibr.txt)
- [Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes](http://www.cs.cornell.edu/~zl548/NSFF/), Li et al., CVPR 2021 | [github](https://github.com/zhengqili/Neural-Scene-Flow-Fields) | [bibtex](./NeRF-and-Beyond.bib#L119-L125) <!---Li20arxiv_nsff-->
- [Animatable Neural Radiance Fields from Monocular RGB Videos](https://arxiv.org/abs/2106.13629), Chen et al., Arxiv 2021 | [github](https://github.com/JanaldoChen/Anim-NeRF) | [bibtex](citations/anim_nerf.txt)
- [Neural Actor: Neural Free-view Synthesis of Human Actors with Pose Control](https://vcai.mpi-inf.mpg.de/projects/NeuralActor/), Liu et al., SIGGRAPH Asia 2021 | [bibtex](./citations/neuralactor.txt)
- [TiNeuVox: Fast Dynamic Radiance Fields with Time-Aware Neural Voxels](https://jaminfong.cn/tineuvox/), Fang et al., SIGGRAPH Asia 2022 | [github](https://github.com/hustvl/TiNeuVox) | [bibtex](./citations/TiNeuVox.txt)
- [HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://grail.cs.washington.edu/projects/humannerf/), Weng et al., CVPR 2022 | [github](https://github.com/chungyiweng/humannerf) | [bibtex](./citations/humannerf.txt)
- [AligNeRF: High-Fidelity Neural Radiance Fields via Alignment-Aware Training](https://yifanjiang19.github.io/alignerf), Jiang et al., CVPR 2023 | [bibtex](./citations/AligNeRF.txt)
- [DynIBaR: Neural Dynamic Image-Based Rendering](https://dynibar.github.io/), Li et al., CVPR 2023 | [bibtex](./citations/DynIBaR.txt)

</details>


<details open>
<summary>Video</summary>

- [BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects](https://bundlesdf.github.io/), Wen et al., CVPR 2023 | [github](https://github.com/NVlabs/BundleSDF) | [bibtex](./citations/bundlesdf.txt)
- [Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes](http://www.cs.cornell.edu/~zl548/NSFF/), Li et al., CVPR 2021 | [github](https://github.com/zhengqili/Neural-Scene-Flow-Fields) | [bibtex](./NeRF-and-Beyond.bib#L119-L125) <!---Li20arxiv_nsff-->
- [Space-time Neural Irradiance Fields for Free-Viewpoint Video](https://video-nerf.github.io/), Xian et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L299-L305) <!---Xian20arxiv_stnif-->
- [Neural Radiance Flow for 4D View Synthesis and Video Processing](https://yilundu.github.io/nerflow/), Du et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L79-L85) <!---Du20arxiv_nerflow-->
- [Neural Body: Implicit Neural Representations with Structured Latent Codes for Novel View Synthesis of Dynamic Humans](https://zju3dv.github.io/neuralbody/), Peng et al., CVPR 2021 | [github](https://github.com/zju3dv/neuralbody) | [bibtex](citations/neuralbody.txt) <!---Peng20arxiv_neuralbody-->
- [UV Volumes for Real-time Rendering of Editable Free-view Human Performance](https://fanegg.github.io/UV-Volumes/), Chen et al., CVPR 2023 | [github](https://github.com/fanegg/UV-Volumes) | [bibtex](citations/UV-Volumes.txt) <!---Chen22arxiv_uvvolumes-->
- [Neural 3D Video Synthesis from Multi-view Video](https://neural-3d-video.github.io/), Li et al., CVPR 2022 | [bibtex](./citations/3d-video.txt)
- [Dynamic View Synthesis from Dynamic Monocular Video](https://free-view-video.github.io/), Gao et al., ICCV 2021 | [bibtex](./citations/dvs_dmv.txt)
- [Streaming Radiance Fields for 3D Video Synthesis](https://arxiv.org/abs/2210.14831) Li et al. NeurIPS 2022 | [github](https://github.com/AlgoHunt/StreamRF) | [bibtex](./citations/StreamRF.txt)
</details>


<details open>
<summary>Generalization</summary>

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
- [MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://apchenstu.github.io/mvsnerf/), Chen et al., ICCV 2021 | [github](https://github.com/apchenstu/mvsnerf) | [bibtex](./citations/mvsnerf.txt)
- [Stereo Radiance Fields (SRF): Learning View Synthesis from Sparse Views of Novel Scenes](https://virtualhumans.mpi-inf.mpg.de/srf/), Chibane et al., CVPR 2021 | [bibtex](./citations/srf.txt)
- [Neural Rays for Occlusion-aware Image-based Rendering](https://liuyuan-pal.github.io/NeuRay/), Liu et al., Arxiv 2021 | [bibtex](./citations/neuray.txt)
- [Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis](https://www.ajayj.com/dietnerf), Matthew Tancik et al., Arxiv 2021 | [bibtex](./citations/DietNeRF.txt)
- [MINE: Towards Continuous Depth MPI with NeRF for Novel View Synthesis](https://vincentfung13.github.io/projects/mine/), Jiaxin Li et al., ICCV 2021 | [github](https://github.com/vincentfung13/MINE) | [bibtex](./citations/MINE.txt)
- [TöRF: Time-of-Flight Radiance Fields for Dynamic Scene View Synthesis](https://imaging.cs.cmu.edu/torf/), Benjamin Attal et al., NeurIPS 2021 | [bibtex](./citations/turf.txt)
- [CodeNeRF: Disentangled Neural Radiance Fields for Object Categories](https://sites.google.com/view/wbjang/home/codenerf), Jang et al., ICCV 2021 | [bibtex](./citations/CodeNeRF.txt)
- [StyleNeRF: A Style-based 3D-Aware Generator for High-resolution Image Synthesis](http://jiataogu.me/style_nerf/), Gu et al., Arxiv 2021 | [bibtex](./citations/stylenerf.txt)
- [Generative Occupancy Fields for 3D Surface-Aware Image Synthesis](https://sheldontsui.github.io/projects/GOF), Xu et al., NeurIPS 2021 | [github](https://github.com/SheldonTsui/GOF_NeurIPS2021) | [bibtex](./citations/gof.txt)
- [NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://bmild.github.io/rawnerf/), Ben Mildenhall et al, arXiv 2021 | [bibtex](./citations/rawnerf.txt)
- [Point-NeRF: Point-based Neural Radiance Fields](https://xharlie.github.io/projects/project_sites/pointnerf/index.html), Xu et al., CVPR 2022 | [github](https://github.com/Xharlie/pointnerf) | [bibtex](./citations/Point-NeRF.txt)
- [SinNeRF: Training Neural Radiance Fields on Complex Scenes from a Single Image](https://vita-group.github.io/SinNeRF/), Xu et al., ECCV 2022 | [github](https://github.com/VITA-Group/SinNeRF) | [bibtex](./citations/SinNeRF.txt)
- [Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://3d-avatar-diffusion.microsoft.com/), Wang et al., CVPR 2023 | [github](https://3d-avatar-diffusion.microsoft.com/) | [bibtex](./citations/rodin.txt)
- [SurfelNeRF: Neural Surfel Radiance Fields for Online Photorealistic Reconstruction of Indoor Scenes](https://arxiv.org/abs/2304.08971), Gao et al., CVPR 2023 | [github](https://gymat.github.io/SurfelNeRF-web/) | [bibtex](./citations/SurfelNeRF.txt)
- [NeO 360: Neural Fields for Sparse View Synthesis of Outdoor Scenes](https://arxiv.org/abs/2308.12967), Irshad et al., ICCV 2023 | [github](https://github.com/zubair-irshad/NeO-360) | [bibtex](./citations/SurfelNeRF.txt)
- [X-NeRF: Explicit Neural Radiance Field for Multi-Scene 360° Insufficient RGB-D Views](https://arxiv.org/abs/2210.05135), Zhu et al., WACV 2023 | [github](https://github.com/HaoyiZhu/XNeRF) | [bibtex](./citations/x-nerf.txt)
- [UFORecon: Generalizable Sparse-View Surface Reconstruction from Arbitrary and Unfavorable Sets](https://arxiv.org/abs/2403.05086), Na et al., CVPR 2024 | [github](https://github.com/Youngju-Na/UFORecon) | [bibtex](./citations/uforecon.txt)
- [🏡Know Your Neighbors: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning](https://arxiv.org/abs/2404.03658), Li et al., CVPR 2024 | [github](https://github.com/ruili3/Know-Your-Neighbors) | [bibtex](./citations/KYN.txt)

</details>

<details open>
<summary>Pose Estimation</summary>

- [BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects](https://bundlesdf.github.io/), Wen et al., CVPR 2023 | [github](https://github.com/NVlabs/BundleSDF) | [bibtex](./citations/bundlesdf.txt)
- [iNeRF: Inverting Neural Radiance Fields for Pose Estimation](http://yenchenlin.me/inerf/), Yen-Chen et al. IROS 2021 | [bibtex](./NeRF-and-Beyond.bib#L321-L327) <!---YenChen20arxiv_iNeRF-->
- [A-NeRF: Surface-free Human 3D Pose Refinement via Neural Rendering](https://zollhoefer.com/papers/arXiv20_ANeRF/page.html), Su et al. Arxiv 2021 | [bibtex](./citations/a-nerf.txt) <!---Su21arxiv_A_NeRF-->
- [NeRF--: Neural Radiance Fields Without Known Camera Parameters](http://nerfmm.active.vision/), Wang et al., Arxiv 2021 | [github](https://github.com/ActiveVisionLab/nerfmm) | [bibtex](./citations/nerf--.txt) <!---Wang21arxiv_nerfmm-->
- [iMAP: Implicit Mapping and Positioning in Real-Time](https://edgarsucar.github.io/iMAP/), Sucar et al., ICCV 2021 | [bibtex](./citations/imap.txt)
- [NICE-SLAM: Neural Implicit Scalable Encoding for SLAM](https://pengsongyou.github.io/nice-slam), Zhu et al., Arxiv 2021 | [bibtex](./citations/nice-slam.txt)
- [GNeRF: GAN-based Neural Radiance Field without Posed Camera](https://arxiv.org/abs/2103.15606), Meng et al., Arxiv 2021 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/gnerf.txt)
- [BARF: Bundle-Adjusting Neural Radiance Fields](https://chenhsuanlin.bitbucket.io/bundle-adjusting-NeRF/), Lin et al., ICCV 2021 | [bibtex](./citations/barf.txt)
- [Self-Calibrating Neural Radiance Fields](https://postech-cvlab.github.io/SCNeRF/), Jeong et al., ICCV 2021 | [github](https://github.com/POSTECH-CVLab/SCNeRF) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/SCNeRF.txt)
- [DFNet: Enhance Absolute Pose Regression with Direct Feature Matching](https://dfnet.active.vision/), Chen et al., ECCV 2022 | [github](https://github.com/ActiveVisionLab/DFNet) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/dfnet.txt)
- [GARF: Gaussian Activated Radiance Fields for High Fidelity Reconstruction and Pose Estimation](https://arxiv.org/abs/2204.05735), Chng et al., ECCV 2022 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/garf.txt)
- [L2G-NeRF: Local-to-Global Registration for Bundle-Adjusting Neural Radiance Fields](https://rover-xingyu.github.io/L2G-NeRF/), Chen et al., CVPR 2023 | [github](https://github.com/rover-xingyu/L2G-NeRF) | [bibtex](./citations/L2G-NeRF.txt)
- [NoPe-NeRF: Optimising Neural Radiance Field with No Pose Prior](https://nope-nerf.active.vision/), Bian et al., CVPR 2023 | [github](https://github.com/ActiveVisionLab/nope-nerf) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nope-nerf.txt)
- [Loc-NeRF: Monte Carlo Localization using Neural Radiance Fields](https://arxiv.org/abs/2209.09050), Maggio et al., ICRA 2023 | [github](https://github.com/MIT-SPARK/Loc-NeRF) | [bibtex](./citations/locnerf.txt)
- [Robust Camera Pose Refinement for Multi-Resolution Hash Encoding](http://arxiv.org/abs/2302.01571), Heo et al., ICML 2023 | [bibtex](.citations/instantpose.txt)
- [CROSSFIRE: Camera Relocalization On Self-Supervised Features from an Implicit Representation](https://arxiv.org/abs/2303.04869), Moreau et al., ICCV 2023 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/crossfire.txt)
- [PoRF: Pose Residual Field for Accurate Neural Surface Reconstruction](https://porf.active.vision/), Bian et al., ICLR 2024 | [github](https://github.com/ActiveVisionLab/porf) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/porf.txt)
- [Neural Refinement for Absolute Pose Regression with Feature Synthesis](https://nefes.active.vision/), Chen et al., CVPR 2024 | [github](https://github.com/ActiveVisionLab/NeFeS) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nefes.txt)
</details>

<details open>
<summary>Lighting</summary>

- [NeRD: Neural Reflectance Decomposition from Image Collections](https://markboss.me/publication/2021-nerd/), Boss et al., Arxiv 2020 | [github](https://github.com/cgtuebingen/NeRD-Neural-Reflectance-Decomposition) | [bibtex](./NeRF-and-Beyond.bib#L9-L15) <!---Boss20arxiv_NeRD-->
- [NeRV: Neural Reflectance and Visibility Fields for Relighting and View Synthesis](https://people.eecs.berkeley.edu/~pratul/nerv/), Srinivasan et al. CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L260-L266) <!---Srinivasan20arxiv_NeRV-->
- [NeX: Real-time View Synthesis with Neural Basis Expansion](https://nex-mpi.github.io/), Wizadwongsa et al. Arxiv 2021 | [github](https://github.com/nex-mpi/nex-code) | [bibtex](./citations/nex.txt)
- [NeRFactor: Neural Factorization of Shape and Reflectance Under an Unknown Illumination](http://people.csail.mit.edu/xiuming/projects/nerfactor/), Zhang et al. Arxiv 2021 | [github](https://github.com/google/nerfactor) | [bibtex](./citations/nerfactor.txt)
- [A Shading-Guided Generative Implicit Model for Shape-Accurate 3D-Aware Image Synthesis](https://xingangpan.github.io/projects/ShadeGAN.html), Pan et al., NeurIPS 2021 | [github](https://github.com/XingangPan/ShadeGAN) | [bibtex](./citations/shadegan.txt)
- [KiloNeuS: Implicit Neural Representations with Real-Time Global Illumination](https://arxiv.org/abs/2206.10885), Esposito et al., Arxiv 2022 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/kiloneus.txt)
</details>


<details open>
<summary>Compositionality</summary>

- [NeRF++: Analyzing and Improving Neural Radiance Fields](https://arxiv.org/abs/2010.07492), Zhang et al., Arxiv 2020 | [github](https://github.com/Kai-46/nerfplusplus) | [bibtex](./NeRF-and-Beyond.bib#L345-L351) <!---Zhang20arxiv_nerf++-->
- [GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields](https://arxiv.org/abs/2011.12100), Niemeyer et al., CVPR 2021, [bibtex](./NeRF-and-Beyond.bib#L175-L181) <!---Niemeyer20arxiv_GIRAFFE-->
- [Object-Centric Neural Scene Rendering](https://shellguo.com/osf/), Guo et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L111-L117) <!---Guo20arxiv_OSF-->
- [Learning Compositional Radiance Fields of Dynamic Human Heads](https://ziyanw1.github.io/hybrid_nerf/), Wang et al., Arxiv 2020 | [bibtex](./citations/hybrid-nerf.txt) <!---Wang20arxiv_hybrid_NeRF-->
- [Neural Scene Graphs for Dynamic Scenes](https://light.princeton.edu/neural-scene-graphs/), Ost et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L353-L358) <!---Ost20arxiv_NeuralSceneGraphs-->
- [Unsupervised Discovery of Object Radiance Fields](https://kovenyu.com/uorf/), Yu et al., ICLR 2022 | [github](https://github.com/KovenYu/uORF) | [bibtex](./citations/uorf.txt)
- [Unsupervised Discovery and Composition of Object Light Fields](https://cameronosmith.github.io/colf/), Smith et al., TMLR 2023 | [github](https://github.com/cameronosmith/COLF) | [bibtex](./citations/colf.txt)
- [Learning Object-centric Neural Scattering Functions for Free-viewpoint Relighting and Scene Composition](https://kovenyu.com/osf/), Yu et al., TMLR 2023 | [github](https://github.com/michguo/osf) | [bibtex](./citations/osf.txt)
- [Learning Object-Compositional Neural Radiance Field for Editable Scene Rendering](https://zju3dv.github.io/object_nerf/), Yang et al., ICCV 2021 | [github](https://github.com/zju3dv/object_nerf) | [bibtex](./citations/object-nerf.txt) <!---yang2021objectnerf-->
- [MoFaNeRF: Morphable Facial Neural Radiance Field](https://neverstopzyy.github.io/mofanerf/), Zhuang et al., Arxiv 2021 | [github](https://github.com/zhuhao-nju/mofanerf) | [bibtex](./citations/mofaNeRF.txt)
</details>


<details open>
<summary>Scene Labelling and Understanding</summary>

- [In-Place Scene Labelling and Understanding with Implicit Scene Representation](https://shuaifengzhi.com/Semantic-NeRF/), Zhi et al., Arxiv 2021 | [bibtex](./citations/semantic-nerf.txt)
- [NeRF-SOS: Any-view Self-supervised Object Segmentation on Complex Real-world Scenes](https://zhiwenfan.github.io/NeRF-SOS/), Fan et al., ICLR 2023 | [bibtex](./citations/NeRF-SOS.txt)
- [Contrastive Lift: 3D Object Instance Segmentation by Slow-Fast Contrastive Fusion](https://www.robots.ox.ac.uk/~vgg/research/contrastive-lift/), Bhalgat et al., NeurIPS 2023 (**Spotlight**) | [bibtex](./citations/contrastive-lift.txt)
</details>


<details open>
<summary>Editing</summary>

- [Editing Conditional Radiance Fields](http://editnerf.csail.mit.edu/), Liu et al., Arxiv 2021 | [github](https://github.com/stevliu/editnerf) | [bibtex](./citations/editnerf.txt)
- [Editable Free-viewpoint Video Using a Layered Neural Representation](https://jiakai-zhang.github.io/st-nerf/), Zhang et al., SIGGRAPH 2021 | [github](https://github.com/DarlingHang/st-nerf) | [bibtex](./citations/st-nerf.txt)
- [NeRF-In: Free-Form NeRF Inpainting with RGB-D Priors](https://jdily.github.io/proj_site/nerfin_proj.html), Liu et al., Arxiv 2022 | [bibtex](./citations/nerf-in.txt)
- [Unified Implicit Neural Stylization](https://zhiwenfan.github.io/INS/), Fan et al., ECCV 2022| [github](https://github.com/VITA-Group/INS)  | [bibtex](./citations/INS.txt)
- [CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fields](https://cassiepython.github.io/clipnerf/), Wang et al., CVPR 2022| [github](https://github.com/cassiePython/CLIPNeRF)  | [bibtex](./citations/clipnerf.txt)
- [Local 3D Editing via 3D Distillation of CLIP Knowledge](https://arxiv.org/abs/2306.12570), Hyung et al., CVPR 2023| [github](https://github.com/lenerf/lenerf.github.io)  | [bibtex](./citations/lenerf.txt)
- [SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field](https://zju3dv.github.io/sine/), Bao et al., CVPR 2023| [github](https://github.com/zju3dv/SINE)  | [bibtex](./citations/sine.txt)
- [General Neural Gauge Fields](https://fnzhan.com/neural-gauge-fields/), Zhan et al., ICLR 2023| [github](https://github.com/fnzhan/Neural-Gauge-Fields)  | [bibtex](./citations/Neural-Gauge-Fields.txt)
</details>


<details open>
<summary>Object Category Modeling</summary>

- [FiG-NeRF: Figure Ground Neural Radiance Fields for 3D Object Category Modelling](https://fig-nerf.github.io/), Xie et al., Arxiv 2021 | [bibtex](./citations/fig-nerf.txt)
- [NeRF-Tex: Neural Reflectance Field Textures](https://developer.nvidia.com/blog/nvidia-research-nerf-tex-neural-reflectance-field-textures/), Baatz et al., EGSR 2021 | [bibtex](./citations/nerf-tex.txt)
</details>


<details open>
<summary>Multi-scale</summary>

- [Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields](https://jonbarron.info/mipnerf/), Barron et al., Arxiv 2021 | [github](https://github.com/google/mipnerf) | [bibtex](./citations/mipnerf.txt)
- [Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://jonbarron.info/mipnerf360/), Barron et al., Arxiv 2022 | [bibtex](./citations/mip-nerf-360.txt)
</details>


<details open>
<summary>Model Reconstruction</summary>

- [UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction](https://arxiv.org/abs/2104.10078), Oechsle et al., ICCV 2021 | [bibtex](./citations/unisurf.txt)
- [NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction](https://arxiv.org/abs/2106.10689), Wang et al., NeurIPS 2021 | [github](https://github.com/Totoro97/NeuS) | [bibtex](./citations/neus.txt)
- [Volume Rendering of Neural Implicit Surfaces](https://arxiv.org/abs/2106.12052), Yariv et al., NeurIPS 2021 | [github](https://github.com/ventusff/neurecon) | [bibtex](./citations/volsdf.txt)
- [NeAT: Learning Neural Implicit Surfaces with Arbitrary Topologies from Multi-view Images](https://arxiv.org/abs/2303.12012), Meng et al., CVPR 2023 | [github](https://github.com/xmeng525/NeAT) | [bibtex](./citations/neat.txt)
</details>


<details open>
<summary>Depth Estimation</summary>

- [NerfingMVS: Guided Optimization of Neural Radiance Fields for Indoor Multi-view Stereo](https://weiyithu.github.io/NerfingMVS/), Wei et al., ICCV 2021 | [bibtex](./citations/NerfingMVS.txt)
</details>


<details open>
<summary>Robotics</summary>

- [3D Neural Scene Representations for Visuomotor Control](https://3d-representation-learning.github.io/nerf-dy/), Li et al., CoRL 2021 Oral | [bibtex](./citations/nerf-dy.txt)
- [Vision-Only Robot Navigation in a Neural Radiance World](https://arxiv.org/abs/2110.00168), Adamkiewicz et al., RA-L 2022 Vol.7 No.2 | [bibtex](./citations/vision-only.txt)
- [Differentiable Physics Simulation of Dynamics-Augmented Neural Objects](https://arxiv.org/abs/2210.09420), Le Cleac'h et al., RA-L 2023 | [bibtex](./citations/dano.txt)
- [Customizable Perturbation Synthesis for Robust SLAM Benchmarking](https://arxiv.org/abs/2402.08125), Xu et al., ArXiv 2024 | [bibtex](./citations/customizable-SLAM.txt)
</details>

<details open>
<summary>Large-scale scene</summary>

- [Switch-NeRF: Learning Scene Decomposition with Mixture of Experts for Large-scale Neural Radiance Fields](https://mizhenxing.github.io/switchnerf), Mi et al., ICLR 2023 | [github](https://github.com/MiZhenxing/Switch-NeRF) | [bibtex](./citations/Switch-NeRF.txt)
- [Block-NeRF: Scalable Large Scene Neural View Synthesis](https://waymo.com/research/block-nerf/), Tancik et al., Arxiv 2022 | [bibtex](./citations/Block-NeRF.txt)
- [InfNeRF: Towards Infinite Scale NeRF Rendering with O(log n) Space Complexity](https://jiabinliang.github.io/InfNeRF.io/), Liang et al., SIGGRAPH Asia 2024 | [github](https://github.com/sail-sg/InfNeRF) | [bibtex](./citations/InfNeRF.txt)
</details>

<details open>
<summary>Pre-training</summary>

- [NeRF-MAE: Masked AutoEncoders for Self-Supervised 3D Representation Learning for Neural Radiance Fields](https://arxiv.org/pdf/2404.01300), Irshad et al., ECCV 2024 | [bibtex](./citations/nerf-mae.txt)
- [Ponder: Point Cloud Pre-training via Neural Rendering](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_Ponder_Point_Cloud_Pre-training_via_Neural_Rendering_ICCV_2023_paper.html), Huang et al., ICCV 2023 | [bibtex](./citations/ponder.txt)
- [PonderV2: Pave the Way for 3D Foundation Model with A Universal Pre-training Paradigm](https://arxiv.org/abs/2310.08586), Zhu et al., Arxiv 2023 | [github](https://github.com/OpenGVLab/PonderV2) | [bibtex](./citations/ponderv2.txt)
- [UniPAD: A Universal Pre-training Paradigm for Autonomous Driving](https://arxiv.org/abs/2310.08370), Yang et al., Arxiv 2023 | [github](https://github.com/Nightmare-n/UniPAD) | [bibtex](./citations/unipad.txt)
</details>

## Talks
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=LCTYRqW-ne8&t=10190s), Ben Mildenhall
- [Understanding and Extending Neural Radiance Fields](https://www.youtube.com/watch?v=nRyOzHpcr4Q&feature=emb_logo&ab_channel=cvprtum), Barron et al.
- [Towards Photorealism (2nd half)](https://youtu.be/Rd0nBO6--bM?t=1992), Vladlen Koltun
- [Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=dPWLybp4LL0), Matthew Tancik

## Implementations
#### Tensorflow
- [NeRF](https://github.com/bmild/nerf), Mildenhall et al., 2020 | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [Nerual-Radiance-Fields](https://www.kaggle.com/code/ritzraha/nerual-radiance-fields), [@ariG23498](https://twitter.com/ariG23498), [@ritwik_raha](https://twitter.com/ritwik_raha), 2022

#### PyTorch
- [NeRF-PyTorch](https://github.com/yenchenlin/nerf-pytorch), Yen-Chen Lin, 2020 | [bibtex](./citations/pytorch-nerf.txt)
- [NeRF-PyTorch-Lighting](https://github.com/kwea123/nerf_pl), [@kwea123](https://github.com/kwea123), 2020
- [NeRF-W](https://github.com/kwea123/nerf_pl/tree/nerfw), [@kwea123](https://github.com/kwea123), 2021
- [NeRF-PyTorch3D](https://github.com/facebookresearch/pytorch3d/tree/master/projects/nerf), [@facebookresearch](https://github.com/facebookresearch), 2020

#### Jax
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf), Deng et al., 2020 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/NeRF-and-Beyond.bib#L55-L60)
- [Mip-NeRF](https://github.com/google/mipnerf), [@google](https://github.com/google), 2021 | [bibtex](./citations/mipnerf.txt)
- [[Jax + Flax] Minimal Implementation of NeRF](https://www.kaggle.com/code/sauravmaheshkar/jax-flax-minimal-implementation-of-nerf), [@soumikrakshit](https://www.kaggle.com/soumikrakshit), [@sauravmaheshkar](https://www.kaggle.com/sauravmaheshkar), 2022

#### Libraries
- [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022

## License
MIT
