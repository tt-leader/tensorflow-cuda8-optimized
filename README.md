## Why this repository

Inspired by [ghostplant's repo](https://github.com/ghostplant/tensorflow-cuda8-optimized), this repo provide Tensorflow-GPU builds for some CUDA versions not provided by official. 

It was build in docker and you can infer to the docker file if you want to build tensorflow binaries against other CUDA version.
Avaliable python wheels:

1. Centos 7 + CUDA 8.0 + cuDNN 6.0 + python 3.5.2 + tensorflow r1.8

    [tensorflow-1.8.0-cp35-cp35m-linux_x86_64.whl](https://github.com/tt-leader/tensorflow-cuda8-optimized/releases/download/tf1.8-py35-cuda8-cudnn6-centos7/tensorflow-1.8.0-cp35-cp35m-linux_x86_64.whl)


## How to use

Download the `.whl` file and install it by `pip`

`pip install --upgrade tensorflow-1.8.0-cp35-cp35m-linux_x86_64.whl`

## How to reproduce

1. Install docker on your system following the [official install doc](https://docs.docker.com/install/)

2. 

TODO