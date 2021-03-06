# Cross-Modality 3D Object Detection (CM3DDet)

:herb: **[Cross-Modality 3D Object Detection](https://arxiv.org/abs/2008.10436)**

Ming Zhu, Chao Ma, Pan Ji, Xiaokang Yang

*IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021.*

## Introduction

- In this paper, we focus on exploring the fusion of images and point clouds for 3D object detection in view of the complementary nature of the two modalities, i.e., images possess more semantic information while point clouds specialize in distance sensing.
<img src="https://github.com/VISION-SJTU/Cross-modality-3d-object-detection/blob/main/paper_materials/main_architecture.png" width='1500'/><br/>

## Results

- We evaluate our proposed 3D object detector on the public KITTI [1] benchmark and compare it with previous state-of-the-art methods in both 3D object detection and 2D object detection tasks. Extensive ablation study is also conducted which evaluates how different components affect our model.
<img src="https://github.com/VISION-SJTU/Cross-modality-3d-object-detection/blob/main/paper_materials/main_results.png" width='1500'/><br/>

- To further analyze the ability of our proposed deeply fused multi-modal 3D object detection method, we conduct extensive ablation studies on the KITTI train/val set to explore the effects of our components.
<img src="https://github.com/VISION-SJTU/Cross-modality-3d-object-detection/blob/main/paper_materials/ablation_study.png" width='1500'/><br/>

## Code
:herb: **The code of Cross-Modality 3D Object Detection is released!!**
- We adopt PointRCNN as our baseline.
- The useage is same with PointRCNN, you can refer to <https://github.com/sshaoshuai/PointRCNN>


## Citation
If any part of our paper and code is helpful to your work, please generously citing: 
```
@inproceedings{zhu2021cross,
  title={Cross-modality 3d object detection},
  author={Zhu, Ming and Ma, Chao and Ji, Pan and Yang, Xiaokang},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={3772--3781},
  year={2021}
}
```

Thank you :)

## Reference
[1] Andreas Geiger, Philip Lenz, and Raquel Urtasun. Are we ready for autonomous driving? the kitti vision benchmark suite. In 2012 IEEE Conference on Computer Vision and Pattern Recognition, pages 3354???3361. IEEE, 2012.

We choose PointRCNN as our baseline. The original code is listed as follows:
- PointRCNN: https://github.com/sshaoshuai/PointRCNN

Thanks for their wonderful work!

## License
Licensed under an MIT license.
