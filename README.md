# Region Proposal Network 

Region Proposal Network **(RPN)** is a part of Faster R-CNN algorithm that is used to propose regions (bounding boxes) that contains the targetted objects. These proposed regions are then refined and the objects inside the regions will be classified. RPN can also be used as a standalone network as a one-class object detector. In this implementation, a VGG-16 network was first used to classify between aeroplanes and bicycles. RPN then uses this pre-trained model as the backbone to enable the localization of aeroplanes and bicycles in images.

Below are some of the results of the RPN on localizing airplanes and bicycles.

### Region Proposals on Aeroplane images
<img src="readme_images/1.png" width="170"/><img src="readme_images/2.png" width="170"/><img src="readme_images/3.png" width="170"/><img src="readme_images/4.png" width="170"/> <img src="readme_images/5.png" width="170"/>


### Region Proposals on Bicycle images
<img src="readme_images/6.png" width="170"/><img src="readme_images/7.png" width="170"/><img src="readme_images/8.png" width="170"/><img src="readme_images/9.png" width="170"/> <img src="readme_images/10.png" width="170"/>

### License
_________
 MIT
