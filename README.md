 Here I have worked with a simple dataset representing gene expression levels. Gene expression levels are calculated by the ratio between the expression of the target gene (i.e., the gene of interest) and the expression of one or more reference genes (often household genes). This dataset is synthetic and specifically designed to show some of the strengths and limitations of using KNN for Classification.
 
 **OBJECTIVE**
--------------------------

By Looking on genes our model will need to predict that whether a person having a Cancer or Not (0 for negative and 1 for Positive)

**Dataset**
---------------------------
This datset has been taken from [sciencedirect]( https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/gene-expression-level)

**About the Dataset**
--------------------------

Datset contains two features that is gene1 and gene2 and a target variable Cancer Present

**Model Accuracies:**
-------------------------
I have used KNN model for Classifying cancer disease - 

| Model        | Accuracy       | precision  |  recall  | f1-score |
| ------------- |:-------------:|:-------: | :-------: |  :------:
| KNearestNeighbors(KNN) | 0.94     |  0.93(0) and 0.95(1) | 0.95(0) and 0.92(1)|0.94(0) and 0.93(1)

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)
