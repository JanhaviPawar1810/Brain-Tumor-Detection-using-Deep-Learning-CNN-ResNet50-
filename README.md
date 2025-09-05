# Brain-Tumor-Detection-using-Deep-Learning-CNN-ResNet50
This project aims to detect brain tumors from MRI scans using deep learning. Early detection of tumors can significantly improve patient survival.

Two models are implemented:
•	Sequential CNN – simple yet effective for feature extraction and classification.
•	ResNet50 – pre-trained deep network using residual connections to handle complex features.
________________________________________
Dataset 
•	Source: Kaggle (3,000 MRI images)
o	Tumor: 1,500
o	No Tumor: 1,500 (some removed for balance)
•	Split: 60% train, 20% validation, 20% test
Preprocessing includes grayscale conversion, resizing (244x244), cropping, and data augmentation (rotation, zoom, flip).

Link to Dataset: https://drive.google.com/drive/folders/10SGlLBzK52qavFX4BOvdx4eyl-21-FrA?usp=sharing
________________________________________
Model Performance
Model	Test Accuracy	F1 Score
Sequential CNN	85.06%	0.7209
ResNet50	74.54%	0.7209
Conclusion: Sequential CNN outperforms ResNet50 in test accuracy, making it the preferred choice for MRI tumor detection.
________________________________________
Usage
1.	Clone the repo: git clone https://github.com/yourusername/brain-tumor-detection.git
2.	Run the notebook: jupyter notebook Brain_Tumor_Detection.ipynb
