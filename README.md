# Integration of Semantic Segmentation into Visual SLAM
This project trains a DeepLabV3+ semantic segmentation model on KITTI, BDD_10K, and a unified dataset. Models are evaluated for cross-dataset generalization, and the best one is integrated into KITTI visual odometry to fuse 2D semantics with LiDAR, producing a semantic 3D map

Datasets & Benchmarks
KITTI Semantic Segmentation (2015)

Benchmark: Semantic Segmentation (2015)
https://www.cvlibs.net/datasets/kitti/eval_semseg.php?benchmark=semantics2015

BDD100K (10K Images + Segmentation)

Subset: 10K Images + Semantic Segmentation

http://bdd-data.berkeley.edu/download.html

KITTI Visual Odometry / SLAM (2012)

Benchmark: Visual Odometry / SLAM Evaluation 2012
https://www.cvlibs.net/datasets/kitti/eval_odometry.php

Used for: integration of semantics into visual SLAM and 3D reconstruction
