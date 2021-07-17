# EndoObjDetect
A TensorFlow-centered approach to object detection using Faster R-CNN to detect endometriosis on the GLENDA database
Model used: Faster R-CNN Inception ResNet V2 1024 x1024
Implemented on Google Colab on High RAM, GPU accelerated environment

Some of the images that were produced:
![alt text](https://github.com/awicklund/EndoObjDetect/blob/main/Finished%20examples/4.png)
![alt text](https://github.com/awicklund/EndoObjDetect/blob/main/Finished%20examples/73.png)
![alt text](https://github.com/awicklund/EndoObjDetect/blob/main/Finished%20examples/51.png)

Endometriosis is a painful condition where the tissues produced inside the uterus to protect a fertilized egg grow outside the uterus. This is the first publically available image study of endometriosis and the model is designed to detect endometrial tissues on and around the uterus.

The files are organized as follows:
**Finished examples** - contains 10 example images and 10 doctor-annotated example images (alpha channel)
**Graphs** - graphs displaying model information provided by Tensorboard
**Model** - contains both important outputs (Endo), as well as test data (Endo) and inputs (my_tfod) 
**Endometriosis Modeling 101** - user-friendly document that describes the model for the general public
**My_Code.ipynb** - the Jupyter Notebook that I used to create the model
**Slide_Deck.pptx** - the Powerpoint used in presenting the model
**Technical_Documentation** - a write-up designed for data scientists, contains technical jargon
**Tutorial_Used** - the tutorial I referenced in creating and running the model


Got a question? Or a neat project to share? E-mail me at theendoproject@yahoo.com
