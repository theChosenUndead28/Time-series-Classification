# TimeSeries_Classification
Classification of Time-series data with RNN

# TeUS_RNN

##### Time-Series binary classification using RNNs 
##### Shekoofeh Azizi


### Aim
In this project we aim to implement and compare different RNN implementaion including LSTM, GRU and vanilla RNN for the task of time series binary classification. We also further visualize gate activities in different implementation to have a better understanding of the underlying signals.

### Data and results
Data could be any time-series data with binary label
Reults presented in detailed at [1]: 
(https://ieeexplore.ieee.org/abstract/document/8395313/)


### Credits
Using Python Keras library (Keras 2.x) with [Tensorflow] backend: (https://www.tensorflow.org/versions/r0.7/tutorials/recurrent/index.html#recurrent-neural-networks)


[1] Azizi, Shekoofeh, et al. "Deep Recurrent Neural Networks for Prostate Cancer Detection: Analysis of Temporal Enhanced Ultrasound." IEEE transactions on medical imaging (2018).

##### Tips for Running on GPU
#####    - export CUDA_VISIBLE_DEVICES="1"
#####    - THEANO_FLAGS=device=gpu1,floatX=float64 python  trainmodel.py
