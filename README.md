Purplehoney team members: Jiarong Li, Shaoyue Yang, Xinyue Zhang, Ryan Gupta

Project Summary: We developed a deep learning framework for predicting standardized Centiloid scores from 3D amyloid PET scans. Our approach uses a 3D ResNet50 backbone with multi-scale feature fusion to capture both local and global spatial patterns of amyloid deposition. To address variability introduced by different PET tracers, tracer-aware modeling is incorporated through learnable tracer embeddings and a cross-attention mechanism. The model is trained using AdamW optimization, mixed-precision training, gradient clipping, and early stopping. Mean Absolute Error (MAE) is used as both the training objective and primary evaluation metric.

# VI-LUAD
The VI-LUAD challenge focuses on predicting vascular invasion status from whole slide pathology images of lung adenocarcinoma patients. The primary task is binary classification:
| Label      | Index | Description                                          |
| ---------- | ----- | ---------------------------------------------------- |
| NONVITUMOR | 0     | Tumor slide from a patient WITHOUT vascular invasion |
| VITUMOR    | 1     | Tumor slide from a patient WITH vascular invasion    |
