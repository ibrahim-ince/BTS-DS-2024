# BTS-DS 2024: Brain Tumor Segmentation Dataset 2024
This repository contains the dataset and source code accompanying the paper:

If you use this dataset or code, please cite:

Kurt Pehlivanoğlu, M., İnce, İ., Kından, B.A. et al. Towards advanced brain tumor segmentation: a novel hybrid architecture integrating UNet, FCN, and YOLO models on the newly introduced BTS-DS 2024 dataset. Eur. Phys. J. Spec. Top. (2025). https://doi.org/10.1140/epjs/s11734-025-01698-6

📄 [Read the paper](https://doi.org/10.1140/epjs/s11734-025-01698-6)  

- **Dataset – BTS-DS 2024**
  - 3956 MRI images (T1, T1C+, T2)
  - 14 tumor classes (Astrocytoma, Glioblastoma, Meningioma, etc.)
  - Polygon-based segmentation masks in JSON format

- **Segmentation Models**
  - Classical: UNet, ResUNet, FCN32, VGG16-UNet Hybrid
  - Detection: YOLOv8, YOLOv9, YOLOv11 (all variants tested)

- **Training & Evaluation**
  - Preprocessing (augmentation, CLAHE, blurring, etc.)
  - Hyperparameter configs for UNet & YOLO models
  - Metrics: Accuracy, Precision, Recall, F1, IoU, mAP (50–95)
 
  
