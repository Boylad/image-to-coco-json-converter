## Introduction
This code transforms segmentation mask images to annotation JSON files as per the COCO structure http://cocodataset.org/#format-data

I followed [this](http://www.immersivelimit.com/tutorials/create-coco-annotations-from-scratch) as a guide when writing the script.

## Dataset used: Ecole Centrale Paris (ECP) Facade
The original images and annotations used in this repo are available at: http://martinovi.ch/datasets/ECP_newAnnotations.zip

## Visual result in Detectron2
Register the dataset to detectron2, following the [detectron2 custom dataset tutorial](https://detectron2.readthedocs.io/tutorials/datasets.html).

| ![Original](https://github.com/chrise96/image-to-coco-json-converter/blob/master/dataset/train/monge_12.jpg) | ![mask](https://github.com/chrise96/image-to-coco-json-converter/blob/master/dataset/train_mask/monge_12.png)|![COCO](https://github.com/chrise96/image-to-coco-json-converter/blob/master/dataset/removethis/coco.png) |
|:---:|:---:|:---:|