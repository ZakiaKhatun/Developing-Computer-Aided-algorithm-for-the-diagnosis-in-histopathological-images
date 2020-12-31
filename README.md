# Developing-Computer-Aided-algorithm-for-the-diagnosis-in-histopathological-images
## Design of a Computer Aided Diagnosis system to classify histopathological images in benign vs malignant patches.


The main objective of this project was to design a Computer Aided Diagnosis system to develop a deep learning algorithm for diagnosis in histological patches to classify benign vs malignant patches. 

**System architecture**:
- Image → Normalization → Per instance standardization → Aggressive Data Augmentation → Classification. 

**Steps**
- Data normalization,
- Per instance standardization (Standardization by mean and std of the training dataset),
- Aggressive Data Augmentation (Horizontal flip, Vertical flip), and 
- Classification; Best performing classification model- ResnNet50 (ImageNet-pretrained).

Note: This project was the project of the third semester of my master's in the 'Computer Aided Diagnosis' course.
