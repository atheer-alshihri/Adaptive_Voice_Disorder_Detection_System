# Adaptive Voice Disorder Detection System
Voice disorder detection systems traditionally rely on static machine learning models, which face challenges when speech characteristics evolve over time. 
This study proposes an adaptive AI-driven voice disorder detection framework that incorporates real-time feedback and incremental learning to enhance classification accuracy and clinical applicability. 
The system extracts acoustic features such as jitter, shimmer, and MFCCs, and employs Support Vector Machines and Random Forest classifiers as base models. 
Adaptation mechanisms, including clinician feedback incorporation and drift detection via ADWIN, enable dynamic model refinement without full retraining.
Experimental evaluations demonstrate an improvement in classification accuracy from 51% to 56% after feedback integration, with notable enhancements in recall and precision.
Latency analysis confirms rapid model updates (0.003 seconds), supporting real-time clinical deployment. 
The findings validate the effectiveness of adaptive learning techniques in maintaining robust voice disorder classification performance under evolving input conditions. Future directions include expanding the system to multi-class disorder classification and integrating with telehealth platforms.
