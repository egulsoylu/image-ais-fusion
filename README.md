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

The following paper is currently under review at [IEEE Journal of Oceanic Engineering](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=48)
```
@article{holst2025fusing,
  title={Fusing monocular RGB images with AIS data to create a 6d pose estimation dataset for marine vessels},
  author={Holst, Fabian and G{\"u}lsoylu, Emre and Frintrop, Simone},
  journal={arXiv preprint arXiv:2508.14767},
  year={2025}
}
```
