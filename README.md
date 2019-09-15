# MegDet3D
MEGVII's pytorch version 3D Object Detection codebase.

## Introduction
MegDet3D is the first 3D Object Detection toolbox which provides off the box implementations of many 3D object detection algorithms such as PointPillars, SECOND, PointRCNN, PIXOR, etc, as well as state-of-the-art methods on major benchmarks like KITTI(ViP) and nuScenes(CBGS). Key features of MegDet3D include the following apects:
* Multi Datasets Support: KITTI, nuScenes, Lyft, waymo
* Point-based and Voxel-based model zoo
* State-of-the-art performance
* DDP & SyncBN

## Benchmark
|              | KITTI(Val)           | nuScenes(Val)  |
| ------------ | -------------------- | -------------- |
| VoxelNet     |           -          |    -           |
| SECOND       |            -         |     -          |
| PointPillars |             -        |      -         |
| PIXOR        |              -       |       -        |
| PointRCNN    |               -      |        -       |
| CBGS         |                -     |         -      |
| ViP          |                 -    |          -     |

## Installation

```python
git clone https://github.com/poodarchu/MegDet3D --recursive
cd MegDet3D
pip install -r requirements.txt
python setup.py develop
```

## Data preparation

## Get Started

### Implement your own methods


## Contribute

## Acknowledgement

## Citation
```
@ARTICLE{2019arXiv190809492Z,
       author = {{Zhu}, Benjin and {Jiang}, Zhengkai and {Zhou}, Xiangxin and
         {Li}, Zeming and {Yu}, Gang},
        title = "{Class-balanced Grouping and Sampling for Point Cloud 3D Object Detection}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Computer Vision and Pattern Recognition},
         year = "2019",
        month = "Aug",
          eid = {arXiv:1908.09492},
        pages = {arXiv:1908.09492},
archivePrefix = {arXiv},
       eprint = {1908.09492},
 primaryClass = {cs.CV},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2019arXiv190809492Z},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

## Repos based on Det3D
* [ViP](https://github.com/poodarchu/ViP)
* [CBGS](https://github.com/poodarchu/Class-balanced-Grouping-and-Sampling-for-Point-Cloud-3D-Object-Detection/blob/master/README.md)
