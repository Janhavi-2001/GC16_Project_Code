## Final Year Project Repository
## Inattentive Driver Identification Smart System (IDISS)

Distracted driving is one of the leading causes of death amongst drivers on the road. This project was undertaken to provide a solution to distracted driving
by using deep learning and the internet of things. 


#### Deep Learning Module
For the deep learning module, the following pre-trained models from the Keras library were trained on the [State Farm Distracted Driving Dataset](https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data):
  - VGG16
  - VGG19
  - Xception
  - ResNet50
  - InceptionV3


#### IoT Module
The IoT module comprises of codes written for the hardware components. 
- Pi camera
- MQ3 sensor
- ADXL345 sensor 

The deep learning module is integrated with the IoT module through a Raspberry Pi device. The driver code within the repository integrates these modules to produce the output in the form of correctly classified actions of the driver with respect to the class labels provided in the dataset.

Group Members:

1. Janhavi Pimplikar
2. Nikita Gaikwad
3. Deepali Javriya
4. Aditi Naiknaware
