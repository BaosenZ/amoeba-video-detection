# **Amoeba Video Detection**

The trained model to detect amoeba is in the folder of `trained-amoeba-model` and you can directly use it. This is trained using the method in the submodule of [amoeba-detection](https://github.com/BaosenZ/amoeba-detection) with the dataset here `dataset-for-detect-video`. 

You can run the inference on amoeba video in `original-video` with Mask R-CNN trained model in Google Colab ([![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/BaosenZ/amoeba-video-detection/blob/master/amoeba_video_detection.ipynb)). Note that the model is trained with original Mask RCNN version, but inference is performed in tf2.X Mask RCNN version. 

The folder of `output-video` contains some output detected videos. 

The `webcam-detection` can only work on your local computer and you need to setup environment by yourself. 

<br/>

## Amoeba Videos
Watch detected amoeba video: 
<p><a href="https://github.com/BaosenZ/amoeba-video-detection/blob/master/output-video/detect-amoeba.mp4"><img src='ML.png' width="750"></a></p>
