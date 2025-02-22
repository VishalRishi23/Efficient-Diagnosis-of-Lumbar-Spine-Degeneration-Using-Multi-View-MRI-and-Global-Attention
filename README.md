# Efficient-Diagnosis-of-Lumbar-Spine-Degeneration-Using-Multi-View-MRI-and-Global-Attention

This repository contains code notebooks that were used to train and evaluate all models mentioned in the manuscript

**Background:** Lumbar spine degeneration is a major cause of back pain and is one of the most common indications for spinal surgery. The high prevalence of degenerative spinal diseases leads to large societal costs from related treatment and disability. Though Magnetic resonance imaging (MRI), particularly T1- and T2-weighted images, is the gold standard for diagnosing lumbar spine degeneration due to its superior soft tissue, its interpretation can be very time-consuming and requires a high level of expertise. 

**Purpose:** To address the challenges of spinal MRI interpretation, we aim to develop deep neural networks with global attention maps trained on axial and sagittal views of spine MRI for automated grading of spinal canal stenosis, neural foraminal narrowing, and subarticular stenosis. Our work differs from other computer-aided diagnosis techniques in that our method learns global attention maps directly from MR images. Hence, our method does not require supervision from radiology experts to develop a separate segmentation model, saving the effort to acquire such annotations and reducing inference time. The global attention maps can also be investigated by radiology experts to assess the reasoning of the model behind a particular prediction. This enhances interpretability, without compromising on performance.

**Dataset:** Tyler Richards, Jason Talbott, Robyn Ball, Errol Colak, Adam Flanders, Felipe Kitamura, John Mongan, Luciano Prevedello, and Maryam Vazirabad.. RSNA 2024 Lumbar Spine Degenerative Classification. https://kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification, 2024. Kaggle.

**Pretrained models:**
1) [MaxViT (λ = 0.01)](https://www.kaggle.com/code/vishalrishi/maxvit-rmlp-tiny-rw-256-l0-01)
2) [MaxViT (λ = 0.1)](https://www.kaggle.com/code/vishalrishi/maxvit-rmlp-tiny-rw-256-l0-1)
3) [MaxViT (λ = 0.5)](https://www.kaggle.com/code/ch18b013/maxvit-rmlp-tiny-rw-256-l0-5)
4) [MaxViT (λ = 1.0)](https://www.kaggle.com/code/ch18b013/maxvit-rmlp-tiny-rw-256-l1-0)
5) [ResNet (λ = 0.01)](https://www.kaggle.com/code/vishalrishi/resnet34-a1-in1k-l0-01)
6) [ResNet (λ = 0.1)](https://www.kaggle.com/code/vishalrishi/resnet34-a1-in1k-l0-1)
7) [ResNet (λ = 0.5)](https://www.kaggle.com/code/ch18b013/resnet34-a1-in1k-l0-5)
8) [ResNet (λ = 1.0)](https://www.kaggle.com/code/ch18b013/resnet34-a1-in1k-l1-0)
9) [DenseNet (λ = 0.01)](https://www.kaggle.com/code/vishalrishi/densenet201-tv-in1k-l0-01)
10) [DenseNet (λ = 0.1)](https://www.kaggle.com/code/vishalrishi/densenet201-tv-in1k-l0-1)
11) [DenseNet (λ = 0.5)](https://www.kaggle.com/code/ch18b013/densenet201-tv-in1k-l0-5)
12) [DenseNet (λ = 1.0)](https://www.kaggle.com/code/ch18b013/densenet201-tv-in1k-l1-0)
13) [EfficientNet B5 (λ = 0.01)](https://www.kaggle.com/code/kalaivani04101977/efficientnet-b5-sw-in12k-l0-01)
14) [EfficientNet B5 (λ = 0.1)](https://www.kaggle.com/code/vishalrishi/efficientnet-b5-sw-in12k-l0-1)
15) [EfficientNet B5 (λ = 0.5)](https://www.kaggle.com/code/vishalrishi/efficientnet-b5-sw-in12k-l0-5)
16) [EfficientNet B5 (λ = 1.0)](https://www.kaggle.com/code/vishalrishi/efficientnet-b5-sw-in12k-l1-0)

**Global attention maps:**
![destination_path](https://github.com/user-attachments/assets/9a8abcf4-5ef9-4b9c-b4dd-94e2d6fa92a1)

**Note:**
While running trainer.ipynb, add this [dataset](https://www.kaggle.com/datasets/coopermini/rsna-v224) to the kernel as well
