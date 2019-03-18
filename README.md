# nn-demo-keras
Demo notebooks for neural networks.

## Installation
1. install Conda (Python 3.7): https://docs.conda.io/en/latest/miniconda.html
2. make sure to have direct internet access or configure a web-proxy (for git and conda) - see web-proxy with conda below
3. check out this project: `git clone https://github.com/PhilipMay/nn-demo-keras.git`
4. change to the `nn-demo-keras` project directory
5. create new conda environment with python version 3.6: `conda create --name nn-demo python=3.6`
6. activate the new conda environment: `conda activate nn-demo`
7. install pip packages: `pip install -r pip-packages.txt`
8. install tool to use conda with jupyter: `conda instal nb_conda_kernels`
9. Start jupyter notebook: `jupyter notebook`
10. load the first notebook and execute it

## Use a web-proxy with conda
To use a web-proxy with conda you have to create a `.condarc` with the following content:

```
proxy_servers:
  http: http://user:pass@corp.com:8080
  https: https://user:pass@corp.com:8080

ssl_verify: False
```