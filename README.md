# Brain-Tumor-SVM-Classifier
Machine learning project that classifies brain tumor cases using Support Vector Machine (SVM) with data preprocessing, visualization, and model evaluation.

1. Developed a machine learning model to classify brain tumor cases using a Support Vector Machine (SVM) algorithm.
2. Used a dataset containing 6,000 records and 9 columns, with different numerical features related to tumor characteristics.
3. The dataset includes features such as Mean Intensity, Intensity STD, Texture Contrast, Homogeneity, Energy, Entropy, Tumor Area, and Perimeter.
4. Performed data exploration and preprocessing using Pandas to understand the dataset structure, data types, and statistical information.
5. Checked for missing values, and the dataset contained no null values in the available features.
6. Removed duplicate records to improve the quality and consistency of the dataset.
7. Used box plots and visualizations to examine the distribution of numerical features and identify potential outliers.
8. Converted the categorical Tumor_Class into numerical labels using Label Encoding, with classes including Glioma, Meningioma, No Tumor, and Pituitary.
9. Applied StandardScaler to normalize the input features, then split the data into 80% training and 20% testing using stratified sampling.
10. Trained an SVM classifier and evaluated its performance using metrics such as accuracy, classification report, and confusion matrix.
