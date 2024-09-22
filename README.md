Helmet Detection using YOLOv8
This project implements a helmet detection model using the YOLOv8 architecture, designed to automatically detect whether individuals are wearing helmets in images or videos. The model is trained using a custom dataset hosted on Roboflow and fine-tuned for helmet detection tasks.

Features
YOLOv8 Model: A state-of-the-art object detection architecture that is both fast and accurate.
Helmet Detection: Identifies whether people in the provided images are wearing helmets.
Dataset: Managed and sourced from Roboflow.
Installation
Clone the repository from GitHub.

Install the required dependencies, which include packages like:

ultralytics for YOLOv8 implementation
roboflow for dataset management and API interaction
Standard Python libraries such as numpy, matplotlib, and torch.
Dataset
The dataset for this project is hosted on Roboflow. It can be downloaded via the Roboflow API by using your API key. The project dataset is versioned to ensure consistency during training and testing.

Model Training
The model is trained using the YOLOv8 architecture, with options to customize training parameters such as the number of epochs, batch size, image size, and the model type (e.g., YOLOv8n, YOLOv8s) based on the specific requirements.

Usage
Once the model is trained, it can be used for inference on images or videos to detect helmets. The outputs include images or video frames with bounding boxes highlighting the detected helmets.

Acknowledgments
Ultralytics for the YOLOv8 framework.
Roboflow for providing an easy-to-use platform for dataset management.
License
This project is licensed under the MIT License.
