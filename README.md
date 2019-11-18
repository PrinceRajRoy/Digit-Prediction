# Digit-Recognition

The project takes MNIST Digit Data as input for training and predicts the corresponding digit based on the image.

The CNN model used in this project is as follows

#### `Input -> Conv2D -> MaxPool2D -> Conv2D -> MaxPool2D -> Flatten -> Dense -> Dropout -> Output`

Steps To Run :-

1) Open the project in Jupyter
2) Click On Cell -> Run All
3) For Testing Any Data Point Prediction say i, plot the data point from test set and print the corresponding prediction as follows :-
#### `plt.imshow(xtest[i])`
#### `print(np.argmax(predictions[i]))`
