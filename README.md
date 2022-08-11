# Object Detection using MaskRCNN Detectron model
 The objective is to use Mask RCNN technique for instance segmentation on the COCO dataset. 
 
 ### Dataset:
[COCO dataset!](https://cocodataset.org/#home)

The **COCO dataset** is a large image dataset designed for Object Detection,  Segmentation,  person keypoints detection, and Caption Generation.
COCO has several features:
* Object segmentation
* Recognition in context
* Superpixel stuff segmentationo330K images (>200K labeled)
* 1.5 million object instances
* 80 object categories
* 91 stuff categories
* 5 captions per image
* 250,000 people with keypoints

### Tasks performed:
•Clone the Facebook Detectron Modelusing the following link:
  - [Facebook Detectron Model](https://github.com/facebookresearch/Detectron.git)

•Load the pre-trained weights using the following link:
  - [Pre-trained weights for Mask RCNN model](https://dl.fbaipublicfiles.com/detectron/36494496/12_2017_baselines/e2e_mask_rcnn_X-101-64x4d-FPN_1x.yaml.07_50_11.fkwVtEvg/output/train/coco_2014_train%3Acoco_2014_valminusminival/generalized_rcnn/model_final.pkl)
  
•Use the Mask RCNN Architecture and the pre-trained weights to generate predictions for our own images or images from the COCO dataset

•Visualize the Results

### Input and Output:
- **The input I provided:**

![Input](/images/input.PNG)

- **The output image with masks**

![Output](/images/output.PNG)
