# DL_practical_problems

## HW1 - BasicMLPs
hw1 contains 3 main notebooks
* The first one is about pytorch basics and different operations on tensors and other pytoch properties.
* In NN_from_scratch, I implemented a vanilla MLP from scratch using numpy and trained it on mnist.
* In the main notebook, we implement different optimization methods like SGD or Adam and test them on Ackley and Baele functions.

## HW2 - CNN
* HW2_CNN_TODO is introducing us to CNN architectures and asks us to implement a CNN arch on our choice, acquiring acc more than a threshold t. Also introduces us to feature maps.
* YOLO was about the YOLO model which is a CNN model of object detection. We implemented it from scratch.
* The last notebook is about implementing and training ResNet18 and UNet(for colorization) on Cifar10.

## HW3 - Transformers
this hw, contains 4 notebooks:

* RNN and LSTM:
  1. In the first part, the task was predicting the corresponding language of a name. I implemented an RNN model from scratch to classify names.
  2. The second task was image classification on mnist. I implemented a multi-layer LSTM from scratch and achieved 98% accuracy easily.
  3. In the last part, I preprocessed IMDb reviews dataset and ran a model based on nn.LSTM for sentiment analysis. I achieved around 90% with few epochs and parameters due to lack of time.
* simpleGPT:
  1. This notebook is about training a character-level decoder-only transformer to generate tokens given a dummy context. The dataset was friend dialogs.

* Bert MLM and CLS:
  1. In the first part I finetuned Bert for the task of masked language modeling in pyTorch. Next, I trained the huggingface Bertmlm directly using its API.
  2. In the second part, the task was classification using the cls token. like the last part, I fine-tuned Bert once fine-tuning in pyTorch and once using huggingface API.
* iTransformer:
  1. It was a long time series problem in which, v variables were changing over time and the task was predicting the next time step values. In the first part, I trained a transformer and gave the series to the encoder and decoder. the result was good but not the best.
  2. The second part, was implementing iTransformer. iTransformer is the recent breakthrough in time series (the paper is indexed at ICLR 2024). I re-implemented iTransformer and achieved very great results.
  
