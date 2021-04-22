# Object_detection-TFOD

In this project I trained a object detection and multi classification model using *TensorFlow Object detetction API(TFOD)*.

I have used **faster_rcnn_inceptionv2_coco**.
Trained the model on Nvidia RTX2060 GPU for 1499 number of epochs. Number of clsses to predict were 5.
**Tensorflow-gpu 1.15.0** was used.


Below are the couple of output images that are predicted by model and you can check more on **Output_Images** Folder

![Output Image](/Output_Images/dre.jpg)

![Output Image2](/Output_Images/cfs.jpeg)

![Output_Image3](/Output_Images/arht.jpg)

## Steps to implement and train the Object detection model using TFOD (1.x)

> Follow this blog for [TFOD Setup](https://inblog.in/TFOD-Installation-Object-Detection-ZEBMHporCF) (if you do't have setup) in your local system. you can train the model with tensorflow cpu or gpu as well. Download the according to your requirement

> I have provided the **labelmap.pbtxt** file **Image dataset** and **tfrecord** file format which will be used for training the model.

> checkpoint file (model.ckpt) files has been provided so that, if interested anyone can retrain the model and can predict better results than my model. Please do the changes in Config file before retraining.

> I have uploaded my trained tfod model (Inference_grapg_1499/frozen_inference_graph.pb) also which you can test the model in your system as well. For testing my model you should have tensorflow-gpu 1.15.0 should be installed in your environment, as cpu version will not be able to load the model.


##Future Scope
> This can be useful in hospitals so that who are entering into operation theaters, ICU's must wear all those kit. Particularly in this pandemic situation nobody even normal should enter into isolated rooms with dress format.
> This project can developed as an end to end application in order to install in CCTV's, and can be integrated with electronics device so that then only the door will be unlocked if suppose **Coverall** is predicted for a person.
