## EXNO-3-DS
NAME:VENKATA MOHAN N
REF NO: 24900969

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
![image](https://github.com/user-attachments/assets/93c1e733-cbb4-4eac-b286-aac7edf2fa79)
![image](https://github.com/user-attachments/assets/089f8484-80c6-43fa-8dfb-1e0e3ec3ef51)
![image](https://github.com/user-attachments/assets/50f02760-f70e-491c-a6c5-11eefffb6631)
![image](https://github.com/user-attachments/assets/ae6ea5df-2246-434e-938f-629d8f8c014b)
![image](https://github.com/user-attachments/assets/52a5c461-5f2e-4968-a1f8-9114c9b844b1)
![image](https://github.com/user-attachments/assets/83472c2f-aa86-4fdb-8e07-641ef761e87b)
![image](https://github.com/user-attachments/assets/f1936867-8f37-4c58-b53c-d4d894ef51ed)
![image](https://github.com/user-attachments/assets/81285af6-5269-4ba7-b9f1-bf10cbd1f115)
![image](https://github.com/user-attachments/assets/a9fb28bc-6320-4057-a5d4-2244d9be58e8)
![image](https://github.com/user-attachments/assets/ce0d11b9-cf66-4bb0-bd86-4465d19a700a)
np.sqrt(df["Highly positive skew"])
![image](https://github.com/user-attachments/assets/85405384-7dd2-4f30-b86c-f4ea54a70f79)
![image](https://github.com/user-attachments/assets/03214f67-e75f-4fc5-962c-ae2253b8dd96)
![image](https://github.com/user-attachments/assets/59382a8b-e2b5-44a8-b05c-43dd562e7c79)
![image](https://github.com/user-attachments/assets/f7f61f72-11a2-48c3-a6eb-f89ef37cbf96)
![image](https://github.com/user-attachments/assets/ec6c032e-d270-429d-a1a1-38095538c42a)
![image](https://github.com/user-attachments/assets/e119237e-1f3b-413f-8879-edb05d4e739b)
![image](https://github.com/user-attachments/assets/b3952a1a-2632-48cb-b9f0-d4b9fca975b1)
![image](https://github.com/user-attachments/assets/ee342301-17bd-4ea8-aae2-843da5755e4d)
![image](https://github.com/user-attachments/assets/f5ec8ba9-7c33-482d-9947-ec2c75b6da9c)
![image](https://github.com/user-attachments/assets/cae499e6-94b6-4dde-ba86-fc2d77618e62)
![image](https://github.com/user-attachments/assets/6be9c5c4-f7e1-4910-bea1-9c05b23b6fe2)

# RESULT:
      THUS THE GIVEN DATA ,FEATURE ENCODED,TRANSFORMATION PROCESSED

       
