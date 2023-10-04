# Handwritten-Digits-Classification--ANN
Implementing Artificial Neural Network For Handwritten Digits Classification

## Required Libraries
    => tensorflow
    => keras
    => matplotlib
    => numpy
    => seaborn

## Dataset
    Data is loaded from keras datasets
    => minist

## Data processing
    => train, test split
    => flatten the dataframes of x_train and x_test

## Model building
    model = keras.Sequential([
            keras.layers.Dense(100, input_shape=(784,), activation = 'relu'),
            keras.layers.Dense(50, activation = 'sigmoid'),
            keras.layers.Dense(10, activation = 'sigmoid')
    ])

## Compiling
    model.compile( optimizer = 'adam',
              loss = 'sparse_categorical_crossentropy',
              metrics = ["accuracy"]

## Evaluation
    loss: 5.8585 
    accuracy: 0.8790

## 
