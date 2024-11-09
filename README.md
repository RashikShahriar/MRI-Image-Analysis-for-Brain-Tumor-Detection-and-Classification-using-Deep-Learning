# MRI-Image-Analysis-for-Brain-Tumor-Detection-and-Classification-using-Deep-Learning

### Description 
This project uses deep learning models to analyze MRI images to detect and classify brain tumors. Specifically, the project uses multiple models **Multi-Layer Perceptron (MLP), AlexNet CNN, and InceptionV3** to categorize brain MRI scans into four classes: **glioma, meningioma, pituitary tumor, and no tumor**. The models were evaluated based on various performance metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Loss, Accuracy, and F1-Score.

The AlexNet CNN model achieved the highest F1-Score (0.411368) and demonstrated promising accuracy. At the same time, InceptionV3 showed the highest accuracy (0.886320) with relatively low loss, making it a strong candidate for tumor detection and classification tasks. The Multi-Layer Perceptron model, although not as accurate as the CNN-based models, provided a baseline for comparison in performance.

### Dataset Structure
The dataset is organized as follows:
- **Training:** This folder contains four subfolders representing different classes: glioma, meningioma, no_tumor, and pituitary_tumor.
- **Testing:** This section contains images divided into two classes, No and Yes, indicating the presence or absence of a tumor.
- **Tumor-Mask:** This holds masks for specific tumor types (glioma, meningioma, pituitary tumor) for use in segmentation tasks.

### Dataset Summary
- **Training Data:** 1935 images across four classes.
- **Validation Data:** 484 images across four classes.
- **Testing Data:** 1038 images across four classes.
