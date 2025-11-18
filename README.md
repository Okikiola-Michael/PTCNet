<h1 align="center">
 PTCNet - Tree crown detection model based on YOLOv3
</h1>

<p align="center">
<img src= "https://github.com/Okikiola-Michael/PTCNet/blob/main/images/all.jpg" >
</p>

[**PTCNet**]() is a deep-learning urban tree crown detector, developed on [__YOLOv3__](https://arxiv.org/abs/1804.02767) architecture with a Darknet-53 backbone. 

```javascript
Model Training
1. Model: YOLOv3 with a Darknet-53 backbone for 30 epochs.
2. Batch: 8
3. IOU: 0.5 (Overlap between the reference and detected tree crowns)
4. Non-maximum suppression: 0.1
5. Confidence score: 0.1

```

Based on the test dataset, the model had `>75% precision` and `62% recall` of ground-truth data. However, based on other [scenario](https://github.com/Okikiola-Michael/PTCNet/blob/main/scenarios.zip) test data, the performance was higher. It was developed for the city of [Pullman](https://en.wikipedia.org/wiki/Pullman,_Washington) located in the southeastern part of Washington. More information on the model can be found in our [publication](). The model will be continually updated to improve its generalization and localization, and the newer version will be uploaded.


|                                                                                             |                                                                              |
|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
|![](https://github.com/Okikiola-Michael/PTCNet/blob/main/images/predicted%20annotations.png) |![](https://github.com/Okikiola-Michael/PTCNet/blob/main/images/image%202.png)| 

The PTCNet model was trained using ArcGIS Pro 3.4, and the .dlpk files can be found [here](https://drive.google.com/drive/u/2/folders/1fmKsfo78rBHs5JBXQokD8GEc1ZOvt78t). 

The high-resolution RGB image used is [here](https://gis.pullman-wa.gov/portal/apps/mapviewer/index.html?layers=8149c19a386c42bd88d440af8dac195e) 

The training, testing, and scenario annotation shapefiles are here in the [`hand annotations`](https://github.com/Okikiola-Michael/PTCNet/tree/main/hand_annotations) folder.

The detected tree crown shapefiles are in the [`predicted annotation`](https://github.com/Okikiola-Michael/PTCNet/tree/main/predicted_annotations) folder.

The entire tree crown, including training/testing annotations, predicted annotations, and other annotations, is available [here]().

See the distribution of the tree crowns in the study area: [Video](https://drive.google.com/file/d/1YZfqkv1KCCzesbo4IaLR5-h9urAqS54T/view?usp=drive_link)

If you find any of these resources useful in your work, cite our [publication]().
