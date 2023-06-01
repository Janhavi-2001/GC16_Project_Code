# Group ID - GC16
## Final Year Project Repository
## Inattentive Driver Identification Smart System (IDISS)

Distracted driving is one of the leading causes of death amongst drivers on the road. This project was undertaken to provide a solution to distracted driving
by using deep learning and the internet of things. 


### Deep Learning Module
For the deep learning module, the following pre-trained models from the Keras library were trained on the [**State Farm Distracted Driving Dataset**](https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data):
  - VGG16
  - VGG19
  - Xception
  - ResNet50
  - InceptionV3

The implementation results reveal that **ResNet50 is the best performing pre-trained model in terms of training accuracy and validation accuracy**,
and the model's weights have been saved in the form of a pickle file. This pickle file will be deployed into the IoT module for predicting driver behavior.



### IoT Module
The IoT module comprises of codes written for the hardware components. 
- Pi camera
- MQ3 sensor
- ADXL345 sensor 

The deep learning module is integrated with the IoT module through a Raspberry Pi device. The driver code contained in the repository integrates these modules to produce the output in the form of correctly classified actions of the driver with respect to the class labels provided in the dataset. We have used around 2000 static images of drivers as input. The model when run, will classify the driver's actions and produce the classification output in the form of a text file. 

By using approximation, the predicted classifications have correctly classified around 80 percent of the images provided as input to the system.



#### **Link to resnet50.pkl file and system input -** [Click here](https://drive.google.com/drive/u/1/folders/10td0d2OsM2sbjkx3mxZ1T8-aWVVHXzxJ)
\
\
**Group Members:**

1. Janhavi Pimplikar (BECOC304)
2. Nikita Gaikwad (BECOC367)
3. Deepali Javriya (BECOC372)
4. Aditi Naiknaware (BECOC373)
