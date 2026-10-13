# SkillCraft Technology – Machine Learning Internship

## Task 3: Cats vs Dogs Image Classification Using SVM

### Project Overview
This project builds an image classification model to distinguish between cat and dog images using image preprocessing, Principal Component Analysis (PCA), and a Support Vector Machine (SVM).

### Objective
- Load and preprocess cat and dog images.
- Convert images into numerical features suitable for machine learning.
- Reduce feature dimensionality using PCA.
- Train an SVM classifier.
- Evaluate the model on a held-out test set.

### Dataset
The project uses the Cats and Dogs image dataset. Update this section with the exact dataset source used in your project.

Expected folder structure:
```text
PetImages/
├── Cat/
└── Dog/
```

### Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

### Workflow
1. Load images from the Cat and Dog folders.
2. Resize images to a consistent size and convert them to grayscale.
3. Flatten images into feature vectors.
4. Split the data into training and testing sets.
5. Apply PCA to reduce the number of features.
6. Train an SVM classifier.
7. Evaluate predictions using accuracy, a classification report, and a confusion matrix.
8. Save the trained model and evaluation outputs.

### Model
**Support Vector Machine (SVM):** A supervised learning algorithm used to classify images into the two categories: Cat and Dog.

**Principal Component Analysis (PCA):** Reduces feature dimensionality while retaining useful variation in the data.

### Evaluation
The notebook evaluates the classifier using:
- Accuracy
- Precision, recall, and F1-score
- Confusion matrix

Add the actual test accuracy and any other results from your notebook here. Results depend on the sampled images, preprocessing, and train/test split.

### Project Structure
```text
SCT_ML_3/
├── README.md
├── SCT_ML_Task3_Cats_vs_Dogs.ipynb
├── confusion_matrix.png
├── sample_predictions.png
├── artifacts/
└── results/
```

Adjust filenames and folders to match the files in your repository. Do not upload the full image dataset or ZIP file unless you specifically intend to distribute it.

### How to Run
1. Download and extract the dataset into the expected `PetImages/Cat` and `PetImages/Dog` folders.
2. Install the dependencies:
   ```bash
   pip install opencv-python-headless numpy matplotlib scikit-learn joblib jupyter
   ```
3. Update the dataset path in the notebook for your computer.
4. Open the notebook:
   ```bash
   jupyter notebook SCT_ML_Task3_Cats_vs_Dogs.ipynb
   ```
5. Run the cells in order.

### Learning Outcomes
- Image preprocessing with OpenCV.
- Converting images into machine-learning features.
- Dimensionality reduction with PCA.
- Image classification using SVM.
- Model evaluation and result visualization.

### Conclusion
This project demonstrates a classical machine-learning workflow for binary image classification, from preprocessing cat and dog images to training and evaluating an SVM model.

### Internship Details
- **Organization:** SkillCraft Technology
- **Domain:** Machine Learning
- **Task:** Task 3
