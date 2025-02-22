> [**Multispectral Semantic Segmentation for UAVs: A Benchmark Dataset and Baseline**]()  

> Qiusheng Li1 Hang Yuan1 Tianning Fu1 Zhibin Yu1,2,† Bing Zheng1,2 Shuguo Chen2

1College of Electronic Engineering,Ocean University of China

2Key Laboratory of Ocean Observation and Information of Hainan Province,
Sanya Oceanographic Institution, Ocean University of China

† corresponding author: yuzhibin@ouc.edu.cn; Project website: https://github.com/yzbouc/UAVM

This repository contains the dataset of the  paper "Multispectral Semantic Segmentation for UAVs: A Benchmark Dataset and Baseline"

## Abstract

Solidago canadensis L. is a typical invasive plant that has become a significant threat worldwide and profoundly impacts local ecosystems. An unmanned aerial vehicle (UAV)-based semantic segmentation (SS) system can help in monitoring the spread and location of Solidago canadensis L. To identify the growth range of this species with greater efficiency, we employ a high-speed multispectral camera, which provides richer color information and features with limited resolution, in conjunction with a high-quality RGB camera to construct a segmentation dataset. We construct a validated UAV multispectral (UAVM) dataset comprising 3260 pairs of calibrated RGB and multispectral images. All the images in the dataset underwent semantic annotation at a fine-grained pixel level, with 12 categories being covered. In addition, other plant categories can be employed in precision agriculture and ecological conservation. Moreover, we propose a benchmark model, UAVM semantic segmentation network (UAVMNet). With the aid of the feature alignment module and the UAVMFuse module, UAVMNet efficiently integrates multispectral and high-quality RGB image information, enhancing its ability to perform semantic segmentation tasks effectively. To the best of our knowledge, this is the first model to colearn semantic representations via high-quality RGB and paired multispectral information on a UAV platform. We conduct comprehensive experiments on the proposed UAVM dataset.

## Dataset display

> ![Alt text](/Pictures/fig1.png)
> ![Alt text2](/Pictures/fig2.png)

## Method

> ![Alt text2](/Pictures/UAVMNet.png)

## Update

- **2025.2.22:** The UAVM dataset has been published.

- Dataset is aviable at https://pan.baidu.com/s/1WeXbhfWURbxv7A7E1Ayn6Q. Exreaction code:8mmr

- **2024.9.4:** Accepted by IEEE Transactions on Geoscience and Remote Sensing!
  
  ## Citation
  
  ```
  @article{li2024multispectral,
  title={Multispectral Semantic Segmentation for UAVs: A Benchmark Dataset and Baseline},
  author={Li, Qiusheng and Yuan, Hang and Fu, Tianning and Yu, Zhibin and Zheng, Bing and Chen, Shuguo},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2024},
  publisher={IEEE}
  }
  ```
