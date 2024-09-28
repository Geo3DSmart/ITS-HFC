# [ITS-HFC：Individual tree segmentation from UAS Lidar data based on hierarchical filtering and clustering](https://www.tandfonline.com/doi/full/10.1080/17538947.2024.2356124#abstract)

**HFC** is a individual tree segmentation method based on hierarchical filtering and clustering. We provide the code in our paper which the clustering method is based on FEC (Fast European Clustering). And we also provide the tool [TreeTool](https://github.com/porteratzo/TreeTool) used in the method.



## Overview
- [Environment](#Environment)
- [Project Structure](#Project-Structure)
- [Code Download](#Code-Download)
- [Citation](#Citation)


## Environment

- python                         3.7.0
- numpy                         1.21.6
- open3d                        0.17.0
- pclpy                            0.12.0
- pandas                        1.1.5
- matplotlib                    3.5.3
- tqdm                            4.66.5



## Project Structure
```
├── LICENSE
├── HFC.py
├── evaluate.py
├── README.md
├── utils
│   ├── FEC.py
│   ├── SVD_filter.py
│   ├── ...
├── testdata
│   ├── Groundtruth.csv
│   ├── Pointclouds.las
├── geometry
│   ├── geometry.py
│   ├── main.py
│   ├── ...
├── TreeTool
│   ├── tree_tool_SVD_3D.py
│   ├── utils.py
│   ├── ...
└── requirements.yaml
```


## Code Download

Our code is freely available to researchers. Please download and sign our [agreement](https://drive.google.com/file/d/1uGB5JPkyqn4XfyuBXjwIsZ1jqTgHRYnm/view) and send it to the provided email address ([witchery007@outlook.com](mailto:witchery007@outlook.com)). You will receive the code within one week.

## Citation

If you found our work useful, consider citing our work.

```bixtex
@article{Zhang2024IndividualTS,
  title={Individual tree segmentation from UAS Lidar data based on hierarchical filtering and clustering},
  author={Cailian Zhang and Chengwen Song and Aleksandra Zaforemska and Jiaxing Zhang and Rachel Gaulton and Wenxia Dai and Wen Xiao},
  journal={International Journal of Digital Earth},
  year={2024},
  url={https://api.semanticscholar.org/CorpusID:270111954}
}
```





## License

Code is released for non-commercial and research purposes only. For commercial purposes, please contact the authors.



