## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![DS exp 3 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/730729ab-9b66-4548-83b4-972186ad429f)
![DS exp 3 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/f02df8f1-e4a5-4179-8c8e-f7cc16bd144a)
![DS exp 3 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/87b7025c-022d-4dac-b826-161b62730521)
![DS exp 3 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/5b86879b-4ea4-49be-91ff-ec95797b3da2)
![DS exp 3 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/4a4f7228-95dd-4b1d-a3a5-5134af470363)
![DS exp 3 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/36fc4b51-3a7f-4d81-a02d-7bb9b52b69d9)
![DS exp 3 ipynb - Colab_page-0007](https://github.com/user-attachments/assets/f0910719-eb1d-4a1e-b05a-e1feb57b4ab4)
![DS exp 3 ipynb - Colab_page-0008](https://github.com/user-attachments/assets/34b0a36b-f78b-4091-af92-923f17c259ab)
![DS exp 3 ipynb - Colab_page-0009](https://github.com/user-attachments/assets/126d3d1b-3ca0-454e-9cae-66695aeaae41)

       
# RESULT:
       Thus we have read and performed Feature Encoding and Transformation process and save the data to a file.

       
