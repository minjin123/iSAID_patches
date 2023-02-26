# iSAID_patches

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/isaid-a-large-scale-dataset-for-instance/object-detection-on-isaid)](https://paperswithcode.com/sota/object-detection-on-isaid?p=isaid-a-large-scale-dataset-for-instance)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/isaid-a-large-scale-dataset-for-instance/instance-segmentation-on-isaid)](https://paperswithcode.com/sota/instance-segmentation-on-isaid?p=isaid-a-large-scale-dataset-for-instance)

## iSAID: A Large-scale Dataset for Instance Segmentation in Aerial Images, CVPR workshops, 2019.

**Datasets for Instance Segmentation**

1.  **Data Preparation for Training, Validation and Testing**
    1. Please download iSAID dataset that contains image segmentation masks. Also, download preprocessed images from DOTA dataset.
    
    Make sure that the final dataset must have this structure:

    ```
    iSAID_patches
    ├── test
    │   └── Label.json
    │   └── Image
    │       ├── P0006_0_0_800_800.png
    │       └── ...
    │       └── P0009_0_0_800_800.png
    ├── train
    │   └── Label.json
    │   └── Image
    │       ├── P0002_0_800_800.png
    │       ├── ...
    │       └── P0010_0_800_800.png
    └── val
    │   └── Label.json
    │   └── Image
            ├── P0003_0_0_800_800.png
            ├── ...
            └── P0004_0_0_800_800.png
    ```
