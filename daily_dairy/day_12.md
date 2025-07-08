**DAY 12(08/07/2025)**

Today we focused on data preprocessing and preparation, which is a vital step before feeding any data into a machine learning model. The goal was to understand how to clean, transform, and prepare raw data into a form suitable for training.

1) **Handling Missing Values:** There are 2 methods for handling missing values- **Dropping** Missing Values (Remove the rows or columns that contain NaN) and **Imputation**(Replace the missing values using mean, median, or mode).

2) **Data Standardization:** Standardization ensures all features contribute equally by bringing them to a common scale.

3) **Label Encoding (Categorical to Numeric):** ML models only work with numbers. So categorical text labels (like “Plastic”, “Metal”, etc.) must be converted to numeric values. Label Encoding does this by assigning each unique category an integer.

4) **Train-Test Split:** To check how well the model generalizes to new unseen data, we split our dataset into:

   a) **Training set**: For model learning

   b)**Test set**: For evaluation

5) **Handling Imbalanced Datasets:** If one class appears much more than others then the model might ignore the minority class. So, we use Undersampling for this where we reduce the majority class to balance the dataset. It may lead to loss of data, but it is helpful when data is large.

6) **Feature Extraction:** For text data, we can’t use raw text in models. So we use TF-IDF to convert text into numeric vectors by measuring how important a word is in a document compared to the entire dataset.

   TF (term frequency) = how often a word appears

   IDF (inverse document frequency) = how rare the word is across documents

   It is used in tasks like spam detection, document classification, etc.


