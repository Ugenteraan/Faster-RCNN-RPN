# Region Proposal Network 

Region Proposal Network **(RPN)** is a part of Faster R-CNN algorithm that is used to propose regions that contains the targetted objects. These proposed regions are then refined and the objects inside the regions will be classified. RPN can also be used as a standalone network as a one-class object detector. In this implementation, a VGG-16 network was first used to classify between aeroplanes and bicycles. RPN uses this pre-trained model as the backbone to enable the localization of aeroplanes in images.

Short notes are provided for a clearer understanding and all implementation is done on RPN.ipynb file only. Below are the results of the RPN on localizing airplanes.

### Original Input Images 
<img src="readme_images/1.png" width="170"/><img src="readme_images/3.png" width="170"/><img src="readme_images/5.png" width="170"/><img src="readme_images/7.png" width="170"/> <img src="readme_images/9.png" width="170"/>


### Predicted Bounding Boxes
<img src="readme_images/2.png" width="170"/><img src="readme_images/4.png" width="170"/><img src="readme_images/6.png" width="170"/><img src="readme_images/8.png" width="170"/> <img src="readme_images/10.png" width="170"/>

### License
_________
 MIT
