# Neuronal cell instance segmentation

This study project was a part of Computational Neuroscience course at the University of Tartu. We participated in [Kaggle competition](https://www.kaggle.com/c/sartorius-cell-instance-segmentation/overview) from Sartorius company.
Project workflow, data description, results are published in [Medium blog](https://medium.com/@ekaterinasedykh/neuronal-cell-segmentation-66b66898c379)

## Content
We've proceeded with 2 models: U-Net and Mask R-CNN, you can find training and inference notebooks under corresponding directory.

### Mask R-CNN
The model based on Detectron2 was used. Initial dataset annotations neede to be converted to COCO format to be easily compatible with Detectron2, so [data](https://www.kaggle.com/ekaterinasedykh/sartorius-coco) in COCO format was used.

