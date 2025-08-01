# Breast Ultrasound Classifier

![](https://camo.githubusercontent.com/570a88dfdfa4285217fc5129a1b84d9409fe8710cc6e3d3e4a99f5b279a89e48/68747470733a2f2f64726976652e676f6f676c652e636f6d2f75633f69643d316347612d3170323466364f7775707538583534445f6143736d4a553242495647)

This repository holds the datasets and code used to train and evaluate various CNN based and transformer models for the classification of benign and malignant breast ultrasound images.

## Project Details

All packages and version numbers used are stated in the requirements.txt file

## Dataset

A full description of the data set with access linkes has been provided below

| Dataset | Number of Benign Images | Number of Malignant Images |
|---|---|---|
| [Breast-Lesions-USG](https://www.cancerimagingarchive.net/collection/breast-lesions-usg/) | 154 | 98 |
| [BUID](https://www.sciencedirect.com/science/article/pii/S0010482522011465?via=ihub) | 109 | 123 |
| [BUS_UC](https://data.mendeley.com/datasets/3ksd7w7jkx/1) | 358 | 453 |
| [BUS_UCLM](https://data.mendeley.com/datasets/7fvgj4jsp7/1) | 174 | 90 |
| [BUSBRA](https://zenodo.org/records/8231412) | 1268 | 607 |
| [BUS](https://helward.mmu.ac.uk/STAFF/M.Yap/dataset.php) | 109 | 54 |
| [BUSI](https://helward.mmu.ac.uk/STAFF/M.Yap/dataset.php) | 437 | 210 |

### Dataset Structure

```
Full_Dataset
├── test
│   ├── benign
│   └── malignant
├── train
│   ├── benign
│   └── malignant
└── val
    ├── benign
    └── malignant
```

## Model Metrics

| Model | Model Size (MB) | Number of Parameters | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|---|---|
| Efficientnet_v2_m | 727.67 | 53,680,758 | 0.8211 | 0.8209 | 0.8211 | 0.821 |
| ResNet50 | 376.82 | 23,512,130 | 0.8075 | 0.8082 | 0.8075 | 0.8078 |
| GoogleNet | 118.07 | 6,126,754 | 0.7835 | 0.7838 | 0.7835 | 0.7836 |
| Swin_v2_b | 760.94 | 58,941,058 | 0.8223 | 0.8203 | 0.8223 | 0.8201 |
| Inception_v3 | 325.49 | 25,116,362 | 0.8045 | 0.8065 | 0.8045 | 0.8053 |
| ViT_B_16 | 333.89 | 85,800,194 | 0.8045 | 0.8052 | 0.8045 | 0.8048 |

## Troubleshooting and Support

* Choja Macarthy - chojamacarthy30@gmail.com

## License

