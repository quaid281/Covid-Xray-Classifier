# Covid-Xray-Classifier
The project #1 intends to apply deep neural network to classify X-Ray images into four different categories. A dataset with four groups of X-Ray images will be provided. Your project will carry out research study on the images, and report your results and findings. 
             
          COVID-19                             Lung-Opacity                   Viral Pneumonia                 Normal

Data source and tasks
1.	Please download the COVID-19 X-Ray images (700+MB zip file) from the following URL
http://www.cse.fau.edu/~xqzhu/courses/cot6930/dataset/covidImages.zip

The original images were downloaded from the Kaggle site (https://www.kaggle.com/tawsifurrahman/covid19-radiography-database). You can also download the images from Kaggle. 
Kaggle also provides useful resources to explain certain category of images (such as lung opacity)
https://www.kaggle.com/zahaviguy/what-are-lung-opacities
Please refer to these resources to obtain domain knowledge, and understand the difference between four groups of images.
2.	Unzip the downloaded (zip) file. There are four sub-folders, four excel files, and a readm.md.txt file. The readme file shows original source of the data, and detailed information about each group of images. Each excel file shows the size, format, and the URL source of the image. Each subfolder includes images in each group. 
 
3.	Please follow “CNN Image Classification [pdf] ” notebook to create your own CNN image classifiers to classify images into four categories.
4.	The implemented project should include following major tasks (required tasks):
a.	The project must include a cross-validation (either 5-fold or 10-fold). The reports must include both training and test results.
b.	Please vary the network structure, such as the number of convolution layers, the filter sizes, dropout layers (and different dropout degrees), and report the best model performance. 
c.	Please report the filters and their feature maps from at least one convolutional layer. Select one sample images from each class, and observe the filters and the feature maps. 
5.	Additional suggested tasks (not required, but suggested):
a.	Because deep neural network takes tremendous amount of time for training, and with limited resource, you may not be able to train a good classifier. Therefore, you can leverage pretrained network (such as VGG16 or VGG19: https://keras.io/api/applications/vgg/#vgg16-function) or Resnet (https://keras.io/api/applications/) to obtain features, and then add classification models. 
b.	You can compare your model vs. pretrained network for COVID-19 image classification.
c.	You can also add changes to the network (when fine tuning the pretrained network), such as add drop out layer, to compare the algorithm performance. 
