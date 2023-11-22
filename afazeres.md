# Data pre-processing and preparation
  - resampling
  - feature extraction (mfccs, spectograms, chroma features)
  - split dataset into training, validation and test sets
    
# Model architecture definition
  - choosing architecture
      - MLP: definition of number of layers, neurons, activation function
      - CNN: 1D or 2D inputs, number layers, kinds of layers, filter dimensions, number of feature maps, etc.
      - RNN: kind of units used, kind of connections (uni or bidirectional); possible choice in this sense are vanilla RNNs, gated recurrent units (GRUs), long-short term memory (LSTM) networks, etc.
  - include layers for data preprocessing (convolutional, pooling and fully connected layers)
  - design output layer with number of classes
    
# Training strategies
  - optimizer
  - setting of the learning hyperparameters (learning rate, mini-batch size, number of epochs, etc.)
  - regularization techniques to adopt (early stopping, weight regularization, dropout, data augmentation, etc.)
  - possibility of using transfer learning (pre trained models like VGG or YAMNet)

    
# Performance evaluation
  - analyze metrics (accuracy, precision, recall, f1-score)
  - 10-fold cross validation (see https://urbansounddataset.weebly.com/urbansound8k.html)
  - confusion matrix, average classification accuracy and its sd over the 10 experiments


# Delivery
  - zip file: source code and intruction file on how to compile it (include version of interpreters)
  - (?) report:
    - brief description of the classification problem
    - brief description of deep learning solutions
    - implementation description (pre-processing, data-preparation, model design, learning strategy)
    - results (classification performance obtained by the different classifiers)
    - discussions and conclusions (comments on the performance obtained and final remarks)
