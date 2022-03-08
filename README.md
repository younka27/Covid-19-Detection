# Covid-19-Detection
In this project we detect the covid-19 case from the classification of X-ray images such as: normal, viral pneumonia and COVID-19. In the project, we used the image dataset that can be found at Kaggle:  https://www.kaggle.com/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset.

Drawing inspiration from projects on Jovian and other tutorials ( like Skin-Cancer-Classification projects), in this project we divide the data set in order to reserve a validation set of 30 images per class, this will allow the accuracy of the model to be measured during training. Using the ResNet18 network, with pre-trained weights on ImageNet, adjusting only the final classification layer to predict between the 3 classes.







