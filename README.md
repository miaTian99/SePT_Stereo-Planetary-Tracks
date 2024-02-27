# SePT_Stereo-Planetary-Tracks
This repo releases a dataset to challenge object SLAM algorithms in an unstructured, weakly textured, and lunar terrain environment. All the data are collected from the Unreal Engine 4 with AirSim.
  ![Lunar GUI](https://github.com/miaTian99/SePT_Stereo-Planetary-Tracks/blob/main/assets/lunar%20GUI.png)
## 1. Simulation Engine:
- Unreal Engine Version: 4.27.2
- AirSim Sensors: Stereo Cameras (150 mm baseline), Lidar (128 channels), IMU
- Setting Files: [Settings for lunar rover exploration](https://github.com/miaTian99/SePT_Stereo-Planetary-Tracks/blob/main/assets/settings.json)
- Offical Guidelines: [AirSim](https://microsoft.github.io/AirSim/) 
## 2. Dataset Download Link:
- SePT01 track: [Google Drive](https://drive.google.com/uc?export=download&id=11mJYHrdUd1CwxPjvXIs3pl1Rz6kTRJLI)
- SePT02 track: [Google Drive](https://drive.google.com/uc?export=download&id=1Ncb6DRubtPpQlUpklbLCODtnBL9co1Tm)
- SePT03 track: [Google Drive](https://drive.google.com/uc?export=download&id=14D_nS-BwYwpmSYTPNvXvEU7W9qTg2xQm)
- SePT04 track: [Google Drive](https://drive.google.com/uc?export=download&id=1Qq2U2tW_siSp2Ns8P0MM10ranBZ1y7Y1)
## 3. Structure:
Similar to the [Euroc dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets), we structured our SePT dataset which can be tested in a typical SLAM framework (e.g., ORB-SLAMx, CubeSLAM).

## 4. Acknowledgement:
Thanks to work: [Image-Matching-Toolbox](https://github.com/GrumpyZhou/image-matching-toolbox), [SAM](https://github.com/facebookresearch/segment-anything), and [EAO-SLAM](https://github.com/yanmin-wu/EAO-SLAM).
- Q. Zhou, T. Sattler and L. Leal-Taixé, "Patch2Pix: Epipolar-Guided Pixel-Level Correspondences," CVPR 2021, Nashville, TN, USA, 2021, pp. 4667-4676. [Paper](https://arxiv.org/abs/2012.01909/). 
- Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and et al., "Segment Anything," 2023, CoRR. [paper](https://ai.meta.com/research/publications/segment-anything/).
- Y. Wu, Y. Zhang, D. Zhu, Y. Feng, S. Coleman and D. Kerr, "EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association," IROS 2020, Las Vegas, NV, USA, 2020, pp. 4966-4973.
[Paper](https://ieeexplore.ieee.org/abstract/document/9341757).
## 5. Contact:
- Author: Yaolin Tian (email: tianyaolin21@mails.ucas.ac.cn)
- paper is under submitting
```
@article{Yaolin2024,
  title={LO-SLAM: Lunar Object-centric SLAM using Point Prompted SAM for Data Association},
  author={Yaolin Tian, Xue Wan, Shengyang Zhang, Jianhong Zuo, Yadong Shao, and Mengmeng Yang},
  year={2024}
}
```
