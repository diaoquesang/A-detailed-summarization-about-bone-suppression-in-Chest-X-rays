# Diffusion  model  based  bone  suppression  in  Chest X-Rays

![](https://img.shields.io/badge/-Github-181717?style=flat-square&logo=Github&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Awesome-FC60A8?style=flat-square&logo=Awesome&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=FFFFFF)
![](https://img.shields.io/badge/-GoogleColab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=FFFFFF)

<div align="center">
   <img src="https://www.konicaminolta.com/global-en/healthcare/technology/imaging-processing/bs/img/img_technologo_imaging_processing_012.jpg"  width="50%"><img src="https://www.konicaminolta.com/global-en/healthcare/technology/imaging-processing/bs/img/img_technologo_imaging_processing_013.jpg" width="50%">
</div>

## Introduction
This homepage lists some representative papers/codes/datasets all about bone suppression. We aim to constantly update the latest relevant papers and help the community track this topic. We also share with you a comprehensive understanding of diffusion models in detail. Please feel free to join us and contribute to the project. If you have any questions, please feel free to contact Zhanghao Benny Chan and Yifei Sun.


Zhanghao Benny Chan's email address is: <czh345068@gmail.com>


Yifei Sun's email address is: <sxsyf20@163.com>


## Bone Suppression Papers
We summarize each bone suppression paper's highlights, and you can view them through the link below if you like.

<https://docs.google.com/presentation/d/1KBkojHk-a7lGJuLotS6myb6UeifyTi9q/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true> 

The mainstream method of bone suppression is deep learning, and can be classified into **5 + 1 (manual suppression)** categories roughly, namely **autoencoder**, **domain adaptation**, **distillation learning**, **GAN**, **convolutional neural networks**.

## Autoencoder

+ **Deep Feature Disentanglement Learning for Bone Suppression in Chest Radiographs**

  *Chunze Lin; Ruixiang Tang; Darryl D. Lin; Langechuan Liu; Jiwen Lu; Yunqiang Chen; Dashan Gao; Jie Zhou*

  ISBI 2020. [[PDF]](https://ieeexplore.ieee.org/document/9635451)

+ **Autoencoder-based bone removal algorithm from x-ray images of the lung**
  
  *Seweryn Kalisz; Michal Marczyk*

  BIBE 2021 [[PDF]](https://ieeexplore.ieee.org/document/9098399)

## Distillation Learning

+ **Bone suppression of lateral chest x-rays with imperfect and limited dual-energy subtraction images**

  *Yunbi Liu; Fengxia Zeng; Mengwei Ma c; Bowen Zheng; Zhaoqiang Yun; Genggeng Qin; Wei Yang; Qianjin Feng*

  Computerized Medical Imaging and Graphics 2023. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0895611123000046?via%3Dihub)

## Domain Adaptation

+ **From 3D to 2D: Transferring knowledge for rib segmentation in chest X-rays**

  *Hugo Oliveira; Virginia Mota; Alexei M.C. Machado; Jefersson A. dos Santos*

  Pattern Recognition Letters 2020. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0167865520303561?ref=pdf_download&fr=RR-2&rr=7f77f615ea876e5e)

+ **High-Resolution Chest X-Ray Bone Suppression Using Unpaired CT Structural Priors**

  *Han Li; Hu Han; Zeju Li; Lei Wang; Zhe Wu; Jingjing Lu; S. Kevin Zhou*

  IEEE Transactions on Medical Imaging 2020. [[PDF]](https://ieeexplore.ieee.org/document/9058664)

## Manual Suppression

+ **Segmentation of Anatomical Structures on Chest Radiographs**

  *S. Juhász; Á. Horváth; L. Nikházy; G. Horváth & Á. Horváth*

  XII Mediterranean Conference on Medical and Biological Engineering and Computing 2010. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-642-13039-7_90)

## GAN

+ **Generation of Virtual Dual Energy Images from Standard Single-Shot Radiographs using Multi-scale and Conditional Adversarial Network**

  *Bo Zhou; Xunyu Lin; Brendan Eck; Jun Hou; David L. Wilson*

  ACCV 2018. [[PDF]](https://arxiv.org/abs/1810.09354) [[Github]](https://github.com/bbbbbbzhou/Virtual-Dual-Energy)

+ **Learning Bone Suppression from Dual Energy Chest X-rays using Adversarial Networks**

  *Dong Yul Oh; Il Dong Yun*

  arxiv 2018. [[PDF]](https://arxiv.org/abs/1811.02628)

+ **Dilated conditional GAN for bone suppression in chest radiographs with enforced semantic features**

  *Zhizhen Zhou; Luping Zhou; Kaikai Shen*

  Medical Physics 2020. [[PDF]](https://pubmed.ncbi.nlm.nih.gov/32621786/)

+ **Generating Dual-Energy Subtraction Soft-Tissue Images from Chest Radiographs via Bone Edge-Guided GAN**

  *Yunbi Liu; Mingxia Liu; Yuhua Xi; Genggeng Qin; Dinggang Shen; Wei Yang*

  MICCAI 2020. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-59713-9_65)

+ **Bone Suppression on Chest Radiographs With Adversarial Learning**

  *Jia Liang; Yuxing Tang; Youbao Tang; Jing Xiao; Ronald M. Summers*

  Medical Imaging 2020. [[PDF]](https://arxiv.org/abs/2002.03073)

+ **Image-to-Images Translation for Multi-Task Organ Segmentation and Bone Suppression in Chest X-Ray Radiography**

  *Mohammad Eslami; Solale Tabarestani; Shadi Albarqouni; Ehsan Adeli; Nassir Navab; Malek Adjouadi*

  IEEE Transactions on Medical Imaging 2020. [[PDF]](https://ieeexplore.ieee.org/document/8999560) [[Github]](https://github.com/mohaEs/image-to-images-translation)

+ **Spatial feature and resolution maximization GAN for bone suppression in chest radiographs**

  *Geeta Rani; Ankit Misra; Vijaypal Singh Dhaka; Ester Zumpano; Eugenio Vocaturo*

  Computer Methods and Programs in Biomedicine 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0169260722004060)

+ **GAN-based disentanglement learning for chest X-ray rib suppression**

  *Luyi Han; Yuanyuan Lyu; Cheng Peng; S. Kevin Zhou*

  Medical Image Analysis 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841522000226?via%3Dihub#bib0002)

+ **Applying a Conditional GAN for Bone Suppression in Chest Radiography Images**

  *Hugo Eduardo Ziviani; Guillermo C´amara Ch´avez; Mateus Coelho Silva*

  SBC 2022. [[PDF]](https://sol.sbc.org.br/index.php/semish/article/view/20794)

## Convolutional Neural Network

+ **Bone suppression on pediatric chest radiographs via a deep learning-based cascade model**

  *Kyungjin Cho; Jiyeon Seo; Sunggu Kyung; Mingyu Kim; Gil-Sun Hong; Namkug Kim*

  Computer Methods and Programs in Biomedicine 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0169260722000128?via%3Dihub)

+ **Cascade of multi-scale convolutional neural networks for bone suppression of chest radiographs in gradient domain**

  *Wei Yang; Yingyin Chen; Yunbi Liu; Liming Zhong; Genggeng Qin; Zhentai Lu;Qianjin Feng; Wufan Chen*

  Medical Image Analysis 2017. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841516301529)

+ **Deep Learning Models for Bone Suppression in Chest Radiographs**

  *Maxim Gusarev; Ramil Kuleev; Adil Khan; Adin Ramirez Rivera; Asad Masood Khattak*

  CIBCB 2017. [[PDF]](https://ieeexplore.ieee.org/abstract/document/8058543) [[Github]](https://github.com/danielnflam/Deep-Learning-Models-for-bone-suppression-in-chest-radiographs)

+ **Bone Suppression of Chest Radiographs With Cascaded Convolutional Networks in Wavelet Domain**

  *Yingyin Chen; Xiaofang Gou; Xiuxia Feng; Yunbi Liu; Genggeng Qin; Qianjin Feng; Wei Yang; Wufan Chen*

  IEEE ACCESS 2019. [[PDF]](https://ieeexplore.ieee.org/document/8604005)


## Datasets
### Original Chest X-Rays and corresponding bone masks:
241 paired JSRT  origianl and bone masks: https://www.kaggle.com/datasets/yoctoman/jsrt-original-and-bone-masks?resource=download)
### Original Chest X-Rays and corresponding bone suppressed images:
241 paired JSRT  original and bone suppressed images: https://aistudio.baidu.com/aistudio/datasetdetail/234557)




















## Diffusion Models Feast
