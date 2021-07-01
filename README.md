# OCT-A-quality-improvement-for-Maestro2
## Project information:
Project NO.: 2021*****

Contributor: Shiyi Liu

Timeline: 2021 Q2 - 2021 Q4

## Description:
### Aim: 
improve the quality of Maestro2 OCT(A) images by developing deep learning models without requirement of repeated scans

### History version: 

7/1/2021, Shiyi Liu, initial test, test new dataset on the built model.

7/2/2021, Shiyi Liu, development, a new model ** added.

## Environment requirements
- Linux
- Python with numpy
- NVIDIA GPU + CUDA 8.0 + CuDNNv5.1
- TensorFlow 0.11

## Usage
- Clone this repo:
```
git clone git@github.com:shiyiliu/******
```

- Download the dataset:
\\oak-rdshare\dataset

- Pull the Docker image:
\\oak-rdshare\docker\shiyi_test:test.tar

- Environment setup:
```
Docker load –-input location/shiyi_test:test.tar
```

- Train the model:
```
python main.py --phase train
```
