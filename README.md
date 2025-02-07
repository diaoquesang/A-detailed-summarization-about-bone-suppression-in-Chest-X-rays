# Bone suppression in Chest X-rays: A deep survey (Keep on updating)

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


Zhanghao Chen's email address is: <czh345068@gmail.com> or <bennychan@hdu.edeu.cn>


Yifei Sun's email address is: <sxsyf20@163.com>


## 🐈Bone Suppression Papers
We summarize each bone suppression and diffusion models based papers' highlights, and you can view them through the link below if you like.

<https://docs.google.com/presentation/d/1JTPUMrqcJ3FQLsop_rtFtiW4e7onhxoK/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true> 

The mainstream method of bone suppression is deep learning, and can be roughly classified into **5 + 1 (manual suppression)** categories roughly, namely **autoencoder**, **domain adaptation**, **distillation learning**, **GAN**, **convolutional neural networks**. We also add a list of papers of bone suppression applications like calcification, segmentation, and detection. More details are listed in https://docs.google.com/spreadsheets/d/1Ip1XWtMDotmN-i82OPshxOWj1SnD7Ncl/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true
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

  **By the way, BSE-JSRT dataset was just created by using this method!**

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

  Anais do XLIX Seminário Integrado de Software e Hardware 2022. [[PDF]](https://sol.sbc.org.br/index.php/semish/article/view/20794)

+ **Cycle-generative adversarial network-based bone suppression imaging for highly accurate markerless motion tracking of lung tumors for cyberknife irradiation therapy**
   
  *Zennosuke Mochizuki, Masahide Saito, Toshihiro Suzuki, Koji Mochizuki, Junichi Hasegawa, Hikaru Nemoto, Kenichiro Satani, Hiroshi Takahashi, Hiroshi Onishi*

  Journal of Applied Clinical Medical Physics 2023. [[PDF]](https://aapm.onlinelibrary.wiley.com/doi/epdf/10.1002/acm2.14212)

+ **CycleGAN Based Bone Suppression Techniques for Standard CXR Images**

  *V.Santhosh Kumar Tangudu, Jagadeesh Kakarla, A.Sam Prabhu & Bala Vikranth Kumar*
  
   Pattern Recognition 2024. [[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-78195-7_19)
  
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

+ **Chest tomosynthesis image enhancement by bone suppression using convolutional neural networks with synthetic data**

  *Xiaotong Xu, Qian Li, Shuang Jin, Zhe Su, Yu Zhang*

  Journal of Radiation Research and Applied Sciences 2024. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1687850724000505?ref=pdf_download&fr=RR-2&rr=87277b24a85d3fcf)

+ **xU-NetFullSharp: The Novel Deep Learning Architecture for Chest X-ray Bone Shadow Suppression**

  *Vojtech Schiller, Radim Burgeta, Samuel Genzor, Jan Mizera, Anzhelika Mezina*

  Biomedical Signal Processing and Control 2025. [[PDF]](https://www.sciencedirect.com/science/article/pii/S1746809424010413)


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

+ **Development and Validation of a Deep Learning–Based Synthetic Bone-Suppressed Model for Pulmonary Nodule Detection in Chest Radiographs**
  
  *Hwiyoung Kim; Kye Ho Lee; Kyunghwa Han, PhD; Ji Won Lee; Jin Young Kim; Dong Jin Im; Yoo Jin Hong; Byoung Wook Choi; Jin Hur, MD, PhD*

  JAMA Network Open 2023. [[PDF]](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2800846)
  
+ **BSD: A multi-task framework for pulmonary disease classification using deep learning**

  *Sanli Yi, Shenglin Qin, Furong She, Dangguo Shao*

  Expert Systems With Applications 2025. [[PDF]](https://www.sciencedirect.com/science/article/pii/S095741742402222X)
## Datasets

### Dual Energy Subtraction(DES)
|     Dataset     |     Resolution    |       Class      |                  Collected                  | Private or Public |    #    |                                         Link                                         |
|:---------------:|:-----------:|:----------------:|:-------------------------------------------:|:-----------------:|:-------:|:------------------------------------------------------------------------------------:|
|  JSRT/BSE-JSRT  | 2048 × 2048 | Nodule/No Nodule | Japanese Society of Radiological Technology |       Public      |   247/240   |              https://www.kaggle.com/hmchuong/xray-bone-shadow-supression             |
| Gusarev M et.al |    Random   |       -----      |               Different online              |       Public      |    35   | https://drive.google.com/drive/folders/1VLD9deplqACJpdd47EdZCVW2BIN4eM95?usp=sharing |
| Yunbi Liu et.al |     ----    |       ----       |           Nanfang Hospital, China           |      Private      | 646/504 |                                         ----                                         |

For 240 paired JSRT original and bone suppressed images, you can also visit this [[website]](https://aistudio.baidu.com/aistudio/datasetdetail/234557).
### CT
|  Dataset  | Resolution |                       Classes                      |             Collected            | Private or Oublic |   #  |                                    Link                                    |
|:---------:|:----------:|:--------------------------------------------------:|:--------------------------------:|:-----------------:|:----:|:--------------------------------------------------------------------------:|
| LIDC-IDRI |   Random   | nodule >or =3mm,nodule < 3mm,non-nodule >or = 3mm  | The Cancer Imaging Archive(TCIA) |       Public      | 1018 | https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254 |
|   RIDER   |   Random   |                       Cancer                       | The Cancer Imaging Archive(TCIA) |       Public       |  154 |     https://wiki.cancerimagingarchive.net/display/public/rider+lung+ct     |

### CXR
|       Dataset      |  Resolution |                                                                Classes                                                                |                                                            Collected                                                            |     #    |                                                       Link                                                       |
|:------------------:|:-----------:|:-------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------:|:--------:|:----------------------------------------------------------------------------------------------------------------:|
|       Indiana      |  512 × 512  |                        Multiple diseases including opacity, cardiomegaly, pleural effusion, and pulmonary edema                       |        Indiana Network for Patient Care with various hospitals associated with the Indiana University School of Medicine        |   7470   |                       https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university                      |
|     ChestX-ray8    | 1024 × 1024 |           8 findings including pneumonia, atelectasis, mass, pneumothorax, infiltration, cardiomegaly, effusion, and nodule           |        From clinical PACS databases in the hospitals associated to NIHCC (National Institutes of Health Clinical Center)        |  108,948 | https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf |
|    ChestX-ray14    | 1024 × 1024 |            14 findings including hernia, consolidation, emphysema edema, pleural thickening, pulmonary fibrosis, and others           |        From clinical PACS databases in the hospitals associated to NIHCC (National Institutes of Health Clinical Center)        |  112,120 |                                 https://www.v7labs.com/open-datasets/chestx-ray14                                |
|     Montgomery     | 4020 × 4892 |                                                             Normal and TB                                                             |                                    Montgomery County Department of Health and Human Services                                    |    138   |                    https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-montgomery                    |
|      Shenzhen      | 3000 × 3000 |                                                             Normal and TB                                                             |                In collaboration with Shenzhen No. 3 People’s Hospital, Guangdong Medical College, Shenzhen, China               |    662   |                     https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen                     |
| RSNA-Pneumonia-CXR |    Random   |                                               Pneumonia, infiltration, and consolidation                                              |                   The RSNA (Radiological Society of North America) and the STR (Society of Thoracic Radiology)                  |  15,000  |                    https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data                   |
|    Pediatric-CXR   |    Random   |                                              Normal, bacterial-pneumonia, viral-pneumonia                                             |                                       Guangzhou Women and Children’s Medical Center, China                                      |   5856   |                      https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia                      |
|      Padchest      |    Random   |                                                        Large number of findings                                                       |                                                    San Juan Hospital (Spain)                                                    |  160,868 |                                  https://bimcv.cipf.es/bimcv-projects/padchest/                                  |
|      CheXpert      |    Random   | 14 findings including edema, cardiomegaly, lung opacity, lung lesion, consolidation, pneumonia, atelectasis, pneumothorax, and others |                                                Stanford University Medical Center                                               | 224,316  |                             https://stanfordmlgroup.github.io/competitions/chexpert/                             |
|       TBX11K       |  512 × 512  |                         5 findings including Healthy, Sick but Non-TB, Active TB, Latent TB, and Uncertain TB                         |                                     Paper: Rethinking Computer-aided Tuberculosis Diagnosis                                     |  11,200  |                                 https://www.kaggle.com/datasets/usmanshams/tbx-11                                |
|      MIMIC-CXR     | 2544 × 3056 |                                                 14 diseases (227,943 imaging studies)                                                 |                                   MIT, Beth Israel Deaconess Medical Center (Boston, MA, USA)                                   |  473,057 |                                  https://www.v7labs.com/open-datasets/mimic-cxr                                  |
|      VinDr-CXR     |    Random   |                      28 findings including TB, pneumonia, cardiomegaly, pleural effusion, lung opacity and others                     |                             The Hospital 108 (H108) and the HMUH (Hanoi Medical University Hospital)                            |  18,000  |                                           https://vindr.ai/datasets/cxr                                          |

### CXR(COVID)

| Dataset                       | Resolution | Classes                                                                   | Collected                                                                                                                       | #      | Link                                                                                                                 |
|-------------------------------|------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|--------|----------------------------------------------------------------------------------------------------------------------|
| COVIDx CXR-3                  | Random     | Positive and negative COVID-19                                            | Paper: COVIDx CXR-3: A Large-Scale, Open-Source Benchmark Dataset of Chest X-ray Images for Computer-Aided COVID-19 Diagnostics | 30,386 | https://www.kaggle.com/datasets/andyczhao/covidx-cxr2                                                                |
| COVIDx CXR-4                  | Random     | Positive and negative COVID-19, Non-COVID infections                      | Paper: COVID-Net: a tailored deep convolutional neural network design for detection of COVID-19 cases from chest X-ray images   | 84,818 | https://github.com/lindawangg/COVID-Net/blob/master/docs/COVIDx.md                                                   |
| COVID-QU-Ex                   | 256 X 256  | COVID-19, Non-COVID infections (Viral or Bacterial Pneumonia) and Normal  | Qatar University                                                                                                                | 33920  | https://www.kaggle.com/datasets/anasmohammedtahir/covidqu/                                                           |
| COVID-19 Radiography Database | 299 X 299  | COVID-19 positive cases, Non-COVID infections, Normal and Viral Pneumonia | Qatar University and the University of Dhaka                                                                                    | 3616   | https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database                                          |
| COVID-19-AR                   | Unclear    | Unclear                                                                   | The University of Arkansas for Medical Sciences (UAMS) Translational Research Institute                                         | 31935  | https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70226443#702264439f6e465db7e5421b8f47e08415e28227 |

**Obviously, there must have other datsets which are not displayed in these three tables. Let us know and we'll add them to this list if you find them.**

**By the way, [T. Weber et al.](https://arxiv.org/abs/2303.11224) provides an API called [MaCheX](https://github.com/saiboxx/machex) which is a composition of mutliple public chest radiography datasets.**
### Mask
|  Dataset  |  Resolution |  #  |                                           Link                                          |
|:---------:|:-----------:|:---:|:---------------------------------------------------------------------------------------:|
| JSRT Mask | 2048 × 2048 | 240 | https://www.kaggle.com/datasets/yoctoman/jsrt-original-and-bone-masks?resource=download |

## Acknowledges
Thanks to [Junjie Wang](<zayn_wang@163.com>) for providing us with more public CXR datasets!


## Some Additional Resources
### Bone Suppression
🎈[[Implementation and evaluation of a bony structure suppression software tool for chest X-ray imaging]](https://open.uct.ac.za/bitstream/handle/11427/11993/thesis_sci_2012_dixon_t.pdf?sequence=1&isAllowed=y)

✈️[[Bone Suppression Methods of ChestRadiographs Based on Deep ConvolutionalNetworks]](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C447WN1SO36whLpCgh0R0Z-iDdIt-WSAdV5IJ_Uy2HKRASwkzLAGLLtVEZ-SelJ51Hxf62QC3j-G2InLwUtUGiZw&uniplatform=NZKPT)

🌼[[Research on bone suppression of chest radiography]](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C475KOm_zrgu4lQARvep2SAk-6BvX81hrs37AaEFpExs0H61xq0Ry5eFrgGdZ6duZtCnOvbyB7URSgaHeE75Ii0j&uniplatform=NZKPT)

⛲[[Metting Notes of RSNA 2018: Multi-stage deep disassembling networks for generating bone-only and tissue-only images from chest radiographs]](https://docs.google.com/presentation/d/1dZB_IyeX4cto3Ly_H0VwtnyWjkqqAzdt/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true)

🤗[[CNN-ENABLED BONE SHADOW SUPPRESSION IN X-RAY IMAGING]]（https://scholarworks.calstate.edu/concern/projects/8g84mw45f）
