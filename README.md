# PTCNet - Tree crown detection model based on YOLOv3

PTCNet is a deep-learning urban tree crown detector for our study area, developed on YOLOv3 architecture with a Darknet-53 backbone. Based on the test dataset, the model had >75% precision and 62% recall of ground-truth data. However, based on other scenario test data, the performance was higher. It was developed for a [Pullman](https://en.wikipedia.org/wiki/Pullman,_Washington) city located in the southeastern part of Washington. More information on the model is in our publication. WHile the model is not perfect yet, it will updated to improve its generalization.


|                                                                                      |                                                                    |
|--------------------------------------------------------------------------------------|--------------------------------------------------------------------|
|![](https://github.com/Okikiola-Michael/PTCNet/blob/main/predicted%20annotations.png) | ![](https://github.com/Okikiola-Michael/PTCNet/blob/main/image.png)| 

PTCNet model was trained using ArcGIS pro 3.4 and the .emd and dlpk files are in the trained model folder

The high-resolution RGB image used is [here](https://gis.pullman-wa.gov/portal/apps/mapviewer/index.html?layers=8149c19a386c42bd88d440af8dac195e) 

The training and test annotation dataset ara in the [`hand-annotated annotations`]() folder

The detected tree crowns are in the [`predicted annotation`]() folder

If you use any data or the model in your work, please cite our publication
