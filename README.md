# PTL-AI Furnas Dataset: A Public Dataset for Fault Detection in Power Transmission Lines Using Aerial Images


This repo stores the PTL-AI Furnas Dataset from the paper: [PTL-AI Furnas Dataset: A Public Dataset for Fault Detection in Power Transmission Lines Using Aerial Images](https://ieeexplore.ieee.org/abstract/document/9991806).

<!-- This repo stores the PTL-AI Furnas Dataset from the paper: [PTL-AI Furnas Dataset: A Public Dataset for Fault Detection in Power Transmission Lines Using Aerial Images](http://sibgrapi.sid.inpe.br/col/sid.inpe.br/sibgrapi/2022/09.22.22.53/doc/oliveira-33_inpe.pdf). -->


This paper has been accepted for presentation at SIBGRAPI 2022.

[Download PTL-AI Furnas Dataset here.](https://drive.google.com/file/d/1JfVxRV6C0vwLTBhW-C97fwj4gawraGHe/view?usp=sharing)

#### Checkpoints for tensorflow-based models are listed below:

- [Faster-RCNN with Inception](https://drive.google.com/file/d/1IicN0pIV33-3Z-17knrir9ldZx3kfV8-/view?usp=sharing)
- [Faster-RCNN with ResNet 152](https://drive.google.com/file/d/1AsPiiq5IIVXzWJ3QewD7BTQ29plB83j0/view?usp=sharing)
- [Faster-RCNN with ResNet 101](https://drive.google.com/file/d/1Pj5FaCFW4qt7BZreSZiish92kYAEn98H/view?usp=sharing)
- [SSD with ResNet 152](https://drive.google.com/file/d/15qwPU259B9cQC1otfFtOpG7Yyg8jreTL/view?usp=sharing)
- [SSD with ResNet 101](https://drive.google.com/file/d/1Fl6TWfrdN_ZfCTNUqZiqYCfG4hCuZHGH/view?usp=sharing)
- [SSD with ResNet 50](https://drive.google.com/file/d/1XCA-86Ve0lBaxsHvpe1jxFxkWCwUnlAf/view?usp=sharing)

The source-code for training can be accessed [here](https://github.com/freds0/fault_detection_power_transmission_lines).

#### Checkpoints for pytorch-based models are listed below:

- [YOLO V5S6](https://drive.google.com/file/d/1xyo-fT2hfDpVG1YYgX7RUNMhpf07ncI3/view?usp=sharing)
- [YOLO V5M6](https://drive.google.com/file/d/1PA2QPgY8BKugsuAuLfEEPMpXbMWDA-vW/view?usp=sharing)
- [YOLO V5L6](https://drive.google.com/file/d/1fGNbIyHX0HVrbIrHLBxoO0ft55bZTmcr/view?usp=sharing)

The source-code for training can be accessed [here](https://github.com/freds0/yolov5).


## Abstract
We present a new images dataset called PTL-AI Furnas Dataset as a new benchmark for fault detection in power
transmission lines. This dataset is composed of five components: baliser, bird nest, insulator, spacer and stockbridge, which have
different states. The images were extracted from real process of maintenance of Furnas power transmission lines. Furnas is
a company that generates or transmits electricity to 51% of households in Brazil and more than 40% of the nation’s electricity passes through their grid enabling generating the dataset in different backgrounds and climatic conditions. We performed experiments using data augmentation techniques to train Faster R-CNN, Single-Shot Detects (SSD) and YoloV5 models, with distinguished set of parameters. The benchmark result was obtained using the metrics of Mean Average Precision (mAP)
and the Mean Average Recall (mAR) with values mAP=91.9% and mAR=89.7%.

## Datasets Statistics

![statistics](imgs/statistics.png) 

## Dataset Samples

![samples](imgs/samples.png)

## Annotated Samples

![annotated_samples](imgs/annotated_samples.png)


# Acknowledgment
	
We would like to thank the [CyberLabs](https://cyberlabs.ai/) and [CEIA/UFG](https://inf.ufg.br/p/39527-centro-de-excelencia-em-inteligencia-artificial-ceia) for financial support for this paper and [Eletrobras-Furnas](https://www.furnas.com.br/) for providing a specialized technical team, support and also the images used to create PTL-AI Furnas Dataset.

<p align="center">  
  <img src="https://files.cercomp.ufg.br/weby/up/1/o/Marca_UFG_cor_completa_horizontal.png" alt="Logo UFG" width="200"><img src="https://files.cercomp.ufg.br/weby/up/1218/o/CEIA_transparente.png" alt="Logo CEIA" width="250"><img src="http://www.ecbsa.com.br/img/site/clientes/17.jpg" alt="Logo Eletrobras-Furnas" width="300">
</p>
