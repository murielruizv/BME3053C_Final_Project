**<h1>Parkinson's Disease Prediction Using Random Forest</h1>**


This project uses a Random Forest Classifier to predict Parkinson's disease based on vocal biomarker data. The code reads data, trains a model, evaluates it using various metrics, and visualizes the results.

**<h2>Table of Contents</h2>**
**1.** Requirements


**2.** Setup Instructions


**3.** How to Run


**4.** Outputs

**<h3>1. Requirements</h3>**
**Python:** Version 3.8 or higher.


**Libraries:**

pandas

numpy

scikit-learn

matplotlib

seaborn


**<h3>2. Setup Instructions</h3>**


**2.1.** Prepare the Dataset: Ensure the dataset file (parkinsons.data) is in CSV format with the required columns:

Features: MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), etc.
Target: status (1 for Parkinson’s, 0 for healthy).
The dataset is already available in this reporsitory. This dataset was obtain from the UC Irvine Machine learning reporsitory website, this is the link for direct acces to the dataset: https://archive.ics.uci.edu/dataset/174/parkinsons 

**2.2.** Upload the Dataset:
Since the code is designed for Google Colab, you will need to upload the dataset manually
Run the files.upload() command in Colab.
Select and upload the parkinsons.data file.

**2.3** Inspect the Dataset:
Verify that the dataset has been loaded correctly by printing its columns and a preview of the data.

**<h3>3. How to Run</h3>**


**3.1** Load and Preprocess Data

- The code reads the dataset using _pandas_.


- Features and target columns are separated for training and evaluation.

**3.2** The data will be splitted


- The data is split into training and testing sets using an 80-20 split.

**3.2** Train the Model


- A Random Forest Classifier is trained on the training data.

**3.3** Make Predictions


- The model predicts the status for the test set.

**3.4** Evaluate the Model


- A confusion matrix and classification report are generated.

  

**3.5** Precision and recall are calculated.

- A confusion matrix heatmap is plotted.

  
- A bar chart of precision, recall, and F1-score for each class is created.


**<h3>4. Outputs</h3>**

**Confusion Matrix:**
A matrix displaying true positives, true negatives, false positives, and false negatives.

**Heatmap:**
A heatmap visualization of the confusion matrix.

**Classification Report:**
Precision, recall, F1-score, and support for each class.

**Bar Chart:**
A bar chart showing precision, recall, and F1-score for each class.


