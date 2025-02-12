# Group ID - GC16
## Final Year Project Repository
## Inattentive Driver Identification Smart System (IDISS)

Distracted driving is one of the leading causes of death among drivers on the road. This project was undertaken to provide a solution to distracted driving
by using deep learning and the Internet of Things. 


### Deep Learning Module
For the deep learning module, the following pre-trained models from the Keras library were trained on the [**State Farm Distracted Driving Dataset**](https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data):
  - VGG16
  - VGG19
  - Xception
  - ResNet50
  - InceptionV3

The implementation results reveal that **ResNet50 is the best-performing pre-trained model in terms of training accuracy and validation accuracy**,
and the model's weights have been saved in the form of a pickle file and an h5 file.



### IoT Module
The IoT module comprises codes written for the hardware components. 
- Pi camera
- MQ3 sensor
- ADXL345 sensor 


### Classification
The driver code contained in the repository produces the output in the form of correctly classified actions of the driver with respect to the class labels provided in the dataset. We have used around 2000 static images of drivers as input. The model when run, will classify the driver's actions and produce the classification output. 

For additional testing of the model, we have also compiled a custom miniature dataset on which we train the model to perform classification. The dataset contains 21 images, to be classified according to the labels of the State Farm Distracted Driver Dataset. 


#### [Click Here For The Video Demonstration!](https://drive.google.com/file/d/15BqNGadL0LV82Vte-cDe-waDjcaCVpp2/view?resourcekey&pli=1)


\
**Group Members:**

1. Janhavi Pimplikar (BECOC304)
2. Nikita Gaikwad (BECOC367)
3. Deepali Javriya (BECOC372)
4. Aditi Naiknaware (BECOC373)
