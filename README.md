# ETL data on CPU and simultaneously Training model on GPU using TFDS
### We are going to use CPU for Extract , Transform and Load data from Tensorflow Dataset, and parallelly GPU for training model parallelly.

## The code is available for the same in notebook file present in this notebook.

* This code will not work on Google Colab as you cannot use both cpu and gpu in colab.
* Make sure you are running this code on Machine containing both CPU and GPU and tensorflow with GPU support. You can find tensorflow gpu installation documentation [here](https://towardsdatascience.com/how-to-install-tensorflow-gpu-on-ubuntu-18-04-1c1d2d6d6fd2).
* If you are getting 
```python
ValueError: No data provided for "input_1". Need data for each key in: ['input_1']
```
Then you are either running code on google colab or on a machine which has either cpu or gpu only.

The blog for same will be available [here](https://towardsdatascience.com/@novasush) soon.