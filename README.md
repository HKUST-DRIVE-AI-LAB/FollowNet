
# FollowNet: A Comprehensive Benchmark for Car-Following Behavior Modeling
Source code for the following paper:

Chen, Xianda, et al. "FollowNet: A Comprehensive Benchmark for Car-Following Behavior Modeling." arXiv preprint arXiv:.

## Description
This notebook demonstrate how to achieve the car following models from traditonal models to data driven models. Motivation: given extracted car following events from five open datasets with the same data formate and train the car follow models. Author: Chen Xianda.
The extracted car following events are avaliable for download.
Provide a tutorial of the data format and how to run the traditional models and the data-driven models.

## Data
Extracted car-following events are stored in `data/` folder. The colab tutorial take the highD data for experiments first. 

## 🛠 Quick Start 
Run the colab notebook directly without other environment setup! Details are in the notebook below. You can run some examples directly in Colab. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jB-eM9A1N1q5mPv3TjZPx6drezvURtqD?usp=share_link) 

## Pretrained Models
Pretrained models are stored in `trained_model/` folder. 


## Dataset distribution
Below is the average time gap during car following (s)

![](results/time_gap.jpg)

## Evaluation Metrics

Collsion rate

![](results/Collision.jpg)

 MSE of spacing

![](results/mse.jpg)


## Contact
meixin@ust.hk

  xchen595@connect.hkust-gz.edu.cn

## 📎 References

If you use FollowNet in your own work, please cite:

```latex
@article{****}
}
```

