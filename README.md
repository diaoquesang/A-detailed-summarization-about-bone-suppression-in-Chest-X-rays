# Diffusion  model  based  bone  suppression  in  Chest X-Rays

![](https://img.shields.io/badge/-Github-181717?style=flat-square&logo=Github&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Awesome-FC60A8?style=flat-square&logo=Awesome&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=FFFFFF)
![](https://img.shields.io/badge/-GoogleColab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=FFFFFF)

<div align="center">
   <img src="https://www.konicaminolta.com/global-en/healthcare/technology/imaging-processing/bs/img/img_technologo_imaging_processing_012.jpg"  width="50%"><img src="https://www.konicaminolta.com/global-en/healthcare/technology/imaging-processing/bs/img/img_technologo_imaging_processing_013.jpg" width="50%">
</div>

## 🏖️Introduction
This homepage lists some representative papers/codes/datasets all about bone suppression. We aim to constantly update the latest relevant papers and help the community track this topic. We also share with you a comprehensive understanding of diffusion models in detail. Please feel free to join us and contribute to the project. If you have any questions, please feel free to contact Zhanghao Benny Chan and Yifei Sun.


Zhanghao Benny Chan's email address is: <czh345068@gmail.com>


Yifei Sun's email address is: <sxsyf20@163.com>


## 🐈Bone Suppression Papers
We summarize each bone suppression paper's highlights, and you can view them through the link below if you like.

<https://docs.google.com/presentation/d/1KBkojHk-a7lGJuLotS6myb6UeifyTi9q/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true> 

The mainstream method of bone suppression is deep learning, and can be roughly classified into **5 + 1 (manual suppression)** categories roughly, namely **autoencoder**, **domain adaptation**, **distillation learning**, **GAN**, **convolutional neural networks**. We also add a list of papers of bone suppression applications like calcification, segmentation, and detection.

## Autoencoder

+ **Deep Feature Disentanglement Learning for Bone Suppression in Chest Radiographs**

  *Chunze Lin; Ruixiang Tang; Darryl D. Lin; Langechuan Liu; Jiwen Lu; Yunqiang Chen; Dashan Gao; Jie Zhou*

  ISBI 2020. [[PDF]](https://ieeexplore.ieee.org/document/9635451) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)

+ **Autoencoder-based bone removal algorithm from x-ray images of the lung**
  
  *Seweryn Kalisz; Michal Marczyk*

  BIBE 2021 [[PDF]](https://ieeexplore.ieee.org/document/9098399) [[Dataset for COVID-19 X-Ray]](https://github.com/lindawangg/COVID-Net) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)                      

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

+ ⭐**Learning Bone Suppression from Dual Energy Chest X-rays using Adversarial Networks**

  *Dong Yul Oh; Il Dong Yun*

  arxiv 2018. [[PDF]](https://arxiv.org/abs/1811.02628)

+ **Dilated conditional GAN for bone suppression in chest radiographs with enforced semantic features**

  *Zhizhen Zhou; Luping Zhou; Kaikai Shen*

  Medical Physics 2020. [[PDF]](https://pubmed.ncbi.nlm.nih.gov/32621786/) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)

+ **⭐Generating Dual-Energy Subtraction Soft-Tissue Images from Chest Radiographs via Bone Edge-Guided GAN**

  *Yunbi Liu; Mingxia Liu; Yuhua Xi; Genggeng Qin; Dinggang Shen; Wei Yang*

  MICCAI 2020. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-59713-9_65)

+ **Bone Suppression on Chest Radiographs With Adversarial Learning**

  *Jia Liang; Yuxing Tang; Youbao Tang; Jing Xiao; Ronald M. Summers*

  Medical Imaging 2020. [[PDF]](https://arxiv.org/abs/2002.03073) [[Dataset for RSNA]](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)

+ **⭐Image-to-Images Translation for Multi-Task Organ Segmentation and Bone Suppression in Chest X-Ray Radiography**

  *Mohammad Eslami; Solale Tabarestani; Shadi Albarqouni; Ehsan Adeli; Nassir Navab; Malek Adjouadi*

  IEEE Transactions on Medical Imaging 2020. [[PDF]](https://ieeexplore.ieee.org/document/8999560) [[Github]](https://github.com/mohaEs/image-to-images-translation) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression) [[Dataset for JSRT bone masks]](https://doi.org/10.25919/5c49548be0551)

+ **⭐Spatial feature and resolution maximization GAN for bone suppression in chest radiographs**

  *Geeta Rani; Ankit Misra; Vijaypal Singh Dhaka; Ester Zumpano; Eugenio Vocaturo*

  Computer Methods and Programs in Biomedicine 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0169260722004060) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)

+ **GAN-based disentanglement learning for chest X-ray rib suppression**

  *Luyi Han; Yuanyuan Lyu; Cheng Peng; S. Kevin Zhou*

  Medical Image Analysis 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841522000226?via%3Dihub#bib0002) [[Dataset for LIDC-IDRI]](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254)

+ **Applying a Conditional GAN for Bone Suppression in Chest Radiography Images**

  *Hugo Eduardo Ziviani; Guillermo C´amara Ch´avez; Mateus Coelho Silva*

  SBC 2022. [[PDF]](https://sol.sbc.org.br/index.php/semish/article/view/20794)

## Convolutional Neural Network

+ **Bone suppression on pediatric chest radiographs via a deep learning-based cascade model**

  *Kyungjin Cho; Jiyeon Seo; Sunggu Kyung; Mingyu Kim; Gil-Sun Hong; Namkug Kim*

  Computer Methods and Programs in Biomedicine 2022. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0169260722000128?via%3Dihub)

+ **⭐Cascade of multi-scale convolutional neural networks for bone suppression of chest radiographs in gradient domain**

  *Wei Yang; Yingyin Chen; Yunbi Liu; Liming Zhong; Genggeng Qin; Zhentai Lu;Qianjin Feng; Wufan Chen*

  Medical Image Analysis 2017. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1361841516301529)

+ **⭐Deep Learning Models for Bone Suppression in Chest Radiographs**

  *Maxim Gusarev; Ramil Kuleev; Adil Khan; Adin Ramirez Rivera; Asad Masood Khattak*

  CIBCB 2017. [[PDF]](https://ieeexplore.ieee.org/abstract/document/8058543) [[Github]](https://github.com/danielnflam/Deep-Learning-Models-for-bone-suppression-in-chest-radiographs) [[Dataset for bone suppression]](https://drive.google.com/drive/folders/1VLD9deplqACJpdd47EdZCVW2BIN4eM95?usp=sharing)

+ **Bone Suppression of Chest Radiographs With Cascaded Convolutional Networks in Wavelet Domain**

  *Yingyin Chen; Xiaofang Gou; Xiuxia Feng; Yunbi Liu; Genggeng Qin; Qianjin Feng; Wei Yang; Wufan Chen*

  IEEE ACCESS 2019. [[PDF]](https://ieeexplore.ieee.org/document/8604005)

+ **Separation of bones from soft tissue in chest radiographs: Anatomy-specific orientation-frequency-specific deep neural network convolution**

  *Amin Zarshenas; Junchi Liu; Paul Forti; Kenji Suzuki*

  Medical Physics 2020. [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6510604/)

+ **Bone Structures Extraction and Enhancement in Chest Radiographs via CNN Trained on Synthetic Data**

  *Ophir Gozes; Hayit Greenspan*

  ISBI 2020. [[PDF]](https://arxiv.org/abs/2003.10839) [[Dataset for LIDC-IDRI]](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254) [[Dataset for NIH X-Ray14]](https://www.kaggle.com/datasets/nih-chest-xrays/data)

+ **⭐Bone suppression for chest X-ray image using a convolutional neural filter**

  *Naoki Matsubara; Atsushi Teramoto, Kuniaki Saito; Hiroshi Fujita*

  Physical and Engineering Sciences in Medicine 2020. [[PDF]](https://link.springer.com/article/10.1007/s13246-019-00822-w)

+ **⭐Improving Tuberculosis Recognition on Bone-Suppressed Chest X-rays Guided by Task-Specific Features**

  *Yunbi Liu; Genggeng Qin; Yun Liu; Mingxia Liu; Wei Yang*

  PRIME 2021. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-87602-9_6)

+ **Isometric Convolutional Neural Networks for Bone Suppression of Multi-Planar Dual Energy Chest Radiograph**

  *Yossathorn Tianrungroj; Iba Hitoshi*

  IIAIAAI 2022. [[PDF]](https://ieeexplore.ieee.org/document/9894637)

+ **Deep learning-based bone suppression in chest radiographs using CT-derived features: a feasibility study**

  *Ge Ren; Haonan Xiao; Sai-Kit Lam; Dongrong Yang; Tian Li; Xinzhi Teng; Jing Qin; Jing Cai*

   Quantitative Imaging in Medicine and Surgery 2021. [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8611463/)

## Bone Suppression Application

+ **Dual energy subtraction: Principles and clinical applications**

  *Peter Vock; Zsolt Szucs-Farkas*

   European Journal of Radiology 2009. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0720048X09001739)

+ **When Does Bone Suppression And Lung Field Segmentation Improve Chest X-Ray Disease Classification?**

  *Ivo M. Baltruschat; Leonhard Steinmeister; Harald Ittrich; Gerhard Adam; Hannes Nickisch; Axel Saalbach; Jens von Berg; Michael Grass; Tobias Knopp*

   ISBI 2019. [[PDF]](https://ieeexplore.ieee.org/document/8759510)

+ **⭐Evaluation of Deep Learning Method for Bone Suppression from Dual Energy Chest Radiography**

  *Ilyas Sirazitdinov; Konstantin Kubrak; Semen Kiselev; Alexey Tolkachev; Maksym Kholiavchenko; Bulat Ibragimov*

   ICANN 2020. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-030-61609-0_20)

+ **⭐Chest X-ray Bone Suppression for Improving Classification of Tuberculosis-Consistent Findings**

  *Sivaramakrishnan Rajaraman; Ghada Zamzmi; Les Folio;; Philip Alderson; Sameer Antani*

   Diagnostics 2021. [[PDF]](https://www.mdpi.com/2075-4418/11/5/840) [[Github]](https://github.com/sivaramakrishnan-rajaraman/CXR-bone-suppression) [[Dataset for Montgomery TB CXR]](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-montgomery) [[Dataset for Shenzhen TB CXR]](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen)[[Dataset for RSNA CXR]](https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data) [[Dataset for Pediatric pneumonia CXR]]( https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)       
  
+ **Value of bone suppression software in chest radiographs for improving image quality and reducing radiation dose**

  *Gil-Sun Hong; Kyung-Hyun Do; A-Yeon Son; Kyung-Wook Jo; Kwang Pyo Kim; Jihye Yun; Choong Wook Lee*

   European Radiology 2021. [[PDF]](https://link.springer.com/article/10.1007/s00330-020-07596-w)
  
+ **Bone Suppression on Chest Radiographs for Pulmonary Nodule Detection: Comparison between a Generative Adversarial Network and Dual-Energy Subtraction**

  *Kyungsoo Bae; Dong Yul Oh; Il Dong Yun; and Kyung Nyeo Jeon*

   Korean Journal of Radiology 2022. [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8743147/)

+ **Improved detection of solitary pulmonary nodules on radiographs compared with deep bone suppression imaging**

  *Jiefang Wu; Weiguo Chen; Fengxia Zeng; Le Ma; Weimin Xu; Wei Yang; Genggeng Qin*

   Quantitative Imaging in Medicine and Surgery 2021. [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8408784/)

+ **⭐DeBoNet: A deep bone suppression model ensemble to improve disease detection in chest radiographs**

  *Sivaramakrishnan Rajaraman; Gregg Cohen; Lillian Spear; Les Folio; Sameer Antani*

   PLOS ONE 2022. [[PDF]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0265691) [[Github]](https://github.com/sivaramakrishnan-rajaraman/Bone-Suppresion-Ensemble)

+ **Development and validation of bone-suppressed deep learning classification of COVID-19 presentation in chest radiographs**

  *Ngo Fung Daniel Lam; Hongfei Sun; Liming Song; Dongrong Yang; Shaohua Zhi; Ge Ren; Pak Hei Chou; Shiu Bun Nelson Wan; Man Fung Esther Wong; King Kwong Chan; Hoi Ching Hailey Tsang; Feng-Ming (Spring) Kong; Yì Xiáng J. Wáng; Jing Qin; Lawrence Wing Chi Chan; Michael Ying; Jing Cai*

   Quantitative Imaging in Medicine and Surgery 2022. [[PDF]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9246721/) [[Dataset for JSRT bone suppression]](https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression)
## Datasets
### Original Chest X-Rays and corresponding bone masks:
241 paired JSRT  origianl and bone masks: https://www.kaggle.com/datasets/yoctoman/jsrt-original-and-bone-masks?resource=download)
### Original Chest X-Rays and corresponding bone suppressed images:
241 paired JSRT  original and bone suppressed images: https://aistudio.baidu.com/aistudio/datasetdetail/234557)


## Diffusion Models Feast
This section provides a detailed description of the diffusion model (including code explanations, paper readings, etc.).
Most of the materials are from Hugging Face Diffusion Models Course(https://github.com/huggingface/diffusion-models-class)

Now, let's dive into it!

👩‍🎓Unit 1: An Introduction to Diffusion Models

There are two parts to this unit, namely Introduction to Diffusers and Diffusion Models from Scratch.

🧨In Introduction to Diffusers, we show the different steps described above using building blocks from the diffusers library. You'll quickly see how to create, train, and sample your own diffusion models on whatever data you choose. By the end of the notebook, you'll be able to read and modify the example training script to train diffusion models and share them with the world! This notebook also introduces the main exercise associated with this unit, where we will collectively attempt to figure out good 'training recipes' for diffusion models at different scales. See the next section for more info.

🤗Here is our code explanation: https://colab.research.google.com/drive/19APZrmXaIfSsfiz2Oxdx42VBmLKjTxsj?usp=sharing

🧑‍🔬In Diffusion Models from Scratch, we show those same steps (adding noise to data, creating a model, training and sampling) but implemented from scratch in PyTorch as simply as possible. Then we compare this 'toy example' with the diffusers version, noting how the two differ and where improvements have been made. The goal here is to gain familiarity with the different components and the design decisions that go into them so that when you look at a new implementation you can quickly identify the key ideas.

## Some Additional Resources
### Bone Suppression
🎈[[Implementation and evaluation of a bony structure suppression software tool for chest X-ray imaging]](https://open.uct.ac.za/bitstream/handle/11427/11993/thesis_sci_2012_dixon_t.pdf?sequence=1&isAllowed=y)

✈️[[Bone Suppression Methods of ChestRadiographs Based on Deep ConvolutionalNetworks]](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C447WN1SO36whLpCgh0R0Z-iDdIt-WSAdV5IJ_Uy2HKRASwkzLAGLLtVEZ-SelJ51Hxf62QC3j-G2InLwUtUGiZw&uniplatform=NZKPT)

🌼[[Research on bone suppression of chest radiography]](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C475KOm_zrgu4lQARvep2SAk-6BvX81hrs37AaEFpExs0H61xq0Ry5eFrgGdZ6duZtCnOvbyB7URSgaHeE75Ii0j&uniplatform=NZKPT)
### Diffusion Models
🚙[[Hugging Face Diffusion Models Course]](https://github.com/huggingface/diffusion-models-class)

☕[[AI Coffee Break video on Diffusion Models]](https://www.youtube.com/watch?v=344w5h24-h8)

🏋️‍♂️[[Lil’Log about Diffusion Models]](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)

🗺[[Hungyi Lee's video on Diffusion Models]](https://www.youtube.com/watch?v=azBugJzmz-o)

🤗[[Some Awesome Diffusion Models]](https://github.com/diff-usion/Awesome-Diffusion-Models)

🍆[[Denoising Diffusion Models: A Generative Learning Big Bang]](https://cvpr2023-tutorial-diffusion-models.github.io/)

🧋[[A Survey on Generative Diffusion Models]](https://arxiv.org/abs/2209.02646)

Found more great resources? Let us know and we'll add them to this list.
