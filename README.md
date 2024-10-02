# Evaluating the Impact of Machine Learning Platforms on Cancer Classification Model Performance: A Cross-Platform Comparative Study
In response to the growing need for improved diagnostic efficiency in cancer care, machine learning (ML) techniques have become instrumental in advancing predictive models for early detection. However, variations in model performance have been observed, even when using the same dataset, raising the question of whether choice of platform influences ML outcomes. This study addresses that gap by evaluating the impact of three different ML implementation platforms SciKit-Learn, Knime Analytics, and MATLAB on the performance of four classification algorithms: Logistic Regression (LR), Decision Tree (DT), Random Forest (RF), and Gradient Boosting (GB). Using the publicly available Wisconsin Diagnostic Breast Cancer (WDBC) dataset, the algorithms were deployed on each platform, operating under default configurations, to compare performance across key metrics: accuracy, recall, precision, and F1-Score. 
The results revealed significant variations across platforms. SciKit-Learn consistently demonstrated higher recall values, particularly for Random Forest and Gradient Boosting, making it more effective in minimizing false negatives, which is critical in cancer diagnosis. MATLAB exhibited strong precision, especially with Random Forest and Gradient Boosting, suggesting its potential in reducing false positives. Knime, while effective in certain cases, generally showed lower recall and precision across algorithms, raising concerns in scenarios where both metrics are critical. These findings highlight the influence of platform choice on model performance and emphasize the importance of selecting an appropriate platform based on the specific requirements of a predictive task, particularly in healthcare, where the balance between false positives and false negatives can have significant implications for patient outcomes. The source code and data for this study are made fully available through a public GitHub repository



## Dataset Source
Link to the UCI Wisconsin Breast Cancer Dataset (Dataset):
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic



Dataset overview.

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/9b34c204-7f40-4a11-b0ad-637dac8b1f72)



## Methodology
The flowchart below represents the methodology followed in this project.
![image](https://github.com/user-attachments/assets/105b3f3d-9aed-4e51-a4b7-cc27d1c40447)






Scatterplot showing relationship between some of the features.


![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/86d105f5-a56b-474d-8f95-79a48d7ed70e)






## Results collected
Below are table of results showing the performances of the four algorithms when implemented on both Knime and Scikit-Learn. 

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/a1c3aa15-e88f-405c-a847-cc76f602563a)



![image](https://github.com/user-attachments/assets/30966cca-154f-4faa-ad34-b48ed2e9b183)







The Confusion Matrix

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/1cbcd659-b90b-49db-9bbf-fa3c657f189d)

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/ed0a10a0-4268-4927-8e63-81542b198a97)


![image](https://github.com/user-attachments/assets/3087526c-3e2d-42cc-a98e-d20b1997d693)





## Visualization of algorithm performances assessed

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/4c05715f-c15d-4da5-a3ca-f4c9a7fa3163)


![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/022f3636-6e34-444c-9dbd-dc34a2347f01)



![image](https://github.com/user-attachments/assets/01792989-ed30-44ff-b417-4cdceaf9f91d)







