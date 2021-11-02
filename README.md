# MNIST-fashion-classification
We explored the basic of Deep Learning platform by perfoming a classification task of the fashion MNIST dataset . The notebook and the report we wrote include data exploration and manipulation , model selection and evaluation .

## MNIST-fashion dataset
The MNIST-fashion dataset contains 70,000 grayscale images in 10 categories. The images show individual articles of clothing at low resolution (28 by 28 pixels).

![](https://github.com/shaniklein/MNIST-fashion-classification/blob/main/images/fashion_MNIST.png)

Here, 60,000 images are used to train the network and 10,000 images to evaluate how accurately the network learned to classify images.

## Training
We ecplored 6 different models , all models architecrue can be found in [full report](https://github.com/shaniklein/MNIST-fashion-classification/blob/main/full%20report.pdf)

Training loss per epoch:
![](https://github.com/shaniklein/MNIST-fashion-classification/blob/main/images/models_comperesion.png)

## Evaluation
### Losses

| 	model  | 	test_loss| test_acc |
| -------- | --------- | ------- |
| model_1  | 7.910297  | 0.9852  |
| model_2  | 0.560745  | 0.9907  |
| model_3  | 0.574428  | 0.9860  |
| model_4  | 0.558946  | 0.9925  |
| model_5  | 0.575826  | 0.9841  |
| model_6  | 0.591517  | 0.9750  |
	

### Confusion matrix

![](https://github.com/shaniklein/MNIST-fashion-classification/blob/main/images/confusion_mat.png)


### per class accuracy


| 	model  | 	Top_acc  |Accessories_acc |	Bottom_acc    |
| -------- | --------- | -------------- |--------------|
| model_1  | 0.9867    |0.9924          | 0.9913       |
| model_2  | 0.9918    |0.9937          | 0.9959       |
| model_3  | 0.9873    |0.9920          | 0.9927       |
| model_4  | 0.9934    |0.9958          | 0.9958       |
| model_5  | 0.9860    |0.9914          | 0.9908       |
| model_6  | 0.9801    |0.9859          | 0.9840       |
		
More evalation mtrices such as percision, recall and f1-score and deeper analysis of the results can be found in  [full report](https://github.com/shaniklein/MNIST-fashion-classification/blob/main/full%20report.pdf)
			

		
		
