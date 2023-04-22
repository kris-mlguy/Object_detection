# Object detection

->  Object detection performs identification of objects in a given image.
It also draws bounding boxes around objects to locate them.  

->  Instance segmentation additionally provides a pixel mask for the shape of detected object. i.e., it is essentially a combination of object detection and semantic segmentation.  

->  Instance segmentation is valuable in distinguishing multiple instances of same or different classes (eg: differentiate a specific car from rest of them in a video frame) and improves granularity of computer vision.

![Alt text](https://github.com/kris-mlguy/Object_detection/blob/main/instances.jpg?raw=true "Optional Title")

### Applications include  
    1. Advanced Driver-Assistance Systems (ADAS)  
    2. Autonomous driving  
    3. Medical imaging  
    4. Surveillance  
    5. Satellite imagery 
    6. Robotics
    
### Detectron2  
    Detectron2 is a state-of-the-art open source framework for computer vision tasks such as object detection and instance segmentation, developed by Facebook AI Research (FAIR).

    It is built on PyTorch and comes with models such as faster R-CNN and mask R-CNN.

### Getting started
    1. Install detectron2 - https://helloshreyas.in/a-step-by-step-guide-to-installing-detectron2-on-your-windows-system 
    2. Clone the repository: git clone https://github.com/kris-mlguy/Object_detection.git  
    3. Open anaconda prompt and navigate to directory containing the cloned repo  
    4. Create a conda environment: conda create -n object_detection  
    5. Activate the environment: conda activate object_detection  
    6. Install jupyter notebook library: conda install jupyter notebook  
    7. Install other dependent libraries: pip install -r requirements.txt  
    8. Open jupyter notebook: jupyter notebook  
    9. Above step will open jupyter notebook in a browser. Open the <required_notebook>.ipynb and run it cell-by-cell to see the working of object detection and instance segmentation  

### References
    https://github.com/facebookresearch/detectron2, https://www.analyticsvidhya.com/blog/2021/08/your-guide-to-object-detection-with-detectron2-in-pytorch/