# Traffic Monitoring

I have developed a system that efficiently detects, tracks, and counts vehicles, estimates their speeds, and identifies speed limit violations with up to 95% accuracy. This promotes proactive traffic management and enhances road safety. By integrating YOLOv8's advanced pretrained model and implementing a centroid tracking algorithm, the system achieves robust performance across diverse video datasets, ensuring adaptability to real-world traffic scenarios

From a technical perspective, YOLOv8 is a family of convolutional neural network models developed and trained using the PyTorch framework. As the latest iteration of the popular YOLO (You Only Look Once) object detection algorithms by Ultralytics, YOLOv8 offers state-of-the-art performance. It builds upon previous YOLO versions to provide faster and more accurate detection, instance segmentation, and image classification through a unified framework. YOLOv8's efficiency improvements stem from using a larger feature map and a more efficient convolutional network.

The system effectively detects, tracks, and counts vehicles moving in either direction and estimates their speeds. It also identifies vehicles exceeding speed limits to enhance road traffic safety. A centroid tracking algorithm is employed to track vehicles by monitoring the centroids of the detections provided by YOLOv8.

Evaluated using YOLOv8's pretrained model (e.g., `yolov8s.pt`), which is trained on the COCO dataset—a large collection of images containing 80 different object classes—the system was tested on various videos and achieved an average accuracy of up to 95%.

## Models Available in YOLOv8

There are five models in each category of YOLOv8 for detection, segmentation, and classification. **YOLOv8 Nano** is the fastest and smallest, while **YOLOv8 Extra Large (YOLOv8x)** is the most accurate yet the slowest among them

YOLOv8 comes bundled with the following pretrained models:

- **Object Detection** checkpoints trained on the COCO detection dataset with an image resolution of 640.
- **Instance Segmentation** checkpoints trained on the COCO segmentation dataset with an image resolution of 640.
- **Image Classification** models pretrained on the ImageNet dataset with an image resolution of 224.

### **I have used YOLOv8's pretrained model, `yolov8s.pt`, in my project.**

- **YOLOv8 Object Detection Tutorial:** [How to Detect Objects in Images Using YOLOv8](https://www.freecodecamp.org/news/how-to-detect-objects-in-images-using-yolov8/)
- **Centroid Tracking Algorithm Tutorial:** [A Tutorial on Centroid Tracker Counter System](https://www.analyticsvidhya.com/blog/2022/05/a-tutorial-on-centroid-tracker-counter-system/)

## Technologies

- **Programming Language:** Python (Version 3.11)
- **Platform:** Visual Studio Code IDE / [PyCharm: Getting Started](https://www.jetbrains.com/help/pycharm/getting-started.html)
- **Libraries:** Pandas (1.5.3), NumPy (1.24.3), OpenCV for Python (4.8.1.78), and Ultralytics (8.0.147)
- **Libraries Installation:** Open Terminal in Windows and run `pip install package_name==version`

<h2>Screenshots:</h2>

![1](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/1.jpg)

![2](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/2.jpg)

![3](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/3.png)

![4](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/4.png)

![5](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/5.png)

![6](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/6.png)

![7](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/7.png)

![8](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/8.png)

![9](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/9.png)

![10](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/10.png)

![12](https://tmp-public-uploader.s3.ap-south-1.amazonaws.com/important-files/12.png)
