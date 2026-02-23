# Integration of Semantic Segmentation into Visual SLAM
This project trains a DeepLabV3+ semantic segmentation model on KITTI, BDD_10K, and a unified dataset. Models are evaluated for cross-dataset generalization, and the best one is integrated into KITTI visual odometry to fuse 2D semantics with LiDAR, producing a semantic 3D map
This project uses:

- KITTI Vision Benchmark Suite  
  - Odometry dataset  
  - Semantic segmentation subset  
  Download: http://www.cvlibs.net/datasets/kitti/

- BDD100K  
  - Semantic segmentation subset  
  Download: https://bdd-data.berkeley.edu/
