
##Explanation of the code files and datasets:
This folder contains the dataset and code of all CNN models performing fundus photogrpahs anomaly detection. 

DATASET:
- folder 'img': This is the original fundus photographs dataset collected by Tsukazaki Hospital in Japan downloaded from GitHub.
- CSV file 'data.csv': Together downloaded with the Tsukazaki Hospitial dataset, 
                       A table describes the characteristics of the imgages, including filename, age, sex, disease
THE NEXT 2 FOLDER CAN BE CREATED BY THE CODE
- folder 'img_an': Adapted from folder 'img'. 
                   Categorized into test and train folder, each include normal and abnormal folder containing corresponding fundus imgaes 
- folder 'cate_c': Adapted from folder 'img'.
                   Categorized into test and train folder, each include folders of fundus images with different diseases.

Folder 'cv_model': Saved different trained CNN models

IPYNB NOTEBOOK:
CNN_an_simple.IPYNB
    simple CNN model, normal and abnormal classification
CNN_an_iv3.IPYNB
    Inception V3, normal and abnormal classification
CNN_an_resnet.IPYNB
    ResNet, normal and abnormal classification
CNN_dip_3_IV3.IPYNB
    Inception V3, HE, DR, Gla classification
CNN_dip_3_IV3_CV.IPYNB
    Inception V3, HE, DR, Gla classification, with cross validation
CNN_dip_3_resnet.IPYNB
    ResNet, HE, DR, Gla classification
CNN_dip_3_resnet_CV.IPYNB
    ResNet, HE, DR, Gla classification, with cross validation
CNN_dip_c_resnet.IPYNB
    ResNet, all 9 diseases classes and normal fundus classification
CNN_resnet_CV_5.IPYNB
    ResNet, 5 class classification (MH, RP, AMD, RVO, RD), with cross validation
CNN_resnet_HE+SD.IPYNB
    ResNet, each separate disease (not included in the 3 class classification) VS. normal fundus classification, with cross validation

All ipynb notebook can run under updated (till today) packages environment (espicially tensorflow etc.)
Attention: the directory of the images might need change
