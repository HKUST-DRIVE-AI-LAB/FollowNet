
# FollowNet: A Comprehensive Benchmark for Car-Following Behavior Modeling
Source code for the following paper:

Chen, Xianda, et al. "FollowNet: A Comprehensive Benchmark for Car-Following Behavior Modeling." arXiv preprint arXiv:.

## Description
This notebook demonstrate how to achieve the car following models from traditonal models to data driven models. Motivation: given extracted car following events from five open datasets with the same data formate and train the car follow models. Author: Chen Xianda.
The extracted car following events are avaliable for download.
Provide a tutorial of the data format and how to run the traditional model and the data-driven model.

## Set Up Environment
`pip install -r requirements.txt`

## Data
Extracted car-following events are stored in `data/raw_data` folder. The colab tutorial take the highD data for experiments first. 

## Train 
Train IDM, NN, and LSTM models:  
`python train.py` 

Test IDM/NN/LSTM models:     
`python IDM_test.py` or `python IDMM_test.py`

## Pretrained Models
Pretrained models are stored in `trained_model/` folder. 

## Reference


## Contact
xchen595@connect.hkust-gz.edu.cn
