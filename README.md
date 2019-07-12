# Neural Networks Demo with Keras
This is a demo code to learn how to use neural networks for image recognition. It uses the MNIST dataset of handwritten digits. Technological we use [Python](https://www.python.org/), [Tensorflow](https://www.tensorflow.org/), [Keras](https://keras.io/) and [Jupyter Notebooks](https://jupyter.org/) to do the job.

- [01-MNIST-dense.ipynb](https://github.com/t-systems-on-site-services-gmbh/nn-demo-keras/blob/master/01-MNIST-dense.ipynb) is the first example. It uses a fully connected neural network.
- [02-MNIST-conv.ipynb](https://github.com/t-systems-on-site-services-gmbh/nn-demo-keras/blob/master/02-MNIST-conv.ipynb) is the second example. It is based on the first example, but uses a convolutional neural network. Here you can examine the improvement of accuracy, although the network has fewer params.

If you want to learn more about this topic, I very much recommend the book [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python) from Francois Chollet.

## Installation
1. install Conda (Python 3.7): https://docs.conda.io/en/latest/miniconda.html
2. make sure to have direct internet access or configure a web-proxy (for git and conda) - see web-proxy with conda below
3. check out this project: `git clone https://github.com/t-systems-on-site-services-gmbh/nn-demo-keras.git`
4. change to the `nn-demo-keras` project directory
5. create new conda environment with python version 3.6: `conda create --name nn-demo python=3.6`
6. activate the new conda environment: `conda activate nn-demo`
7. install pip packages: `pip install -r pip-packages.txt`
8. install tool to use conda with jupyter: `conda install nb_conda_kernels`
9. Start jupyter notebook: `jupyter notebook`
10. load the first notebook and execute it

## Use a web-proxy with conda
To use a web-proxy with conda, you have to create a `.condarc` with the following content:

```
proxy_servers:
  http: http://user:pass@corp.com:8080
  https: https://user:pass@corp.com:8080

ssl_verify: False
```
