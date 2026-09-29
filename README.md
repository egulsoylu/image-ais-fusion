<div>
  <h1>
    Image and AIS Data Fusion Technique <br>for Maritime Computer Vision Applications
  </h1>
</div>

[![PWC](https://img.shields.io/badge/%F0%9F%93%8E%20arXiv-Paper-red)](https://arxiv.org/abs/2312.05270)

This repository contains the resources for the paper titled "*[Image and AIS Data Fusion Technique for Maritime Computer Vision Applications](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Gulsoylu_Image_and_AIS_Data_Fusion_Technique_for_Maritime_Computer_Vision_WACVW_2024_paper.html)*" presented at 2nd Workshop on Maritime Computer Vision (MaCVi) at WACV 2024. 

## Dataset
The AIS data used in this study cannot be shared publicly as the approval from the institution is still pending. However, the images and the 2D bounding box annotations are available for [download here](https://cloud.uni-hamburg.de/public.php/dav/files/iDaLktet82Ld5rb/?accept=zip).

## Alternative Dataset
If you are looking for a similar and publicly available dataset, you can check out the [BONK-pose](https://fabianholst.github.io/BONK-pose/) dataset. The BONK-pose dataset provides:
- 3D bounding boxes for vessel 6D pose estimation
- Related AIS data
- 2D bounding boxes for ship detection

## Citation

Please cite the following papers:

```
@inproceedings{gulsoylu2024image,
  title={Image and ais data fusion technique for maritime computer vision applications},
  author={G{\"u}lsoylu, Emre and Koch, Paul and Yildiz, Mert and Constapel, Manfred and Kelm, Andr{\'e} Peter},
  booktitle={2nd Workshop on Maritime Computer Vision (MaCVi), in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={859--868},
  year={2024}
}
```

The following paper is published at [IEEE Journal of Oceanic Engineering](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=48)

[![PWC](https://img.shields.io/badge/Paper-IEEE_JOE-blue)](https://ieeexplore.ieee.org/abstract/document/11570774)
```
@ARTICLE{holst2026fusing,
  author={Holst, Fabian and Gülsoylu, Emre and Frintrop, Simone},
  journal={IEEE Journal of Oceanic Engineering}, 
  title={Fusing Monocular RGB Images With AIS Data to Create a 3-D Bounding Box Estimation Data Set for Marine Vessels}, 
  year={2026},
  volume={51},
  number={3},
  pages={1676-1688},
  keywords={Marine vehicles;Estimation;Annotations;Modeling;Planing;Signal detection;Water;Object detection;Cameras;Distance measurement;3-D bounding box estimation;automatic identification system (AIS);data fusion;ship detection},
  doi={10.1109/JOE.2026.3695330}
}
```
