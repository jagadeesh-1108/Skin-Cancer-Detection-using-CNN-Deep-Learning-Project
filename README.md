# Skin-Cancer-Detection-using-CNN-Deep-Learning-Project
# Goal of the Project:
The main Goal of this project is to build a deep learning system that can identify the specific type of skin cancer from medical images. Instead of simply telling whether a case is cancerous or not, the project focuses on pinpointing the exact cancer category, which is far more useful in real medical practice. To achieve this, three models — ResNet50, VGG16, and a custom CNN experiment — were trained and compared. Among them, the best model VGG16 achieved an impressive 96% accuracy, showing the strong potential of AI in assisting with precise cancer classification.

# Process

Dataset Collection – Gathered a dataset of skin cancer images representing multiple cancerous categories.

Preprocessing – Standardized the images through resizing, normalization, and cleaning for consistent input.

Data & Image Augmentation – Applied techniques such as rotation, flipping, zooming, and shifting to increase dataset variability and prevent overfitting.

Model Building:
1)Random Forest: Implemented as a baseline classical machine learning approach for comparison.

2)Deep Learning Models: Built and tested using pretrained CNN architectures – ResNet50 and VGG16 – along with a custom CNN experiment (Copy_of_2017_(1).ipynb).

Training & Validation – Trained the models with augmented datasets, fine-tuned parameters, and validated performance using hold-out validation data.

Testing – Evaluated the final models on unseen test data to measure generalization performance.

Evaluation Metrics – Assessed models using accuracy, precision, recall, F1-score, and confusion matrix.

Results – Compared models, with VGG16 achieving the highest performance at 96% accuracy in classifying skin cancer types.


# Features of the Project

Focused on classifying skin cancer into specific cancerous types rather than just cancer vs. non-cancer.

Implemented multiple models: Random Forest (baseline), VGG16, ResNet50, and a custom CNN.

Used transfer learning with pretrained architectures for better accuracy and efficiency.

Applied image augmentation to improve generalization and reduce overfitting.

Achieved 96% accuracy with VGG16, proving the strength of deep learning in medical image analysis.

# Final Results

Random Forest – Used as a baseline traditional machine learning model; accuracy was lower compared to deep learning approaches.

Custom CNN – Built and trained from scratch in multiple experiments; performed better than Random Forest but less effective than pretrained architectures.

ResNet50 – Produced good results and handled deeper feature extraction well, but did not surpass VGG16.

VGG16 – Achieved the highest performance with 96% accuracy, making it the most effective model for classifying skin cancer into specific types.

The Achieved 96% accuracy highlights the effectiveness of deep learning in medical imaging. ResNet50 performed better due to its residual connections, enabling deeper learning without vanishing gradients, making it highly suitable for critical applications like skin cancer detection.

# Conclusion

This project successfully demonstrates the use of deep learning and transfer learning for medical image classification, achieving 96% accuracy in skin cancer detection. The results prove that AI-based approaches can significantly aid in early diagnosis and healthcare decision-making, providing a reliable tool for dermatological analysis.


