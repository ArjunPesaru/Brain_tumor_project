# Brain_tumor_project
# Brain_tumor_project

Brain tumor segmentation is a critical task in medical imaging that aids in diagno- sis and treatment planning. This project aims to develop an innovative deep learn- ing model for accurate and robust brain tumor segmentation using multi-modal 3D MRI scans. Our approach centers on a 3D Convolutional Neural Network (CNN) architecture, specifically a modified U-Net, designed to process volumetric data from multiple MRI modalities simultaneously.
The proposed method incorporates several advanced techniques: a multi-modal 3D CNN architecture that takes inputs from T1, T2, FLAIR, and DWI scans, with a feature fusion module to combine information effectively; an attention mech- anism [4] integrated into the decoder path to focus on relevant tumor regions, improving segmentation accuracy and reducing false positives; transfer learning to leverage pre-trained weights from large medical imaging datasets, enhancing the model’s generalization capabilities; explainable AI techniques, specifically Gradient-weighted Class Activation Mapping (Grad-CAM), to provide visual ex- planations of the model’s predictions; and post-processing using Conditional Ran- dom Fields (CRF) to refine tumor boundaries.
By combining these techniques, we aim to push the boundaries of automated brain tumor segmentation, potentially improving diagnostic accuracy and treat- ment planning in clinical scenarios. The resulting model could contribute signifi- cantly to medical image analysis and have practical implications for patient care.

Literature Survey
• Isensee et al. (2021) - a self-adapting U-Net for medical image segmentation.
• Zhou et al. (2019) - UNet++, a nested U-Net architecture for better segmentation accuracy. • Myronenko (2018) - 3D MRI brain tumor segmentation with autoencoder regularization.
• Oktay et al. (2018) - Attention U-Net for improved multi-class image segmentation.

Potential Datasets
IEEE DataPort BraTS MICCAI dataset: A multimodal MRI collection for brain tumor segmentation research. Kaggle BraTS 2020 dataset: Pre-operative MRI scans for brain tumor segmentation used in the BraTS 2020 challenge.

3 Plan of Activities (October 8th - December 10th, 2024)
In Weeks 1-2, Vinod will organize the dataset, apply data augmentation, and conduct initial model training and validation. During Weeks 3-4, he will evaluate the model and analyze Grad-CAM visualizations. Simultaneously, in Weeks 1-3, Arjun will develop a 3D U-Net with multi-modal inputs and integrate attention mechanisms. In Weeks 4-5, he will fine-tune hyperparameters and apply CRF post-processing. Finally, in Weeks 6-7, We will complete report and documentation.
4 Expected Outcomes
• A novel 3D multi-modal CNN architecture for brain tumor segmentation.
• Improved segmentation accuracy compared to existing 2D and single-modal approaches. • Interpretable results through attention mechanisms and Grad-CAM visualizations.
• A comprehensive analysis of the model’s performance on different tumor types and sizes.
Preprint. Under review.


References
[1] B. H. Menze, A. Jakab, S. Bauer, J. Kalpathy-Cramer, K. Farahani, J. Kirby, et al., ”The Multi- modal Brain Tumor Image Segmentation Benchmark (BRATS)”, IEEE Transactions on Medical Imaging, 34(10), 1993-2024 (2015). DOI: 10.1109/TMI.2014.2377694
[2] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. S. Kirby, et al., ”Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features”, Nature Scientific Data, 4:170117 (2017). DOI: 10.1038/sdata.2017.117
[3] GLISTRboost method, which won first prize at the International Multimodal Brain Tumor Im- age Segmentation challenge 2015 (BraTS’15).
[4] S. Bakas, H. Akbari, A. Sotiras, M. Bilello, M. Rozycki, J. Kirby, et al., ”Segmentation Labels and Radiomic Features for the Pre-operative Scans of the TCGA-GBM collection”, The Cancer Imaging Archive, 2017. DOI: 10.7937/K9/TCIA.2017.KLXWJJ1Q
[5] GLISTR (GLioma Image SegmenTation and Registration) software, which forms the basis for GLISTRboost.
[6] F. Isensee, P. F. Jaeger, S. A. A. Kohl, J. Petersen, K. H. Maier-Hein, ”nnU-Net: a self- configuring method for deep learning-based biomedical image segmentation”, Nature Methods, 18(2), 203-211 (2021).
[7] Z. Zhou, M. M. R. Siddiquee, N. Tajbakhsh, J. Liang, ”UNet++: A Nested U-Net Architecture for Medical Image Segmentation”, IEEE Transactions on Medical Imaging, 39(6), 1935-1946 (2020).
[8] A. Myronenko, ”3D MRI Brain Tumor Segmentation Using Autoencoder Regularization”, In- ternational MICCAI Brainlesion Workshop, 311-320 (2018).
[9] O.Oktay,J.Schlemper,L.L.Folgoc,M.Lee,M.Heinrich,K.Misawa,etal.,”AttentionU-Net: Learning Where to Look for the Pancreas”, Medical Image Computing and Computer Assisted Intervention – MICCAI 2018, 11070, 3-10 (2018).
[10] Y. LeCun, Y. Bengio, G. Hinton, ”Deep learning”, Nature, 521(7553), 436-444 (2015).
