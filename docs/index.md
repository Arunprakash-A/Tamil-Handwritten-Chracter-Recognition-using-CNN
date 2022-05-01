# Tamil Handwritten Character Recogniton Model
Tamil Handwritten character recognition using convolutional neural networks.
## Dataset: IWFHR-10 
### Samples from the dataset
![samples](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/Output/samples.png?raw=True)
  * Let's see the distribution of training samples to check whether the dataset is balanced or imbalanced. 
  ![Data Distribution](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/Output/trainDistribution.png?raw=True)
  * We can observe that there is a slight class imbalance (i.e., some classes have more training samples over other classes) problem
## Model Architecture:
  
![Model](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/Model/Architecture.JPG?raw=true)

## Training
 * Loss: Categorical Cross Entropy
 * Optimization: Nesterov Accelarated GD
 
## Performance
* The Performance Measure of the model for training and valiadation split. 
![Performance Measure](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/Output/download.png?raw=true)

## Confusion Matrix:
* The number of classes in the problem is 127.THerefore, We can plot the confusion matrix to get a coarse view of the performence of the model.
![Performance Measure](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/Output/ConfusionMatrix.png?raw=true )


## Download the model

[Download](https://drive.google.com/drive/folders/1CV3f37rgDHCnKLuJU0-3QUFVRHgYUxLB?usp=sharing)

## Download the Notebook 
[Notebook](https://github.com/Arunprakash-A/Tamil-Handwritten-Chracter-Recognition-using-CNN/blob/master/CodeNotebooks/tocr_train.ipynb)


