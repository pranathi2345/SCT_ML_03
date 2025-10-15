# SCT_ML_03
Implement a support vector machine (SVM) to classify images of cats and dogs from the kaggale dataset
"""
1. Objective:
   Implement an SVM model to classify images of cats and dogs using the Kaggle dataset.
2. Tools Used:
   - Python (numpy, pandas, matplotlib)
   - scikit-learn (for SVM and preprocessing)
   - OpenCV or PIL (for image processing)
   - os (for file handling)
3. Steps:
Step 1: Data Loading and Preprocessing
   - Load images of cats and dogs from Kaggle dataset directories.
   - Resize images to a fixed size (e.g., 64x64 pixels) to standardize input.
   - Convert images to grayscale or flatten RGB channels.
   - Normalize pixel values (e.g., scale to 0-1 range).
Step 2: Label Encoding
   - Assign numeric labels to classes (e.g., 0 for cats, 1 for dogs).
Step 3: Feature Extraction
   - Flatten image matrices into 1D feature vectors for SVM input.
Step 4: Train-Test Split
   - Split dataset into training and testing sets (e.g., 80% train, 20% test).
Step 5: Model Training
   - Initialize and train the SVM classifier with training data.
   - Use kernels like linear or RBF based on performance.
Step 6: Model Evaluation
   - Predict labels for test set.
   - Calculate accuracy, confusion matrix, and classification report.
Step 7: Visualization (Optional)
   - Plot sample images with predicted labels.
   - Visualize confusion matrix.
Outcome:
   - Trained SVM model classifies cat and dog images with reasonable accuracy.
"""
  
 
