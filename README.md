# <div align="center"> Face Mask Classifier</div>
<p align="center">
  <img src="image.jpg">
</p>


Face Mask Classifier, Here we are implementing Deep Learning Classification Project in Tensorflow and Keras to classifies the Person with Mask and without Mask.

We can get huge dataset from Kaggle to train FaceMask Classification Model as two folders like with mask and without mask.

I preprocessed the images and changed names to 0_(i).jpg for with mask and 1_(i).jpg for without mask.(here i from 0 to len(dataset)) in one single folder.
By this we can get labels easily while training, And no need to create another csv file for labels.

Coming to Tensorflow, I used normal network architecture to train 5000 and test 1000 images with (64,64,3) size for faster training. we can use same (224,224,3) size if we have GPU based system.

We used BatchNormalization to rescaling, reshifting and train our model faster and used DropOut layer to Regularisation.   




We Used 5000 Images For Training and 1000 Images for Testing.

We used Batch Normalisation and Dropout Layers in TensorFlow. And Used ResNet Network Architecture to train our model in keras.



### DataSet Source :
 (https://www.kaggle.com/pranavsingaraju/facemask-detection-dataset-20000-images#__sid=js0)
