# Object Detection for PharmaSEE
Code for training and object detection model in Tensorflow that identifies 100 classes of pills. We utilized the EfficientDet architecture from Tensorflow Hub and used the TF Object Detetion API for training. The inference results can be found [here](https://github.com/Pharma-SEE/Ai_recognition/blob/main/object_detection.ipynb). 

<!-- Details can be found on our project [website](https://sites.google.com/view/pharma-see-hyu/object-detetion-w-tf?authuser=0). -->

## Inference Result Example
<img src='https://user-images.githubusercontent.com/58558382/155475736-c7767d67-d111-4bc0-96c3-cbd6ce8b79d6.png' height=500>

## Object Detetion in the PharmaSEE Server
Mobile app users can select images or take pictures of the pills they wish to identify, which will be sent to the backend server. The server performs object detection in real time using a deployed tensorflow model. The model is deployed using TensorFlow Model Serving. The user receives results in within 1000ms.

- Example Input / Output Image   
<img src='https://user-images.githubusercontent.com/58558382/155477314-fc48d95a-2024-42c6-8299-3d17567188f7.png' height=300>  <img src='https://user-images.githubusercontent.com/58558382/155477387-e2eee86e-6347-471d-a793-8d1dcb3969e6.png' height=300>

