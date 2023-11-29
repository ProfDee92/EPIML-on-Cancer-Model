# Cancer-(3IPMLM) Investigating the Impact of the Implementation Platform on Machine Learning Models)
In the context of global cancer prevalence and the imperative need to improve diagnostic efficiency, this study addresses a critical question: does the choice of development platform for machine learning models impact their performance in cancer diagnosis? 
With cancer, particularly breast cancer, representing a significant global health concern, delays in diagnosis have been identified as a major obstacle to reducing morbidity. 
Scientists have turned to machine learning techniques to tackle this challenge to expedite diagnosis processes.
Although previous research has shown promising results in developing predictive models for faster cancer diagnosis, discrepancies in outcomes have emerged, even when employing the same dataset.
However, the underlying factors contributing to these variations remain unexplored. Therefore, this investigation seeks to shed light on whether inherent platform features influence the performance of 
machine learning algorithms and whether healthcare professionals should be meticulous in their choice of implementation platform.
This study utilizes the publicly available WDBC dataset from the UCI data repository to train four machine learning algorithms (Logistic Regression, Decision Tree, Random Forest, and Gradient Boosted Trees) on two distinct platforms: Python SciKit-Learn and Knime Analytics. 
The algorithms' performance is rigorously assessed and compared, with both platforms operating under their default configurations. 
The results reveal disparities in accuracy, with Logistic Regression achieving the highest accuracy of 92.11% in Knime, while Gradient Boosted Trees outperforms the others with an accuracy of 97.37% in Python. 
In general, Python consistently yields higher accuracy across all algorithms when compared to Knime. 
These findings underscore the impact of platform selection on machine learning model performance, emphasizing the need for thoughtful consideration when choosing a platform for predictive models’ development.
Such a decision bears significant implications for model efficacy and, ultimately, patient outcomes in the healthcare industry.

## Dataset Source
Link to the UCI Wisconsin Breast Cancer Dataset (Dataset):
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## Methodology
The flowchart below represents the methodology followed in this project.

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/ec73170f-ea60-4ad2-b824-636d97909488)

## Results collected
Below are table of results showing the performances of the four algorithms when implemented on both Knime and Scikit-Learn. 
![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/c0e7de46-dd86-4269-bdd9-d43cb73c4c3f)

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/b5f2e543-0d8d-4397-bb2e-9b7d9b585801)


## Visualization of algorithms performances assessed

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/eefb18fc-61f8-4dfa-b506-cc4ed7c11dee)

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/f47f218c-494f-4107-a93a-7cd540e355ef)

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/e41b5b9e-8f5c-4cca-9f1c-5d9ff9bd2e39)

![image](https://github.com/ProfDee92/Cancer-3IPMLM/assets/103885055/738ce710-1ce3-4619-95e0-a50fc38b4584)






