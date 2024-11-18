# PTCNet - Tree crown detection model based on YOLOv3

[**PTCNet**]() is a deep-learning urban tree crown detector, developed on [__YOLOv3__](https://arxiv.org/abs/1804.02767) architecture with a Darknet-53 backbone. Based on the test dataset, the model had `>75% precision` and `62% recall` of ground-truth data. However, based on other [scenario](https://github.com/Okikiola-Michael/PTCNet/blob/main/scenarios.zip) test data, the performance was higher. It was developed for the city of [Pullman](https://en.wikipedia.org/wiki/Pullman,_Washington) located in the southeastern part of Washington. More information on the model is in our [publication](). The model will be continually updated to improve its generalization and localization. The newer version will be uploaded


|                                                                                      |                                                                    |
|--------------------------------------------------------------------------------------|--------------------------------------------------------------------|
|![](https://github.com/Okikiola-Michael/PTCNet/blob/main/predicted%20annotations.png) |![](https://github.com/Okikiola-Michael/PTCNet/blob/main/image.png) | 

PTCNet model was trained using ArcGIS pro 3.4 and the .dlpk files can be found [here](https://drive.google.com/drive/u/2/folders/1fmKsfo78rBHs5JBXQokD8GEc1ZOvt78t).

The high-resolution RGB image used is [here](https://gis.pullman-wa.gov/portal/apps/mapviewer/index.html?layers=8149c19a386c42bd88d440af8dac195e) 

The training and test annotation dataset ara in the [`hand-annotated annotations`](https://github.com/Okikiola-Michael/PTCNet/blob/main/hand-annotated%20annotations.zip) folder

The detected tree crowns are in the [`predicted annotation`]() folder

If you use any data or the model in your work, please cite our [publication]()
