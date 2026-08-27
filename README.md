# Awesome 3D Gaussian Splatting Resources with stars

3D Gaussian Splatting (3DGS) opens a new window for using neural rendering for real applications.
This repo is intended to provide a collection of papers that are related to 3DGS, but not necessarily use 3DGS.

In general, 3D Gaussian Splatting can be considered as a variant of NeRF. This repo will more focused on the practical side of NeRF, e.g. realtime, compatibility with Unity/Unreal, ease of editing, etc.

Other resources:

* [Dynamic NeRF](./dynamic.md)
* [awesome-LLMs-finetuning](https://github.com/pdaicode/awesome-LLMs-finetuning) ⭐ 120 | 🐛 3 | 📅 2025-01-12

**Verified**: Papers listed with `[+]` have been verfied by myself or colleagues. The code is runnable. Please leave an issue if you need help on setting up.

**If you have any additions or suggestions, feel free to contribute. Everything is welcome.**

## Most Recent Update & News:

[Complete List](./UpdateLog.md)

* Aug 2024: added papers for improving NeRF speed
* May 2024: added **2024** section, added **LLM** subsection
* Dec 2023: added **verified** section
* 26 Nov 2023: added more details for cumstom data.
* Nov 2023: Start a separate page for [**NeRF**](./nerf)
* 29 Oct 2023: Start a separate page for [**Dynamic NeRF**](./dynamic)

### CVPR 2024 word cloud:

<img src="images/cvpr2024.png" alt="cvpr2024" width="500" >

## 1. 3D Reconstruction

* **3D Gaussian Splatting for Real-Time Radiance Field Rendering**,
  [Bernhard Kerbl](https://scholar.google.at/citations?user=jeasMB0AAAAJ\&hl=en), [Georgios Kopanas](https://scholar.google.com/citations?user=QLWLLHMAAAAJ), [Thomas Leimkühler](https://www-sop.inria.fr/members/Thomas-Sebastian.Leimkuhler/), [George Drettakis](https://scholar.google.fr/citations?user=LGo5J4IAAAAJ\&hl=en), SIGGRAPH 2023 (Best Paper).
  \[[📄 Paper (Low Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf) | [📄 Paper (High Resolution)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [🌐 Project Page](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [💻 Code](https://github.com/graphdeco-inria/gaussian-splatting) ⭐ 23,468 | 🐛 713 | 🌐 Python | 📅 2025-10-17 | [🎥 Short Presentation](https://youtu.be/T_kXY43VZnk?si=DrkbDFxQAv5scQNT) | [🎥 Explanation Video](https://www.youtube.com/live/xgwvU7S0K-k?si=edF8NkYtsRbgTbKi) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/gaussian_splatting_colab.ipynb)]

### Other 3D Papers

* High-quality Surface Reconstruction using Gaussian Surfels. \[[Paper](https://arxiv.org/pdf/2404.17774) | [Code](https://github.com/turandai/gaussian_surfels) ⭐ 682 | 🐛 7 | 🌐 Python | 📅 2025-06-17]
* Toon3D: Seeing Cartoons from a New Perspective, 2024. \[[Paper](https://arxiv.org/abs/2405.10320) | [Project](https://toon3d.studio/) | [Code](https://github.com/ethanweber/toon3d) ⭐ 225 | 🐛 0 | 🌐 Python | 📅 2025-04-05]
* Texture Generation on 3D Meshes with Point-UV Diffusion, 2024. \[[Paper](https://arxiv.org/abs/2308.10490) | [Project](https://cvmi-lab.github.io/Point-UV-Diffusion/) | [Code](https://github.com/CVMI-Lab/Point-UV-Diffusion) ⭐ 219 | 🐛 7 | 🌐 C++ | 📅 2023-12-06]
* N-BVH: Neural ray queries with bounding volume hierarchies, SIGGRAPH 2024. \[[Paper](https://weiphil.s3.eu-central-1.amazonaws.com/neural_bvh.pdf) | [Project](https://weiphil.github.io/portfolio/neural_bvh) | [Code](https://github.com/WeiPhil/nbvh) ⭐ 140 | 🐛 0 | 🌐 C++ | 📅 2025-12-03]

### 2024

**General**

* `[+]` [2DGS](./colabs/2DGS.ipynb): 2D Gaussian Splatting for Geometrically Accurate Radiance Fields, SIGGRAPH 2024. \[[Paper](https://arxiv.org/abs/2403.17888) | [Project](https://surfsplatting.github.io/) | [Code](https://github.com/hbb1/2d-gaussian-splatting) ⭐ 3,280 | 🐛 127 | 🌐 Python | 📅 2026-08-25]

* MVSplat: Efficient 3D Gaussian Splatting from Sparse Multi-View Images, ECCV2024. \[[Paper](https://arxiv.org/pdf/2403.14627) | [Project](https://github.com/donydchen/mvsplat) ⭐ 1,297 | 🐛 47 | 🌐 Python | 📅 2026-05-06]

* LangSplat: 3D Language Gaussian Splatting, CVPR 2024 (Highlight). \[[Project](https://langsplat.github.io/) | [Code](https://github.com/minghanqin/LangSplat) ⭐ 1,078 | 🐛 46 | 🌐 Python | 📅 2025-10-10]

* Triplane Meets Gaussian Splatting: Fast and Generalizable Single-View 3D Reconstruction with Transformers, CVPR 2024. \[[Project](https://zouzx.github.io/TriplaneGaussian/) | [Code](https://github.com/VAST-AI-Research/TriplaneGaussian) ⭐ 927 | 🐛 23 | 🌐 Python | 📅 2024-03-05]

* GaussianPro: 3D Gaussian Splatting with Progressive Propagation, ICML 2024. \[[Paper](https://arxiv.org/abs/2402.14650) | [Project](https://github.com/kcheng1021/GaussianPro) ⭐ 844 | 🐛 53 | 🌐 Python | 📅 2025-08-24]

* COLMAP-Free 3D Gaussian Splatting, CVPR2024. \[[Paper](https://arxiv.org/abs/2312.07504) | [Project](https://oasisyang.github.io/colmap-free-3dgs/) | [Code](https://github.com/NVlabs/CF-3DGS) ⭐ 788 | 🐛 46 | 🌐 Python | 📅 2024-08-22]

* On Scaling Up 3D Gaussian Splatting Training, 2024. \[[Project](https://daohanlu.github.io/scaling-up-3dgs/) | [Code](https://github.com/nyu-systems/Grendel-GS) ⭐ 681 | 🐛 36 | 🌐 Python | 📅 2025-09-24]

* GPS-Gaussian: Generalizable Pixel-wise 3D Gaussian Splatting for Real-time Human Novel View Synthesis, CVPR 2024. \[[Project](https://shunyuanzheng.github.io/GPS-Gaussian) | [Code](https://github.com/aipixel/GPS-Gaussian) ⭐ 626 | 🐛 48 | 🌐 Python | 📅 2025-07-02]

* MVSGaussian: Fast Generalizable Gaussian Splatting Reconstruction from Multi-View Stereo, ECCV 2024. \[[Project](https://mvsgaussian.github.io/) | [Code](https://github.com/TQTQliu/MVSGaussian) ⭐ 566 | 🐛 18 | 🌐 Python | 📅 2026-02-25]

* GS-IR: 3D Gaussian Splatting for Inverse Rendering, CVPR 2024. \[[Project](https://lzhnb.github.io/project-pages/gs-ir.html) | [Code](https://github.com/lzhnb/GS-IR) ⭐ 446 | 🐛 22 | 🌐 Python | 📅 2024-07-16]

* Deblur-GS: 3D Gaussian Splatting from Camera Motion Blurred Images, I3D 2024. \[[Paper](https://chaphlagical.icu/Deblur-GS/static/paper/Deblur_GS_author_version.pdf) | [Code](https://github.com/Chaphlagical/Deblur-GS) ⭐ 413 | 🐛 18 | 🌐 Python | 📅 2024-05-16]

* GaussianShader: 3D Gaussian Splatting with Shading Functions for Reflective Surfaces, CVPR 2024. \[[Project](https://asparagus15.github.io/GaussianShader.github.io/) | [Code](https://github.com/Asparagus15/GaussianShader) ⭐ 409 | 🐛 22 | 🌐 C++ | 📅 2024-05-20]

* bsGS: Recovering Fine Details for 3D Gaussian Splatting, ACM MM 2024. [Code](https://github.com/Asparagus15/GaussianShader) ⭐ 409 | 🐛 22 | 🌐 C++ | 📅 2024-05-20

* Deblurring 3D Gaussian Splatting, ECCV 2024. \[[Project](https://benhenryl.github.io/Deblurring-3D-Gaussian-Splatting/) | [Code](https://github.com/benhenryL/Deblurring-3D-Gaussian-Splatting) ⭐ 341 | 🐛 15 | 🌐 Python | 📅 2024-07-03]

* Depth-Regularized Optimization for 3D Gaussian Splatting in Few-Shot Image, CVPRW 2024 (3DMV). \[[Project](https://robot0321.github.io/DepthRegGS/index.html) | [Code](https://github.com/robot0321/DepthRegularizedGS) ⭐ 274 | 🐛 22 | 🌐 Python | 📅 2024-09-27]

* Gaussian in the Wild: 3D Gaussian Splatting for Unconstrained Image Collections, 2024. \[[Project](https://eastbeanzhang.github.io/GS-W/) | [Code](https://github.com/EastbeanZhang/Gaussian-Wild) ⭐ 201 | 🐛 6 | 🌐 Python | 📅 2025-03-13]

* Spec-Gaussian: Anisotropic View-Dependent Appearance for 3D Gaussian Splatting, 2024. \[[Project](https://ingra14m.github.io/Spec-Gaussian-website/) | [Code](https://github.com/ingra14m/Spec-Gaussian) ⭐ 180 | 🐛 21 | 🌐 Python | 📅 2024-11-15]

* DarkGS: Learning Neural Illumination and 3D Gaussians Relighting for Robotic Exploration in the Dark, \[[Paper](https://arxiv.org/abs/2403.10814) | [Project](https://github.com/tyz1030/darkgs) ⭐ 119 | 🐛 9 | 🌐 Python | 📅 2025-01-29]

* GaussianVTON: 3D Human Virtual Try-ON via Multi-Stage Gaussian Splatting Editing with Image Prompting, \[[Paper](https://arxiv.org/abs/2405.07472) | [Code](https://github.com/HaroldChen19/GaussianVTON) ⭐ 88 | 🐛 1 | 🌐 Python | 📅 2024-06-04]

* VR-GS: A Physical Dynamics-Aware Interactive Gaussian Splatting System in Virtual Reality, \[[Paper](https://arxiv.org/abs/2401.16663) | [Project](https://yingjiang96.github.io/VR-GS/)]

* DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting,  \[[Paper](https://arxiv.org/abs/2404.06903) | [Project](https://dreamscene360.github.io/)]

* FreGS: 3D Gaussian Splatting with Progressive Frequency Regularization, CVPR 2024. \[[Paper](https://arxiv.org/abs/2403.06908) | [Project](https://rogeraigc.github.io/FreGS-Page/)]

* GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting, CVPR 2024. \[[Project](https://gs-slam.github.io/)]

* SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering, CVPR 2024.

* pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction, CVPR 2024.

* Surfel-based Gaussian Inverse Rendering for Fast and Relightable Dynamic Human Reconstruction from Monocular Video, 2024. \[[Paper](https://arxiv.org/pdf/2407.15212) | [Project](https://gs-ia.github.io/)]

* GaussMR: Interactive Gaussian Splatting Sandbox with GPU Particles and Signed Distance Fields, SIGGRAPH 2024. \[[Paper](https://dl.acm.org/doi/pdf/10.1145/3641521.3664405?casa_token=GXIJMXbeT1sAAAAA:Pqv_zjOe9uXiTSVUEj03Hz8lDRAynMJPDIAuLBI_unPN9gG06KI_Lks6SJJFgAG4CLKRY6wFpBR5cQ)]

* GS-LRM: Large Reconstruction Model for 3D Gaussian Splatting, 2024. \[[Project](https://sai-bi.github.io/project/gs-lrm/)]

* WildGaussians: 3D Gaussian Splatting in the Wild, 2024. \[[Project](https://wild-gaussians.github.io/)]

**Literature Review**

* Recent advances in 3D Gaussian splatting, Computational Visual Media, 2024. \[[Paper](https://link.springer.com/article/10.1007/s41095-024-0436-y)]
* 3D Gaussian Splatting as New Era: A Survey, IEEE Transactions on Visualization and Computer Graphics, 2024. \[[Paper](https://ieeexplore.ieee.org/abstract/document/10521791?casa_token=CmDrVUqmo1kAAAAA:3ekE_T2xp9gWMActz0wLQ3Z6m7cdmyomp0ubYIl-nVZyheke22vbIoCKjId1jouaI4m7rm-UFQ)]
* Gaussian Splatting: 3D Reconstruction and Novel View Synthesis: A Review, IEEE Access, 2024. \[[Paper](https://ieeexplore.ieee.org/abstract/document/10545567)]

**[NeRF (Improving speed & efficiency)](./nerf.md)**

* How Far Can We Compress Instant-NGP-Based NeRF? CVPR 2024. \[[Project](https://yihangchen-ee.github.io/project_cnc/) | [code](https://github.com/YihangChen-ee/CNC) ⭐ 56 | 🐛 1 | 🌐 Cuda | 📅 2025-11-09]
* FastSR-NeRF: Improving NeRF Efficiency on Consumer Devices With a Simple Super-Resolution Pipeline, WACV 2024. \[[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Lin_FastSR-NeRF_Improving_NeRF_Efficiency_on_Consumer_Devices_With_a_Simple_WACV_2024_paper.pdf)]
* HybridNeRF: Efficient Neural Rendering via Adaptive Volumetric Surfaces, CVPR 2024. [Project](https://haithemturki.com/hybrid-nerf/)

**[Dynamic](https://github.com/pdaicode/awesome-dynamic-NeRF) ⭐ 67 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-04-21**

* Shape of Motion: 4D Reconstruction from a Single Video, 2024. \[[Project](https://shape-of-motion.github.io/) | [Code](https://github.com/vye16/shape-of-motion/) ⭐ 1,302 | 🐛 58 | 🌐 Python | 📅 2025-08-02]
* CoGS : Controllable Gaussian Splatting, CVPR 2024. \[[Project](https://cogs2024.github.io/) | [Code](https://github.com/Heng14/CoGS/tree/main) ⭐ 67 | 🐛 4 | 📅 2023-12-13]
* MoSca: Dynamic Gaussian Fusion from Casual Videos via 4D Motion Scaffolds, 2024. [Project](https://www.cis.upenn.edu/~leijh/projects/mosca/)
* Dynamic Gaussian Marbles for Novel View Synthesis of Casual Monocular Videos, 2024.

**LLM & 3D**

* Comp4D: LLM-Guided Compositional 4D Scene Generation, \[[Paper](https://arxiv.org/abs/2403.16993) | [Project](https://vita-group.github.io/Comp4D/)]
* GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guidedGenerative Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2402.07207) | [Project](https://gala3d.github.io/)]

**SLAM & Sensor Fusion**

* SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM, CVPR 2024. \[[Paper](https://arxiv.org/pdf/2312.02126.pdf) | [Code](https://github.com/spla-tam/SplaTAM) ⭐ 2,186 | 🐛 53 | 🌐 Python | 📅 2024-06-19]
* Gaussian Splatting SLAM, CVPR 2024 \[[Paper](https://arxiv.org/abs/2312.06741) | [Code](https://github.com/muskie82/MonoGS) ⭐ 2,149 | 🐛 101 | 🌐 Python | 📅 2024-08-07]
* Gaussian-SLAM: Photo-realistic Dense SLAM with Gaussian Splatting, \[[Paper](https://ivi.fnwi.uva.nl/cv/paper/GaussianSLAM.pdf) | [Code](https://github.com/VladimirYugay/Gaussian-SLAM) ⭐ 1,182 | 🐛 1 | 🌐 Python | 📅 2024-07-03]
* Photo-SLAM: Real-time Simultaneous Localization and Photorealistic Mapping for Monocular, Stereo, and RGB-D Cameras, \[[Paper](https://arxiv.org/pdf/2311.16728.pdf) | [Code](https://github.com/HuajianUP/Photo-SLAM) ⭐ 760 | 🐛 38 | 🌐 C++ | 📅 2024-06-12]
* RGBD GS-ICP SLAM, \[[Paper](https://arxiv.org/abs/2403.12550) | [Code](https://github.com/Lab-of-AI-and-Robotics/GS_ICP_SLAM) ⭐ 534 | 🐛 36 | 🌐 C++ | 📅 2026-06-20]

**Compression & Efficiency**

* GaussianPro: 3D Gaussian Splatting with Progressive Propagation, \[[Paper](https://arxiv.org/abs/2402.14650) | [Code](https://github.com/kcheng1021/GaussianPro) ⭐ 844 | 🐛 53 | 🌐 Python | 📅 2025-08-24]
* Compressed 3D Gaussian Splatting for Accelerated Novel View Synthesis, CVPR 2024. \[[Project](https://keksboter.github.io/c3dgs/) | [Code](https://github.com/KeKsBoTer/c3dgs) ⭐ 404 | 🐛 11 | 🌐 Python | 📅 2025-09-17]
* HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression, \[[Paper](https://arxiv.org/abs/2403.14530) | [Code](https://github.com/YihangChen-ee/HAC) ⭐ 336 | 🐛 14 | 🌐 Python | 📅 2025-11-09]
* SUNDAE: Spectrally Pruned Gaussian Fields with Neural Compensation, \[[Paper](https://runyiyang.github.io/data/SUNDAE.pdf) | [Code](https://github.com/RunyiYang/SUNDAE) ⭐ 163 | 🐛 10 | 🌐 C++ | 📅 2024-06-14]
* InstantSplat: Unbounded Sparse-view Pose-free Gaussian Splatting in 10 Seconds, \[[Paper](https://arxiv.org/pdf/2403.20309.pdf)
* Reducing the Memory Footprint of 3D Gaussian Splatting, \[[Paper](https://repo-sam.inria.fr/fungraph/reduced_3dgs/reduced_3DGS_i3d.pdf) | [Project](https://repo-sam.inria.fr/fungraph/reduced_3dgs/#:~:text=Our%20approach%20to%20reduce%20the,is%20applied%20as%20post%2Dprocessing.)]

### 2023

Speed & Efficiency

* `[+]` SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering, 2023. \[[Paper](https://arxiv.org/abs/2311.12775) | [Code](https://github.com/Anttwo/SuGaR) ⭐ 3,496 | 🐛 187 | 🌐 C++ | 📅 2024-09-24]
* `[+]` LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS, 2023. \[[Paper](https://arxiv.org/abs/2311.17245) | [Code](https://github.com/VITA-Group/LightGaussian) ⭐ 816 | 🐛 18 | 🌐 Python | 📅 2024-12-30]
* Compact 3D Gaussian Representation for Radiance Field, \[[Paper](https://github.com/maincold2/Compact-3DGS/blob/main) ⭐ 500 | 🐛 13 | 🌐 Python | 📅 2024-09-27 | [Code](https://github.com/maincold2/Compact-3DGS) ⭐ 500 | 🐛 13 | 🌐 Python | 📅 2024-09-27]
* Compact3D: Compressing Gaussian Splat Radiance Field Models with Vector Quantization, \[[Paper](https://arxiv.org/abs/2311.18159) | [Code](https://github.com/UCDvision/compact3d) ⭐ 228 | 🐛 7 | 🌐 Python | 📅 2024-09-26]

Quality

* Mip-Splatting: Alias-free 3D Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2311.16493) | [Code](https://github.com/autonomousvision/mip-splatting) ⭐ 1,467 | 🐛 32 | 🌐 Python | 📅 2024-12-17]
* Multi-Scale 3D Gaussian Splatting for Anti-Aliased Rendering, \[[Paper](https://arxiv.org/abs/2311.17089) | [Code](https://github.com/JokerYan/MS-GS/tree/main) ⭐ 41 | 🐛 2 | 🌐 Python | 📅 2025-01-25]
* FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information, [Paper](https://arxiv.org/abs/2311.17874)
* COLMAP-Free 3D Gaussian Splatting, \[[Paper](https://arxiv.org/pdf/2312.07504) | [Project](https://oasisyang.github.io/colmap-free-3dgs/)]
* NeuSG: Neural Implicit Surface Reconstruction with 3D Gaussian Splatting Guidance, [Paper](https://arxiv.org/abs/2312.00846)
* Depth-Regularized Optimization for 3D Gaussian Splatting in Few-Shot Images, [Paper](https://arxiv.org/pdf/2311.13398)
* GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting, [Paper](https://arxiv.org/abs/2311.11700)

Reflection & Relighting

* GaussianShader: 3D Gaussian Splatting with Shading Functions for Reflective Surfaces, \[[Paper](https://arxiv.org/abs/2311.17977) | [Code](https://github.com/Asparagus15/GaussianShader) ⭐ 409 | 🐛 22 | 🌐 C++ | 📅 2024-05-20]
* Relightable 3D Gaussian: Real-time Point Cloud Relighting with BRDF Decomposition and Ray Tracing, [Paper](https://arxiv.org/abs/2311.16043)

Others

* Splatter Image: Ultra-Fast Single-View 3D Reconstruction, \[[Paper](https://arxiv.org/abs/2312.13150) | [Code](https://github.com/szymanowiczs/splatter-image) ⭐ 1,106 | 🐛 19 | 🌐 Python | 📅 2024-08-17]
* pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction, \[[Paper](https://arxiv.org/abs/2312.12337) | [Project Page](https://davidcharatan.com/pixelsplat/)]
* Volume Feature Rendering for Fast Neural Radiance Field Reconstruction, NeurIPS 2023.

## 2. Dynamic 3D Gaussian Splatting:

* `[+]` 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering, \[[Paper](https://arxiv.org/pdf/2310.08528.pdf) | [Project Page](https://guanjunwu.github.io/4dgs/) | [Code](https://github.com/hustvl/4DGaussians) ⭐ 3,896 | 🐛 135 | 🌐 Jupyter Notebook | 📅 2024-10-27 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pdaicode/awesome-3dgs/blob/master/colabs/4DGaussians.ipynb)]
* Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, \[[Paper](https://dynamic3dgaussians.github.io/paper.pdf) | [Project Page](https://dynamic3dgaussians.github.io/) | [Code](https://github.com/JonathonLuiten/Dynamic3DGaussians) ⭐ 2,292 | 🐛 32 | 🌐 Python | 📅 2023-12-22 | [Explanation Video](https://www.youtube.com/live/hDuy1TgD8I4?si=6oGN0IYnPRxOibpg)]
* `[+]` 4K4D: Real-Time 4D View Synthesis at 4K Resolution. \[[Paper](https://drive.google.com/file/d/1Y-C6ASIB8ofvcZkyZ_Vp-a2TtbiPw1Yx/view?usp=sharing) | [Project Page](https://zju3dv.github.io/4k4d/) | [Code (Inference)](https://github.com/zju3dv/4K4D) ⭐ 1,807 | 🐛 47 | 🌐 Python | 📅 2024-06-07]]
* Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction, \[[Paper](https://arxiv.org/pdf/2309.13101.pdf) | [Project Page](https://ingra14m.github.io/Deformable-Gaussians/) | [Code](https://github.com/ingra14m/Deformable-3D-Gaussians) ⭐ 1,255 | 🐛 64 | 🌐 Python | 📅 2024-06-25]
* Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting, [Paper](https://arxiv.org/pdf/2310.10642.pdf)
* GauFRe: Gaussian Deformation Fields for Real-time Dynamic Novel View Synthesis, [Project Page](https://lynl7130.github.io/gaufre/index.html)

## 3. Generative 3D Gaussian Splatting:

Papers with shared code are ranked higher in this list

* DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation, [Paper](https://arxiv.org/pdf/2309.16653.pdf) | [Project Page](https://dreamgaussian.github.io/) | [Code](https://github.com/dreamgaussian/dreamgaussian) ⭐ 4,354 | 🐛 134 | 🌐 Python | 📅 2024-01-02 | [Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)]
* Text-to-3D using Gaussian Splatting, \[[📄 Paper](https://arxiv.org/pdf/2309.16585.pdf) | [Project Page](https://gsgen3d.github.io/) | [Code](https://github.com/gsgen3d/gsgen) ⭐ 845 | 🐛 37 | 🌐 Python | 📅 2024-01-07 | [Explanation Video](https://www.youtube.com/live/l956ye13F8M?si=ZkvFL_lsY5OQUB7e)]
* Gsgen: Text-to-3D using Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2309.16585) | [Project Page](https://gsgen3d.github.io/) | [Code](https://github.com/gsgen3d/gsgen) ⭐ 845 | 🐛 37 | 🌐 Python | 📅 2024-01-07]
* GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors, \[[Paper](https://arxiv.org/pdf/2310.08529.pdf) | [Project Page](https://taoranyi.com/gaussiandreamer/) | [Code](https://github.com/hustvl/GaussianDreamer) ⭐ 831 | 🐛 18 | 🌐 Python | 📅 2025-01-13]
* DreamGaussian4D: Generative 4D Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2312.17142) | [Code](https://github.com/jiawei-ren/dreamgaussian4d) ⭐ 620 | 🐛 11 | 🌐 Python | 📅 2024-06-10]
* Learn to Optimize Denoising Scores for 3D Generation: A Unified and Improved Diffusion Prior on NeRF and 3D Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2312.04820) | [Code](https://github.com/yangxiaofeng/LODS) ⭐ 72 | 🐛 1 | 🌐 Python | 📅 2024-07-11]
* LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes, \[[Paper](https://arxiv.org/abs/2311.13384) | [Project Page](https://luciddreamer-cvlab.github.io/)]
* PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics, \[[Paper](https://arxiv.org/abs/2311.12198) | [Project Page](https://xpandora.github.io/PhysGaussian/)]
* HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting, \[[Paper](https://arxiv.org/abs/2311.17061)]

## 4. Digital Avatar

* GauHuman: Articulated Gaussian Splatting from Monocular Human Videos, \[[Paper](https://arxiv.org/pdf/2312.02973.pdf) | [Project Page](https://skhu101.github.io/GauHuman/) | [Code](https://github.com/skhu101/GauHuman) ⭐ 426 | 🐛 2 | 🌐 Python | 📅 2024-07-04]
* Gaussian Shell Maps for Efficient 3D Human Generation, \[[Paper](https://arxiv.org/abs/2311.17857) | [Code](https://github.com/computational-imaging/GSM) ⭐ 228 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2024-01-03]
* HeadGaS: Real-Time Animatable Head Avatars via 3D Gaussian Splatting, [Paper](https://arxiv.org/abs/2312.02902)
* HUGS: Human Gaussian Splats, [Paper](https://arxiv.org/abs/2311.17910)
* SplatArmor: Articulated Gaussian splatting for animatable humans from monocular RGB videos, [Paper](https://arxiv.org/pdf/2311.10812)
* Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling, [Paper](https://arxiv.org/pdf/2311.16096.pdf)
* Human101: Training 100+FPS Human Gaussians in 100s from 1 View, [Paper](https://arxiv.org/abs/2312.15258)
* Deformable 3D Gaussian Splatting for Animatable Human Avatars, [Paper](https://arxiv.org/abs/2312.15059)

## 5. LLM 3D Gaussian Splatting

* LangSplat: 3D Language Gaussian Splatting, \[[Paper](https://arxiv.org/pdf/2312.16084.pdf) | [Project Page](https://langsplat.github.io/) | [Code](https://github.com/minghanqin/LangSplat) ⭐ 1,078 | 🐛 46 | 🌐 Python | 📅 2025-10-10]

## 6. 3D Gaussian Viewers

### Colab

* [NeRFStudio](https://github.com/nerfstudio-project/nerfstudio/blob/main/colab/demo.ipynb) ⭐ 11,936 | 🐛 954 | 🌐 Python | 📅 2025-07-29
* [Camenduru](https://github.com/camenduru/gaussian-splatting-colab) ⭐ 513 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2023-12-19

### Training

* [nerfstudio: python/CUDA](https://github.com/nerfstudio-project/gsplat) ⭐ 5,592 | 🐛 361 | 🌐 Python | 📅 2026-08-20
* [fast: C++/CUDA](https://github.com/MrNeRF/gaussian-splatting-cuda) ⭐ 3,602 | 🐛 206 | 🌐 C++ | 📅 2026-08-27
* [Taichi 3D Gaussian Splatting](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting) ⭐ 754 | 🐛 38 | 🌐 Jupyter Notebook | 📅 2024-03-12

### Viewers

* [Playcanvas](https://github.com/playcanvas/supersplat) ⭐ 9,908 | 🐛 107 | 🌐 TypeScript | 📅 2026-08-27
* [WebGL Viewer 1](https://github.com/antimatter15/splat) ⭐ 3,066 | 🐛 37 | 🌐 JavaScript | 📅 2025-11-16
* [Three.js](https://github.com/mkkellogg/GaussianSplats3D) ⭐ 2,872 | 🐛 97 | 🌐 JavaScript | 📅 2025-10-19
* [WebGL Viewer 2](https://github.com/cvlab-epfl/gaussian-splatting-web) ⭐ 667 | 🐛 12 | 🌐 TypeScript | 📅 2024-03-13
* [A-Frame](https://github.com/quadjr/aframe-gaussian-splatting) ⭐ 227 | 🐛 9 | 🌐 JavaScript | 📅 2023-12-20
* [Luma AI (WebGL)](https://lumalabs.ai/luma-web-library)

### Game Engines

* [Unity Implementation](https://github.com/aras-p/UnityGaussianSplatting) ⭐ 3,390 | 🐛 43 | 🌐 C# | 📅 2025-10-17
* [Blender](https://github.com/ReshotAI/gaussian-splatting-blender-addon) ⭐ 587 | 🐛 31 | 🌐 Python | 📅 2024-08-30

## 6. Documents

### Product

* [Luma AI](https://lumalabs.ai/interactive-scenes)
* [Polycam](https://poly.cam/gaussian-splatting)

### Blog Posts

1. [Gaussian Splatting is pretty cool](https://aras-p.info/blog/2023/09/05/Gaussian-Splatting-is-pretty-cool/)
2. [Making Gaussian Splats smaller](https://aras-p.info/blog/2023/09/13/Making-Gaussian-Splats-smaller/)
3. [Making Gaussian Splats more smaller](https://aras-p.info/blog/2023/09/27/Making-Gaussian-Splats-more-smaller/)

### Tutorial Videos

1. [Getting Started with 3DGS](https://youtu.be/UXtuigy_wYc?si=j1vfORNspcocSH-b)
2. [How to view 3DGS Scenes in Unity](https://youtu.be/5_GaPYBHqOo?si=6u9j1HqXwF_5WSUL)

## Reference

* [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) ⭐ 23,468 | 🐛 713 | 🌐 Python | 📅 2025-10-17
* [MrNeRF](https://github.com/MrNeRF/awesome-3D-gaussian-splatting/tree/main) ⭐ 8,838 | 🐛 4 | 🌐 Python | 📅 2026-08-18
* <https://github.com/yangjiheng/nerf_and_beyond_docs> ⭐ 1,166 | 🐛 0 | 📅 2024-12-26
* <https://dellaert.github.io/NeRF22/>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
