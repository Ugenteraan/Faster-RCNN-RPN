# Region Proposal Network 

Region Proposal Network **(RPN)** which is a part of Faster R-CNN algorithm, is used to propose regions . Using these proposed regions, the predicted bounding boxes will be further refined and filtered, and the objects detected will be classified. RPN can also be used as a standalone network to be used as a one-class object detector. In this implementation, a VGG-16 network was first used to classify between aeroplanes and bicycles. RPN was implemented on top of this pre-trained model. RPN is then used to locate aeroplanes only. 

Short notes are provided for a clearer understanding and all implementation is done on RPN.ipynb file only. Below are the results of the RPN on localizing airplanes.

### Original Input Images 
![1](readme_images/1.png){ width=50% }
![3](readme_images/3.png){ width=50% }


### Predicted Bounding Boxes
<img src="readme_images/2.png" width="60">
<img src="readme_images/4.png" width="60">
<img src="readme_images/6.png" width="60">
<img src="readme_images/8.png" width="60">
<img src="readme_images/10.png" width="60">


### License
_________
 MIT
