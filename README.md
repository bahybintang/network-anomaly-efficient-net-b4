# android-malware-classification
Dataset Source: 
- https://www.kaggle.com/datasets/subhajournal/android-malware-detection?tags=13302-Classification 
- https://archive.ics.uci.edu/dataset/855/tuandromd+(tezpur+university+android+malware+dataset)
- https://archive.ics.uci.edu/dataset/722/naticusdroid+android+permissions+dataset

The dataset contains four labels namely Android_Adware, Android_Scareware, Android_SMS_Malware and Benign. The dataset includes 355630 entries or instances (rows) with 85 columns. The data has been scrapped from CIC repository. Presently, the data has the following label distribution:

| Class              |  Total  |
|--------------------|:-------:|
|Android_Adware      |  147443 |
|Android_Scareware   |  117082 |
|Android_SMS_Malware |  67397  |
|Benign              |  23708  |
|--------------------|:-------:|
|Total All Class     |  355630 |

In this study we used 80% of the dataset as training data and 20% for testing data. This division allows the researcher to examine how the model performs when given limited data training examples and when trained at a larger data level. The dataset is processed using several data normalization (scaling) techniques, data preprocessing, and sampling techniques with the aim of determining a combination of techniques that produces a better level of accuracy. Following are some of the data normalization algorithms, data processing, and sampling techniques used in this study.

| Technique                        |  Algorithm                                 |
|----------------------------------|:------------------------------------------:|
|Normalization Data (Scaling)      |  Min-Max Normalization                     |
|                                  |  Standardization (Z-Score Normalization))  |
|Data Preprocessing                |  Principal Component Analysis (PCA)        |
|Data Sampling                     |  Random Under Sampling                     |
|                                  |  Random Over Sampling                      |
|                                  |  SMOTE                                     |
