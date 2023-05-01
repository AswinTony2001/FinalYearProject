# FinalYearProject



Sri Sivasubramaniya Nadar College of Engineering.

Department of Computer Science and Engineering.

Automated Medical Image Captioning System

May 2023


Group no: A - 7
Project Coordinator: Dr. B. Bharathi
Supervisor: Dr. P. Mirunalini
Authors:
1. Aswin Tony K (195001025)
2. Rohit A S (195001308)


Project Overview:


Analyzing and summarising the insights derived from medical images of any modalities is a time-consuming operation. It requires highly skilled experts and possess a bottleneck in clinical diagnosis pipelines. As a result, to overcome these problems there is a need for automatic systems that can approximate the mapping from visual information to condensed verbal descriptions. The more image characteristics that are identified resulting in a better grasp of interpretation for radiologists. In this project, we proposed to develop an automated system that summarises the information present in the medical images based on two processes such as concept detection and caption prediction. Concept detection  involves finding concepts based on the image characteristics by better understanding the scene of the given input image. We have achieved the concept identification with the help of Unique Identifiers (CUIs) present in the Unified Medical Language System (UMLS) for different characteristics of images such as image modality, anatomy, chemical substances and diseases etc. We developed three different models using transfer learning techniques such as ResNet50, DenseNet121, EfficientNet and analysed the performance of the models. In caption prediction,  coherent captions have been predicted for the entirety of an image and is based on the image features and lexical similarity.


Dataset Used: A subset of the extended Radiology Objects in COntext (ROCO) dataset released by ImageCLEF 2022


For the creation and training of automated medical image captioning systems, vast data sets are essential. Biomedical papers in the PMC OpenAccess subset were used to create the extended version of the Radiology Objects in Context (ROCO) dataset that was used for this project. There are a lot of radiological images in it, including 65,000 for the training set and 18,275 for the test set.

The Unified Medical Language System, or UMLS, has 8,374 concepts labelled on this dataset. The terminology and expressions used to describe the photos in the dataset are represented by these concepts. A single image can be associated with up to 100 different UMLS concepts, providing for a rich and comprehensive description of the image


URL:  https://drive.google.com/drive/u/1/folders/1JHMoWimnp2eafUf2X8OSXCnb2sy10H6F


Installation: 


Application Requirements


*  Application : Google Colab



Steps to run the code:


1. Download zip file containing source code.
        
2. Select the required python notebook for the model to be work on.


3. There are 4 python notebooks availabe:
   For Concept Detection part:
   i) For ResNet model open FinalResNetNew notebook in Colab.

   ii) For Efficientnet model open FinalEfficientnetNew notebook in Colab.

   iii) For DenseNet model open FinalDenseNetNew notebook in Colab.

   For Caption Prediction:
   i) Open Caption Prediction notebook in Colab.


4. Download the dataset from the drive and upload it to the personal Google Drive.

5. Change the code for importing the data with the url from personal Drive. 

6. Run all the modules in the Colab and wait for the training to complete.

7. Insert the image to be tested in the Input module and run it for the concept detction or/ caption prediction.

6. Run the application using the following command.
   1. python manage.py runserver
