# PRODIGY_ML_03
Implementing a support vector machine (SVM) to classify images of cats and dogs from the Kaggle dataset.

To build an image classifier using an SVM that can distinguish between cats and dogs based on image features.

Libraries Used:-
1. os, cv2, numpy: For loading and processing images.
2. sklearn: For training/testing split, SVM, scaling, and evaluation.
3. matplotlib: For displaying predictions.

Features:-
Images are resized to 64x64 pixels.
Flattened into vectors of size 64 × 64 × 3 = 12,288.
Standardized before training the SVM.

Significance:-
Shows how SVMs can be applied to image data, though not ideal for large/high-res images.
Demonstrates feature flattening, label encoding, and normalization for SVM.
Can be extended using HOG features, PCA, or a CNN for better performance.
