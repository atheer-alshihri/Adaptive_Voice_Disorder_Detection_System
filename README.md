# Adaptive Voice Disorder Detection System
Voice disorder detection systems traditionally rely on static machine learning models, which face challenges when speech characteristics evolve over time. 
This study proposes an adaptive AI-driven voice disorder detection framework that incorporates real-time feedback and incremental learning to enhance classification accuracy and clinical applicability. 
The system extracts acoustic features such as jitter, shimmer, and MFCCs, and employs Support Vector Machines and Random Forest classifiers as base models. 
Adaptation mechanisms, including clinician feedback incorporation and drift detection via ADWIN, enable dynamic model refinement without full retraining.
Experimental evaluations demonstrate an improvement in classification accuracy from 51% to 56% after feedback integration, with notable enhancements in recall and precision.
Latency analysis confirms rapid model updates (0.003 seconds), supporting real-time clinical deployment. 
The findings validate the effectiveness of adaptive learning techniques in maintaining robust voice disorder classification performance under evolving input conditions. Future directions include expanding the system to multi-class disorder classification and integrating with telehealth platforms.
                                                  ![image](https://github.com/user-attachments/assets/2f598f16-dda0-4d0c-9f92-72b52f43b305)

# Datasets
This dataset comprises vocal audio recordings from both healthy individuals and patients diagnosed with specific vocal disorders. It serves as a valuable resource for developing machine learning models aimed at detecting and classifying voice-related health conditions.
Key Features:
Audio Samples: The dataset includes recordings from individuals with and without vocal disorders, providing a balanced set for training and evaluation.
Vocal Disorders Covered: Specifically, the dataset contains samples related to conditions such as Laryngocele and vocal cord issues, which are critical for studying voice pathologies.
Data Format: Audio files are provided in standard formats suitable for processing with various audio analysis tools and machine learning frameworks.

https://www.kaggle.com/datasets/subhajournal/patient-health-detection-using-vocal-audio/data


