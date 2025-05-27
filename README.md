# Hierarchical Spatial-Frequency Fusion with Derived Features Branch for Camouflage Object Detection
## Overall 
In this paper, we propose HiSFFNet for camouflaged object detection, effectively addressing the challenges of high object-background similarity and boundary ambiguity through the integration of the Auxiliary Input Generation Module (AIGM) with its derived feature branch, the Hierarchical Guided Fusion Module (HGFM), and the Multi-scale Spatial-Frequency Deformable convolution module (MSFD). The core of HiSFFNet lies in the synergy of a "primary + derived" dual-branch feature encoder. The AIGM generates diverse input modalities to capture complementary information, enhancing object representation. The HGFM facilitates hierarchical cross-branch interactions to guide the intensity distribution of object pixels in the primary branch, establishing semantic connections across feature levels. Subsequently, in a multi-stage decoding pipeline, the original input is fused in a block-wise intra-group manner to supplement fine-grained intra-object details in the primary branch. The MSFD leverages multi-scale deformable convolutions and frequency fusion to capture edge contours, reduce uncertainty in boundary predictions, and filter spectral information from highly similar backgrounds, thereby improving segmentation accuracy. Experimental results demonstrate that HiSFFNet outperforms existing methods in camouflaged object detection and exhibits strong generalization capabilities across related tasks with similar characteristics.
![image](https://github.com/user-attachments/assets/3078f8e7-8345-4757-9167-fcb5eb5ce60b)
## Prepare Data
The COD datasets CAMO, CHAMELEON, COD10K, and NC4K are publicly available on the internet; detailed addresses are not provided here. If interested, you can obtain them according to the official instructions at the corresponding reference in the text.
## Code Available
After the article is published, the code will be organized and made publicly available soon. If interested, you can contact the author in advance to make a request, and collaboration is welcome.
## Results
![image](https://github.com/user-attachments/assets/1dfcc536-f4ec-430e-9b66-5a3cd65e4d3d)
![image](https://github.com/user-attachments/assets/4223754d-4818-47e9-a9d4-2ed4d4780b08)

## Prediction maps
The COD prediction results of our HiSFFnet are stored in Quark Drive. Please check follows.
Link：https://pan.quark.cn/s/60af2c804b70
Access code：jkQc

The Polpy prediction results of our HiSFFnet are stored in Quark Drive. Please check follows.
Link：https://pan.quark.cn/s/047fa4801fb3
Access code：35v7
