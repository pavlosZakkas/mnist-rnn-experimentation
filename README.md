# Recurrent Neural Networks (RNN) experimentation

Sequences of simple mathematical operations is used to experiment with a variety of neural networks including text-to-text, image-to-text, text-to-image.

Mnist dataset was used in order to create the dataset of sequences of mathematical operations.

## Text-to-text
**Given** a simple mathematical operation as a **sequence of characters**, **return** a **sequence of characters** representing the output of the operation.

Different models were examined, including SimpleRNN, LSTM, GRU networks.

## Image-to-text
**Given** a simple mathematical operation as a **sequence of images**, **return** a **sequence of characters** representing the output of the operation.

Various models were used, including a network of LSTM layers and a network of Convolutional layers followed by LSTM layers.

## Text-to-image
**Given** a simple mathematical operation as a **sequence of characters**, **return** a **sequence of images** representing the output of the operation.

A text-to-text network followed by a text-to-image upsampling convolutional network was trained with the usage of SSIM loss in order to produce the sequence of images representing the result of the operation.  
