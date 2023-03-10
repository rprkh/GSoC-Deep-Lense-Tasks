# GSoC Deep Lense Tasks

The trained models for both the tasks can be found at the Google Drive link: https://drive.google.com/drive/folders/1bEzLPteXPbo9fqSoHiutuf1FMVlUGCWf?usp=share_link

# Common Test I: Multi-class Classification

### Models Used:

| Deep Learning Model              | Epochs | Batch Size | Learning Rate | AUC (OVO) | AUC (OVR) |
| :------------------------------- | :----- | :--------- | :------------ | :-------- | :-------- |
| DenseNet161                      | 2      | 64         | 0.0001        | 0.97      | 0.97      |
| DenseNet161                      | 6      | 64         | 0.0001        | 0.97      | 0.97      |
| DenseNet161                      | 15     | 64         | 0.0001        | 0.98      | 0.98      |
| MobileVitV2_150                  | 15     | 32         | 0.0001        | 0.95      | 0.95      |
| DenseNet201                      | 15     | 64         | 0.0001        | 0.97      | 0.97      |
| Ensemble_DenseNet161_DenseNet201 | 10     | 32         | 0.0001        | 0.98      | 0.98      |

Final Combined (Averaged) AUC (OVO) = **0.99**

Final Combined (Averaged) AUC (OVR) = **0.99**

### Final Results for Combined (Averaged) Predictions:

![image](https://user-images.githubusercontent.com/75483881/224155221-6dc22fe6-8290-46fc-b165-6794e159c2b8.png)

# Specific Test V: Exploring Transformers (Binary Classification)

### Final Results for Combined (Averaged) Predictions:

![image](https://user-images.githubusercontent.com/75483881/224155347-ede8969a-6f16-4e32-aa45-21cdd948c5d3.png)
