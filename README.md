# GSoC Deep Lense Tasks

The trained models for both the tasks can be found at the following Google Drive link: https://drive.google.com/drive/folders/1bEzLPteXPbo9fqSoHiutuf1FMVlUGCWf?usp=share_link

# Common Test I: Multi-class Classification

### Models Used:

| Deep Learning Model                         | Epochs | Batch Size | Learning Rate | AUC (OVO) | AUC (OVR) |
| :------------------------------------------ | :----- | :--------- | :------------ | :-------- | :-------- |
| DenseNet161                                 | 2      | 64         | 0.0001        | 0.97      | 0.97      |
| DenseNet161                                 | 6      | 64         | 0.0001        | 0.97      | 0.97      |
| DenseNet161                                 | 15     | 64         | 0.0001        | 0.98      | 0.98      |
| MobileVitV2_150                             | 15     | 32         | 0.0001        | 0.95      | 0.95      |
| DenseNet201                                 | 15     | 64         | 0.0001        | 0.97      | 0.97      |
| Ensemble_DenseNet161_DenseNet201            | 10     | 32         | 0.0001        | 0.98      | 0.98      |
| Combined (Averaged) Model Predictions       | -      | -          | -             | 0.99      | 0.99      |

### Final Results for Combined (Averaged) Predictions:

![image](https://user-images.githubusercontent.com/75483881/224155221-6dc22fe6-8290-46fc-b165-6794e159c2b8.png)

# Specific Test V: Exploring Transformers (Binary Classification)

### Models Used:

| Deep Learning Model                                 | Epochs | Batch Size | Learning Rate | AUC (OVO) | AUC (OVR) |
| :-------------------------------------------------- | :----- | :--------- | :------------ | :-------- | :-------- |
| ViT_Base_Patch_16_224                               | 20     | 64         | 0.0001        | 0.99800   | 0.99800   |
| Swin_Base_Patch4_Window7_224                        | 20     | 32         | 1e-05         | 0.99975   | 0.99975   |
| Ensemble_Swin_s3_Base_224_Swinv2_cr_Base_224        | 20     | 16         | 1e-05         | 0.99997   | 0.99997   |
| Combined (Averaged) Model Predictions               | -      | -          | -             | 1.00000   | 1.00000   |

### Final Results for Combined (Averaged) Predictions:

![image](https://user-images.githubusercontent.com/75483881/224155347-ede8969a-6f16-4e32-aa45-21cdd948c5d3.png)
