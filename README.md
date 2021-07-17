# Detectron2_Tutorials
This is repository for basic tutorials to configure detectron2 i.e. an open source library of object detection by Facebook

## Installation Guide

1. Install `Python ≥ 3.6` 
   ```
   $ sudo apt-get update
   $ sudo apt-get install python3.6
   ```
2. OS Should be **Linux** or **macOS**
3. Installation CUDA (≥10) - _This tutorial is for CUDA-11.4_
   - Go to [NVIDIA Developer](https://developer.nvidia.com/cuda-downloads).
   - Select Compatible Variables `(Linux > x86_64 > Ubuntu > 18.04 > deb[local])`
   - Download Required Version of CUDA
      ```
      wget https://developer.download.nvidia.com/compute/cuda/11.4.0/local_installers/cuda-repo-ubuntu1804-11-4-local_11.4.0-470.42.01-1_amd64.deb
      ```
   - Install Downloaded Packge 
     ```
     sudo dpkg -i cuda-repo-ubuntu1804-11-4-local_11.4.0-470.42.01-1_amd64.deb
     ```
   - Adding Key 
     ```
     sudo apt-key add /var/cuda-repo-ubuntu1804-11-4-local/7fa2af80.pub
     ```
   - Installation of CUDA-11.4
     ```
     sudo apt-key add /var/cuda-repo-ubuntu1804-11-4-local/7fa2af80.pub
     ```
   - 
