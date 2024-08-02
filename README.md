
in this repo we fix titanic code

1-To fix the missing values in the "Age" column, you can fill them using the mean of the existing values:

<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١٠ ٥١ ٣٥ م" src="https://github.com/user-attachments/assets/cc4e7665-9aa8-451b-99ba-458774ea1569">

This code first calculates the mean of the "Age" column, then fills any missing values with that mean. The inplace=True argument ensures that the changes are made directly to the original DataFrame. Finally, the code checks if there are any remaining missing values in the "Age" column.


2- To fill the missing values in the "Embarked" column with the most frequent value (mode), you can use the following code:

<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١٠ ٥٦ ٢١ م" src="https://github.com/user-attachments/assets/e30595b2-9574-41ea-8f7a-7cb3052fd3f6">

This code calculates the mode of the "Embarked" column and fills any missing values with that mode. The inplace=True argument ensures that the changes are made directly to the original DataFrame. Finally, the code checks if there are any remaining missing values in the "Embarked" column.


-3 To drop the "PassengerId" and "Name" columns from the dataset, you can use the following code:
<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١١ ٠٤ ٠٧ م" src="https://github.com/user-attachments/assets/85662846-2d3b-42af-a834-09439723f6e9">
This code uses the drop method to remove the specified columns. The axis=1 argument indicates that columns are being dropped.


4- Checking for duplicates:

This code calculates the number of duplicate rows in the dataset and prints the result:

5- Dropping duplicates:

This code removes the duplicate rows from the dataset and prints the number of rows remaining after the duplicates are removed

<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١١ ١٥ ٠٧ م" src="https://github.com/user-attachments/assets/04d3926a-f5e7-4330-9c9c-04fa9d673a65">

6-


<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١١ ٤٨ ٤٣ م" src="https://github.com/user-attachments/assets/08f47dd7-27f6-4104-a913-ae5050a1fbbd">

7-

<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-٢٧ في ١١ ٥٢ ٤٩ م" src="https://github.com/user-attachments/assets/c1387b0f-12c2-4031-882f-c31a7955d474">
