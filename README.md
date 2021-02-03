# Poker AI

Overview
--------
This is an implementation of a an artificial intelligence agent that plays 6-person no-limit hold 'em.

Setup
-----
- TensorFlow [documentation](https://www.tensorflow.org/versions/master/api_docs/python/index.html) 
  ``` bash
  # Ubuntu/Linux 64-bit
  $ sudo apt-get install python-pip python-dev
  # Ubuntu/Linux 64-bit, CPU only, Python 3.5
  $ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.11.0-cp35-cp35m-linux_x86_64.whl

  # Mac OS X
  $ sudo easy_install pip3
  $ sudo easy_install --upgrade six
  # Mac OS X, CPU only, Python 3.4 or 3.5:
  $ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/gpu/tensorflow-0.11.0-py3-none-any.whl
  
  
  $ sudo pip3 install --upgrade $TF_BINARY_URL
  ```
  
  
- Jupyter Notebook  [documentation](http://jupyter.readthedocs.io/en/latest/index.html)
  
  ``` bash
  $ pip3 install --upgrade pip
  $ pip3 install jupyter
  $ jupyter notebook
  ```
