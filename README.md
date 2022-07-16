# Ultrasound Classification: Deep Neural Networks in Python 

### Objectives: 
- Train a multi-layer neural network model that classifies potentially cancerous breast ultrasounds as benign, malignant, or normal 
- Experiment with different layering techniques, data augmentation, and transfer learning 
- Determine the most accurate and efficient model built 

### How to view: `breastDNN.ipynb`
- step by step explanations of the deep learning process, concepts, and techniques 
- Python code with descriptions of how packages and methods are used
- visualizations (ultrasound images and model evaluation plots)
- data set details and citations

### Process Overview:
1. read in ultrasound images into numpy arrays size 500 x 500
2. randomly split data into training and testing sets 
3. pre-process images into framework that `Keras` can train a model on
4. model building and experimentation with the following techniques: 
    - 2D convolutional layers 
    - max pooling layers 
    - linear layers 
    - l2 regularization 
    - batch normalization 
    - dropout layer
5. data augmentation: artificial expansion of training set by random alterations to the images (vertical shifts and flips, horizontal shifts and flips, random rotation, random zoom)
6. transfer learning: classification using the state-of-the-art pre-trained model VGG-16
7. computation and plotting of cross entropy loss, test set accuracy, and misclassification rate for each model 

### Major Libraries Used:
- `Keras`
- `Tensorflow 2`
- `Numpy`
- `Sklearn`
- `Matplotlib`
- `torch`
- `PlaidML`
