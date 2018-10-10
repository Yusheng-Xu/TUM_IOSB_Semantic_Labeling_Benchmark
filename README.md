# TUM-Semantic-Labeling-Benchmark
This is the dataset used as the reference for semantic labeling of MLS point clouds

### Manully segmented reference

The testing area is the Arcisstrasse along the main entrance of Technical University of Munich (TUM) city campus, which covers
about an area of around 29000 m2. This dataset is original acquired by [Fraunhofer Institute of Optronics, System Technologies and Image Exploitation (IOSB)](https://www.iosb.fraunhofer.de/servlet/is/71825/). The used point clouds are acquired by two Velodyne HDL-64E mounted at an angle of 35◦ on the front roof of the vehicle. In the following provides sketch about how the two scanners are mounted (Gehrung et al., 2017). The original raw point clouds are also preprocessed by a statistical outlier removal for down-sampling and noise suppressing. The number of points after preprocessing is around 50 million. 


With thousands of scans acquired by the laser scanners, the scene contains various kinds of objects according to the eight semantic classes, including building, hight vegetation, low vegetation, vehicles, man-made terrain, natural terrain, hard scape, and scanning artefacts. For the evaluation process, an accurate manually labeled point cloud for the experimental dataset as ground truth is also generated manully by [Photogrammetry & Remote Sensing](http://www.pf.bgu.tum.de) of TUM. The manual work is conducted following ETH standard (Semantic3D Benchmark), and consumed totally 30 hours. As a consequence, a highly accurate reference of the Arcisstrasse is generated with only a subset of the entire dataset.

### Download link

Please contact [Prof. Uwe Stilla, Dr. Ludwig Hoegner, or Yusheng Xu](http://www.pf.bgu.tum.de/sta.html) for getting this dataset. 

![Illustration](/figure/Reference_BuildingSegmentation.png)

### Reference:

This reference dataset is original cropped from ETH Zurich [Semantic3D dataset](http://semantic3d.net/), and .

Please refer the following publications, if this reference dataset is used in your work:

```
@article{sun2018classification,
  title={CLASSIFICATION OF MLS POINT CLOUDS IN URBAN SCENES USING DETRENDED GEOMETRIC FEATURES FROM SUPERVOXEL-BASED LOCAL CONTEXTS.},
  author={Sun, Z and Xu, Y and Hoegner, L and Stilla, U},
  journal={ISPRS Annals of Photogrammetry, Remote Sensing \& Spatial Information Sciences},
  volume={4},
  number={2},
  year={2018}
}

@article{gehrung2017approach,
  title={An approach to extract moving objects from MLS data using a volumetric background representation},
  author={Gehrung, Joachim and Hebel, Marcus and Arens, Michael and Stilla, Uwe},
  journal={ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
  volume={4},
  pages={107},
  year={2017},
  publisher={Copernicus GmbH}
}
```