
# Breast_cancer_ml_project





Here we are going to predict  whether the tumor is cancerous or not.
### What is a tumor?

A tumor is a mass or group of abnormal cells that form in the body. 

## First lets look at types of tumors:


![514240-article-img-malignant-vs-benign-tumor2111891f-54cc-47aa-8967-4cd5411fdb2f-5a2848f122fa3a0037c544be](https://github.com/NAUSHEEN6/Breast_cancer_ml_project/assets/109889514/49ec9412-6828-4998-8f4f-81c1a6148ea8)
    BENIGN TUMOR                                               |      MALIGNANT TUMOR                           |
|-------------------------------------------------              |------------------------------------------------|                                               
|  1) Non cancerous                                             |   1) Cancerous                                              |
|  2)Capsulated                                                 |   2)Non Capsulated                                             |
|  3)Non invasive                                               |   3) Abnormal shape                                              |
|  4)Slow growing                                               |   4) Fast Growing
|  5)do not metastasize[Spread to other parts of the body]      |   5) Metastasize                                 |
|  6) Cells are normal                                            | 6) Cells have large and dark nuclei                                               |

## Work flow:
```mermaid
graph TD;
    Dataset collection--> Data Preprocessing;
    Data Preprocessing-->Tran and Test split;
    Tran and Test split-->Train Logistic Regression;
    Train Logistic Regression--> Model;

```
                                       











