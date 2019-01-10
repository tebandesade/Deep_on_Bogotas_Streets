# Deep_on_Bogotas_Streets
This repository contains the software used for my undergraduate thesis

# Description
The repo is divided into two: 
    * FasterRCNN : that contains https://github.com/roytseng-tw/Detectron.pytorch and is the implementation of Facebook's Detectron, which has Faster R-CNN in Pytorch 
    * RetinaNet  : that contains https://github.com/fizyr/keras-retinanet and is the implementation of Facebooks's RetinaNet in Keras 


# Faster R-CNN
The new files in this work are: 

* Detectron.pytorch/tools/
    * Detectron.pytorch/tools/infer_evaluation.py
    * Detectron.pytorch/tools/parse_location_dataset.py
    * Modified file Detectron.pytorch/tools/train_net_step.py
    * Modified file Detectron.pytorch/tools/test_net.py

* Detectron.pytorch/lib/datasets/
    * Detectron.pytorch/lib/datasets/mio_json_dataset_evaluator.py
    * Modified file Detectron.pytorch/lib/datasets/dummy_datasets.py
    * Modified file Detectron.pytorch/lib/datasets/task_evaluation.py
    * Modified file Detectron.pytorch/lib/datasets/dataset_catalog.py

* Detectron.pytorch/Data/*
