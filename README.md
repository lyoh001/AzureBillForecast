# COVID-19 Xray
## 1. Introduction
### 1.1	Background

![Figure 1: Covid19-Xray](./.images/image.png)
The 2019 novel coronavirus (COVID-19) presents several unique features. While the diagnosis is confirmed using polymerase chain reaction (PCR), infected patients with pneumonia may present on chest X-ray and computed tomography (CT) images with a pattern that is only moderately characteristic for the human eye Ng, 2020. COVID-19’s rate of transmission depends on our capacity to reliably identify infected patients with a low rate of false negatives. In addition, a low rate of false positives is required to avoid further increasing the burden on the healthcare system by unnecessarily exposing patients to quarantine if that is not required. Along with proper infection control, it is evident that timely detection of the disease would enable the implementation of all the supportive care required by patients affected by COVID-19.

In late January, a Chinese team published a paper detailing the clinical and paraclinical features of COVID-19. They reported that patients present abnormalities in chest CT images with most having bilateral involvement Huang 2020. Bilateral multiple lobular and subsegmental areas of consolidation constitute the typical findings in chest CT images of intensive care unit (ICU) patients on admission Huang 2020. In comparison, non-ICU patients show bilateral ground-glass opacity and subsegmental areas of consolidation in their chest CT images Huang 2020. In these patients, later chest CT images display bilateral ground-glass opacity with resolved consolidation Huang 2020.

COVID is possibly better diagnosed using radiological imaging Fang, 2020 and Ai 2020.

## 2 Content
### 2.1	Dataset
The dataset consists of a posteroanterior (PA) view of chest X-ray images comprising Normal, Viral, and CVOID-19 affected patients. There are total 1823 CXR images.


## 3 Covid19 Classification using Convolutional Neural Networks
- [Notebook using Mobilenet_v2](https://github.com/lyoh001/DLCovid19/blob/main/notebook/notebook_mobilenet_v2.ipynb)

- [Notebook using CNN](https://github.com/lyoh001/DLCovid19/blob/main/notebook/notebook_cnn.ipynb)


## 4 Mobilenet_v2 Reference
https://tfhub.dev/google/tf2-preview/mobilenet_v2/classification/4


## 5 Citation
### 5.1	Acknowledgements
- Joseph Paul Cohen and Paul Morrison and Lan Dao. COVID-19 image data collection, arXiv, 2020. https://github.com/ieee8023/covid-chestxray-dataset

- https://github.com/JordanMicahBennett/SMART-CT-SCAN_BASED-COVID19_VIRUS_DETECTOR/

- D. Kermany, K. Zhang, M. Goldbaum, Large dataset of labeled optical coherence tomography (oct) and chest x-ray images, Mendeley Data, v3
http://dx. doi. org/10.17632/rscbjbr9sj 3 (2018).

- C. J. P, P. Morrison, D. L, Covid-19 image data collection, arxiv, arXiv preprint arXiv:2003.11597 (2020). URL https://github.com/ieee8023/covid-chestxray-dataset

- Z.-H. Chen, Mask-rcnn detection of covid-19 pneumonia symptoms by employing stacked autoencoders in deep unsupervised learning on low-dose
high resolution ct (2020). doi:10.21227/4kcm-m312.URL http://dx.doi.org/10.21227/4kcm-m312
-  D. S. et.al, Covid19action-radiology-cxr (2020). doi:10.21227/s7pw-jr18.
URL http://dx.doi.org/10.21227/s7pw-jr18
