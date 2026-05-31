# From Pneumonia to Multi-Disease: Interpretable and Uncertainty-Aware Semi-Supervised Learning Strategies for Chest X-Ray Classification

## Authors

**Samiha Muntaha Mahin**  
Department of Computer Science and Engineering  
International Islamic University Chittagong (IIUC), Bangladesh  
Email: c223201@ugrad.iiuc.ac.bd

**Tahmina Hasan**  
Department of Computer Science and Engineering  
International Islamic University Chittagong (IIUC), Bangladesh  
Email: c223213@ugrad.iiuc.ac.bd

Sara Karim

Maksura Binte Rabbani Nuha

Ekramul Haque Tusher

Abdur Rahman

Jia Uddin

Debasish Ghose

## Abstract

Pneumonia is a deadly respiratory disease that causes millions of deaths each year worldwide. Chest
X-ray imaging is one of the most widely used and affordable tools available for screening pneumonia.
However, accurate diagnosis can often be complicated because pneumonia shares similar radiographic
features with other respiratory illnesses such as COVID-19 and tuberculosis, leading to potential confusion
and misdiagnosis in high-volume clinical environments. To address these issues, this study proposes an
automated approach for chest X-ray disease identification by comparing supervised and semi-supervised
learning techniques across two publicly available datasets. Experiments were conducted under both binary
(Normal vs. Pneumonia) and multiclass (COVID-19, Normal, Pneumonia, Tuberculosis) classification
settings. The proposed framework integrates MobileNet-based architectures with modern pseudo-labeling
methods, including FixMatch, FlexMatch, and FreeMatch. In supervised experiments, the models achieved
up to 98% accuracy in binary classification and 97% in multiclass classification, with MobileNetV3Small
selected for its lightweight architecture and deployment efficiency. Under limited labeled data settings,
FreeMatch demonstrated the most stable SSL performance, achieving 97% accuracy using only 20% labeled
data in binary classification and 95% accuracy using only 30% labeled data in multiclass classification,
while maintaining lower variance and improved class balance compared to competing methods. Model
interpretability was evaluated using Grad-CAM, confirming that predictions were primarily focused on
clinically relevant lung regions. In addition, predictive reliability was assessed using Monte Carlo Dropout,
Expected Calibration Error (ECE), and Test-Time Augmentation, demonstrating improved confidence
calibration and robustness. Overall, the proposed framework shows that lightweight deep learning models
combined with semi-supervised learning, uncertainty estimation, and explainability can provide accurate,
efficient, and clinically reliable solutions for automated chest X-ray diagnosis.
