# mnist-digit-classifier
Deep learning model from scratch to classify MNIST handwritten digits dataset

Summary: 
This project contains a deep learning model from scratch, loosely based on the "Neural Networks and Deep Learning" course from Coursera. This model was trained on the MNIST handwritten digit dataset, whose .csv file can be found at https://pjreddie.com/projects/mnist-in-csv/. 

In more detail, this project walks one through the steps of building the main functions of neural networks (including parameter initialization, computing forward prop, computing cost, computing backprop, updating parameters). Additionally, we learn how to conduct gradient checking, split data into training/validation sets, implement minibatch learning, and use pandas for one-hot encoding. Furthermore, this project combines these methods with elements of object-oriented programming as we create a class NeuralNetwork with member functions (e.g. training parameters, computing accuracy, and predicting outputs and probabilities for new data). Next, this project illustrates how to avoid overfitting the training data by keeping track of validation cost and accuracy after training for a few epochs. Finally, using digit_image_processor.ipynb, we can evaluate how our model performs on our own real-life handwritten digits by converting it into data the model can take in (note: it won't be as good as the ~98% accuracy we get on the test set, because our hand-drawn digits don't seem to match the distribution of training data in the MNIST set). 

Thanks for reading! Constructive criticism is always appreciated.
