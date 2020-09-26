# Music Generation using RNN 

This assignment is a part of the "MIT 6.S191: Introduction to Deep Learning" lecture series.  All lecture slides and videos are available on the course website.<br> 
Do have a look at the course at http://introtodeeplearning.com <br> <br>
It is advised to use Google Colab for running this notebook.

In this assignment we'll be building an RNN model with LSTM architecture for music generation. We will train a model to learn the patterns in raw sheet music given in ABC notation and then use this model to generate new music. 
This notebook also used a package called "mitdeeplearning" which contains some convienence functions and will be imported along with the other dependencies. <br>
This package can be simply installed by using the command:

```python
pip install mitdeeplearning
```

The model we use follows this architecture: <br>
![Architecture](https://github.com/aamini/introtodeeplearning/blob/master/lab1/img/lstm_unrolled-01-01.png?raw=true)

