# Fashion_MNIST_Classification
Classification of 28x28 pixels of fashion images using Keras Neural Networks

## Classification Technique
- Keras Neural Networks
## Dataset
- [Fashion MNIST](https://research.zalando.com/welcome/mission/research-projects/fashion-mnist/)
## Built with
- Jupyter Notebook

### Problem Statement
- Fashion-MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples.
- Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.
- Here is an example how the data look like along with its Class Numbers

***
![](https://i.imgur.com/nj3xvxp.png)
***
<details><summary>Jupyter Notebook Index</summary><p>

* Problem Statement & Business Case
* Importing Libraries & Data Set
* Data Visualization
* Training the Model
* Neural Networks
* Evaluating the Model
* Summary
  </p></details><p></p>
  
### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot 

### Libraries Used

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sci-Kit Learn
- Keras

### Conlusion
- The model obtained is 94% accurate with the training dataset & 91% accurate with validation data set
- Model predicted 93% of accurate results with test data set taken.
- This model can be further used for any 28*28 image class predictions.
- Maintaining a higher epochs gives us better test data predictions.
