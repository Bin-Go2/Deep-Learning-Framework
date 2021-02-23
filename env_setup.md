
## Prerequisite: 
* Linux
* Anaconda
  1. `conda create -n DL-framework python=3.7`
  2. `conda activate DL-framework`
  3. `pip install jupyter`
* GPU



## PyTorch Setup

1. Check CUDA version
  * `nvcc -V`
  ```
  nvcc: NVIDIA (R) Cuda compiler driver
  Copyright (c) 2005-2019 NVIDIA Corporation
  Built on Wed_Oct_23_19:24:38_PDT_2019
  Cuda compilation tools, release 10.2, V10.2.89
  ```
2. Install Pytorch suited to machine
* `conda install pytorch==1.6.0 torchvision==0.7.0 cudatoolkit=10.2 -c pytorch`
*  You can use `conda list | grep torch` to check the version of PyTorch that you installed 
  
Bingo! Let's go PyTorch!



