# UAV75
## A Challenging Dataset for Crack Segmentation

The images in the dataset were captured by a drone flying at the surface of the structure. Its purpose is to cover specifically two challenges: the occuring strong *planking patterns* and *tiny cracks*, which are only a couple of pixels wide.

The dataset contains 75 manually annotated images of size 512×512 pix with pixel-wise labels. The images were manually split into *training*, *validation*, and *test* dataset, each subset covering the perceptible variations in crack and planking patterns. Unlike the other datasets, the UAV75 includes a **planking class** to account for the false positives caused by the planking patterns. The planking class was annotated area-wise, while cracks – due to their narrowness and conforming to other approaches – obtained line-wise labels.


## Reference
```
@inproceedings{benz2019crack,
  title={Crack segmentation on UAS-based imagery using transfer learning},
  author={Benz, Christian and Debus, Paul and Ha, Huy Khanh and Rodehorst, Volker},
  booktitle={2019 International Conference on Image and Vision Computing New Zealand (IVCNZ)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}
```
